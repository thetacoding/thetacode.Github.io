[toc]

# java基础



## 一、java的基本程序设计类型

### 数据类型

- 基本类型

  - 整型

    - byte / 1
    - short / 2
    - int / 4
    - long / 8

  - 浮点类型

    - float / 4

    - double / 8

    > 浮点类型不适用于无法接收舍入误差的金融计算。如果计算中不允许有任何误差，应该使用BigDecimal类

  - char类型

    - char / 2
    
    > [unicode编码机制](extension/unicode编码机制.md)
    >
    > 在Java中，char类型描述了UTF-16编码中的一个代码单元，所以是2个字节
    >
    > 强烈建议不要在程序中使用char类型，除非确实需要处理UTF-16代码单元

  - boolean类型

    - boolean / true or false
    
    > 整型与布尔值之间不能进行相互转换

- 包装类型

  > 基本类型都有对应的包装类型，基本类型与其对应的包装类型之间的赋值使用自动装箱与拆箱完成。
