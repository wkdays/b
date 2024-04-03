# a Project Container

> ==一个想法的实现==，从**想法**开始，去做一个**实现**想法的拓展过程，一个想法就是一个高层的构架开始。
>
> ==什么== ==怎么做== ==结果==
>
> 

## 开始于一个想法

> [!tip]
>
> 这里需要一个理论的书籍支撑我的开始理论依据。
>
> 

``` mermaid
---
	title "流程图"
---
flowchart LR
	w1(从一个想法开始)-->w2(
	1、组织的协同渠道
	2、知识的管理工具
	)
```

```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'default' } }%%
timeline
        title 开始搭建平台
          开始: 一个想法: 一个平台: 沟通: 汇总: 分析
          2005 : Youtube
          2006 : Twitter
          2007 : Tumblr
          2008 : Instagram
          2010 : Pinterest

```

组织：

```mermaid
sequenceDiagram
		人->>人: 沟通、方法论
    想法->>+工具: 组织、流程
    工具-->>-结果: 自动化

```

```mermaid
journey
    title 一个想法的实现
    section 想法组织表现
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section 业务运营
      Go downstairs: 5: Me
      Sit down: 5: Me
```

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :active,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :until isadded
    Functionality added                 :milestone, isadded, 2014-01-25, 0d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h

```

```mermaid
%%{init: {"pie": {"textPosition": 0.5}, "themeVariables": {"pieOuterStrokeWidth": "5px"}} }%%
pie showData
    title Key elements in Product X
    "Calcium" : 42.96
    "Potassium" : 50.05
    "Magnesium" : 10.01
    "Iron" :  5

```

```mermaid
gitGraph TB:
  commit id:"step1"
  branch dev
  commit id:"做什么" tag:"什么"
```

```mermaid
mindmap
Root
    A
      B
      C
```

```mermaid

```

