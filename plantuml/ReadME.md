# PlantUML使用指南

## 最简单的使用方法

打开URL[PlantUML Server](http://www.plantuml.com/plantuml/uml/)即可，里面还有外链。

## VS Code集成方法（Windows 10）

搜索扩展`PlantUML`安装第一个，在插件设置中`Render`选择`PlantUMLSever`为提交到[PlantUML Server](http://www.plantuml.com/plantuml/uml/)渲染。选择`Local`则需要安装java环境并设置`JAVA_HOME`环境变量，安装graphviz并设置`GRAPHVIZ_DOT`环境变量为安装目录下的`\bin\dot.exe`。

语言模式选择为`Diagram`，文件后缀名`.wsd` `.pu` `.puml` `.plantuml` `.iuml`等。

## 样式编辑

在代码中输入`!include 文件名`包含样式代码文件，例如：

`@startuml`

`!include style.puml`

`代码`

`@enduml`

## 语法？

比如活动图的官方参考 [活动图](https://plantuml.com/zh/activity-diagram-beta)，里面还有其他的，UML绝对够用。

语言规范总页面 [语言规范](https://plantuml.com/zh/sitemap-language-specification)，可以查看各种语法。