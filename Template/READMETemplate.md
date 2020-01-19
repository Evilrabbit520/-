复制下方内容拼接在分类后面即可，需要填写的内容是{单词}、{音频链接}、{音标}、{中文释义}、{文件名}

填写方法：

- 单词：新的，没有重复(master分支中不存在)的单词(记得首字母大写);
- 音频链接：使用这个链接`http://dict.youdao.com/dictvoice?audio={word}&type={id}`，将链接中的{word}改为单词，{id}改为，master分支中README.md文件当前字母分类中的排序序号，(从0开始的)，例如：`http://dict.youdao.com/dictvoice?audio=word&type=0`;
- 音标：可以去[有道翻译](https://dict.youdao.com/)直接复制;
- 中文释义：同样可以去[有道翻译](https://dict.youdao.com/)直接复制,每个词性只需要复制一个贴切编程相关的即可(例如：Access中n.使用权;v.访问(名词和动词));
- 文件名：就是这个单词(记得首字母大写);

```text
| 单词 [🔊](音频链接) | ⚓[音标] | 中文释义 | [详情](Detailed/{文件名}.md) |
```
将这个写好添加在README.md文档中后请参考[DetailedInterpretationTemplate.md模板](DetailedInterpretationTemplate.md)