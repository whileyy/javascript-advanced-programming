# JavaScript高级程序设计中的一些关键词概览

### [MIME 类型（IANA 媒体类型）](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Basics_of_HTTP/MIME_types"MDN")

> 媒体类型（也通常称为多用途互联网邮件扩展或 MIME 类型）是一种标准，用来表示文档、文件或一组数据的性质和格式。

### **[IEEE](https://zh.wikipedia.org/wiki/%E7%94%B5%E6%B0%94%E7%94%B5%E5%AD%90%E5%B7%A5%E7%A8%8B%E5%B8%88%E5%8D%8F%E4%BC%9A "电气电子工程师协会")二进制浮点数算术标准**（**IEEE 754**）

> 是20世纪80年代以来最广泛使用的[浮点数](https://zh.wikipedia.org/wiki/%E6%B5%AE%E9%BB%9E%E6%95%B8 "浮点数")运算标准，为许多[CPU](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%A4%AE%E8%99%95%E7%90%86%E5%96%AE%E5%85%83 "中央处理单元")与[浮点运算器](https://zh.wikipedia.org/wiki/%E6%B5%AE%E7%82%B9%E8%BF%90%E7%AE%97%E5%99%A8 "浮点运算器")所采用。这个标准定义了表示浮点数的格式（包括负零[-0](https://zh.wikipedia.org/wiki/-0 "-0")）与反常值（denormal number），一些特殊数值（（[无穷](https://zh.wikipedia.org/wiki/%E7%84%A1%E7%AA%AE "无穷")（Inf）与[非数值](https://zh.wikipedia.org/wiki/NaN)（NaN）），以及这些数值的“浮点数运算符”；它也指明了四种[数值舍入规则](https://zh.wikipedia.org/wiki/%E6%95%B8%E5%80%BC%E4%BF%AE%E7%B4%84%E8%A6%8F%E5%89%87 "数值舍入规则")和五种例外状况（包括例外发生的时机与处理方式）。

#### （IEEE 754）舍入规则

* **向最接近的偶数舍入（Round to Nearest, Ties to Even）** ：当一个数需要舍入时，如果小数部分恰好为 0.5，那么结果将舍入到最接近的偶数。例如，1.5 舍入为 2，2.5 舍入为 2。
* **向零舍入（Round towards Zero）** ：当一个数需要舍入时，结果将朝着零的方向进行舍入。无论数的正负，都会直接截断小数部分。例如，1.5 舍入为 1，-1.5 舍入为 -1。
* **向上舍入（Round towards Positive Infinity）** ：当一个数需要舍入时，结果将朝着正无穷大的方向进行舍入。无论数的正负，都将向上舍入到下一个更大的数。例如，1.5 舍入为 2，-1.5 舍入为 -1。
* **向下舍入（Round towards Negative Infinity）** ：当一个数需要舍入时，结果将朝着负无穷大的方向进行舍入。无论数的正负，都将向下舍入到下一个更小的数。例如，1.5 舍入为 1，-1.5 舍入为 -2。

### 原始值
> 即一些代表原始数据类型的值，也叫基本数据类型，直接将值存在栈中

### Unicode
Unicode，全称为Unicode标准（The Unicode Standard），其官方机构Unicode联盟所用的中文名称为统一码[1]，又译作万国码、统一字元码、统一字符编码[2]，是信息技术领域的业界标准，其整理、编码了世界上大部分的文字系统，使得电脑能以通用划一的字符集来处理和显示文字，不但减轻在不同编码系统间切换和转换的困扰，更提供了一种跨平台的乱码问题解决方案。Unicode由非营利机构Unicode联盟（Unicode Consortium）负责维护，该机构致力让Unicode标准取代既有的字符编码方案，因为既有方案编码空间有限，亦不适用于多语环境。