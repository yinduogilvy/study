# 前端标签中英文对照

| 标签名称 | 标签英文 | 标签解释 | 标签使用示例| 标签使用规范 |
|---------|-------|------|--------|-------|
| html | HyperText Markup Language |  超文本传输协议 | ```<html></html>``` | 标签对，一个页面只出现一次|
| head | head | 规定文档相关的通用信息 ,提供给浏览器 或者 蜘蛛爬虫使用 | ```<head></head>``` | 标签对 |
| meta | meta | 元信息，文档的相关信息，作者等 | ```<meta name="" content=""/>``` | 单标签 ，放在head标签对里面|
| style | style | 页面CSS样式 | ```<style></style>``` | 标签对，放在 head 标签对里面|
| link | link | 引用外部CSS样式文件 | ```<link rel="stylesheet" href="css文件路径"/>```| 单标签，放在 head标签对里面 |
| script | script | 脚步标签，JavaScript (JS)脚本 | ```<script></script>``` ```<script src="外部JS 的路径"><script>``` | 放在head标签对里面或者 body标签对里面或者后面 |
| body | body | 页面主体内容，显示在浏览器中  | ```<body></body>``` | 标签对  |
| h1~h6 | heading | 标题(Heading)元素拥有六个不同的级别，\<h1\> 是最高级的，而 \<h6\> 则是最低的级别 | ```<h1>字体最大</h1>``` ```...``` ```<h6>字体最小</h6>``` | 标签对 |
| a | anchor | 超链接 | ```<a href="超链接地址">需要超链接的文字或者图片等</a>``` | 标签对 |
| p | paragraph | 段落 | ```<p></p> ```| 标签对  |
| ol | order list | 有序列表 | ```<ol></ol>``` | 标签对 |
| ul | unorder list | 无序列表 | ```<ul></ul>``` | 标签对 |
| li | list item | 列表项目 | ```<li></li>``` ```<ul><li></li>....<li></li></ul>``` ```<ol><li></li>....<li></li></ol>``` | 标签对 ，必须放在 ol或者ul标签对里面 |
| dl | definition list | 定义列表，用于 解释名词 | ``` <dl></dl>```| 标签对 |
| dt | definition list term/title | 要定义的术语 | ```<dt>前端工程师</dt>```` | 标签对,必须放在dl中 |
| dd | definition list description | 要定义的解释 | ```<dd>前端工程师就是XXXX</dd>```` ```<dl><dt></dt><dd></dd>....<dt></dt><dd></dd></dl>| 标签对,必须放在dl中 |
| div | division | 分割区域 | ```<div></div>```` | 主要用于 页面布局分割，没有实际意义 |
| span | span | 范围 | ```<span></span>``` | 用于 无意义的 内容包含|
| form | form | 表单 | ```<form></form>``` | 表单，用户将用户的信息提交 |
| input | input | 输入框 ，单行| ```<input type="text"/>``` | 用于用户输入内容 |
| select | select | 下拉框 | ```<select></select>``` | |
| option | option | 选项，放在 select 标签对中 | ```<select><option></option></select>``` |必须放在 select/optgroup标签里面 |
| optgroup | option group | 对选项进行分组，放在 select 标签对中 | ```<select><optgroup><option></option></optgroup></select>``` |必须放在 select标签里面 |
| textarea |textarea | 多行文本输入框 | ```<textarea></textarea>``` | 多行文本输入框 |
| label | label | 标签 | ```<label></label>``` | 仅用于 对 input 输入框的解释 |
| button | button | 按钮 | ```<button>我是一个按钮</button>``` | 按钮，属性type="submit"时，用于提交表单内容|
|img | image | 图片 | ```<img src="图片地址" /> ``` | 标签对 |
|table | table| 表格 | ```<table></table>```` | |
|tr | table row| 表格行 | ```<table><tr></tr> </table>```` | 必须放在 table 标签对里 |
|td | table data cell| 单元格 | ```<table><tr><td></td></tr></table>```` | 必须放在 tr 标签对里 |
|th | table header cell| 表格的表头,与td相同，只不过文字 加粗 | ```<table><tr><th></th></tr></table>```` | 必须放在 tr 标签对里 |
| audio | audio | 音频 | ```<audio src="">您的浏览器不支持audio</audio>``` | 音频 |
| video | video | 视频 | ```<video src="">您的浏览器不支持video</video>``` | 视频 |


