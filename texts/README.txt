课文数据放在这个文件夹，一课一个文件：

  lesson01.json
  lesson02.json
  ...
  lesson30.json

文件由「课文编辑器 text_editor.html」生成，不要手写，格式如下：

{
  "lesson": 7,
  "texts": [
    {
      "title": "课文一",
      "sentences": [
        { "zh": "我是学生。", "py": ["wǒ", "shì", "xué", "shēng", "。"] }
      ]
    }
  ]
}

py 数组必须和 zh 的字符一一对应（标点也要占一位）。
网页会自动判断第 1–10 课直接显示拼音，第 11 课起改为点「？」查看。
