# 高可读性的HTML
## 编写高语义的HTML代码最佳实践
1. 熟悉所有规范中的HTML标签，理解各标签的语义，在合适的地方使用合适的标签
2. 熟悉各标签上规范的属性，给HTML标签设置必要的属性，例如alt和title
3. 样式和结构分离
4. 给空标签中添加隐藏文字，用于说明标签的实际功能

**关于img与background**，如果图片是作为页面内容的一部分，则应该使用img元素，如果图片仅仅是起装饰作用，这应该使用背景图片方式。

# 如何设置网页标题层级
1. 在页面内容的标题部分使用<hx>标签
2. 页面中只是用一个h1标签
3. hx标签使用过程中不要跳级，把不在页面中显示的标题隐藏，而不是删除
4. 不要单纯使用hx标签给内容设置样式

# 如何正确设计表单
## **关于label**
- label用于为输入控件定义文本标签label----即显示在输入控件旁边的说明性文字
- 用label元素定义的文本标签，从显示上看与其他文本毫无差异。不过，他为鼠标用户增强了可用性:当用户点击由label元素定义的文本标签时，该文本标签关联的输入控件将获得焦点
- 要为label指定关联的输入控件，只需要把相关的控件的id赋值给label，标签的for属性

## fieldset元素给表单控件分组。形成一个控件组。
##legend元素定义控件组的标题

## 提高表单易用性的手段
1. 使用label标签，并设置label标签的for属性
2. label元素上的鼠标事件会转移到相关联的输入控件上，这一特性为鼠标用户增强了可用性。
3. 给输入控件设置合适的水印提示----placeholder属性
4. 如有必要，给输入控件设置tab顺序----tabindex属性
5. 使用Html5中引入的表单控件(url, email, date, search和number)

## 精简html代码
1. 删除多余的容器
2. 装饰性的元素使用css样式实现
3. 避免table布局

## 常见的块状元素:div, p, table, ul, ol, h1~h6等
## 常见的行内元素:span,img,a,em,input,select
