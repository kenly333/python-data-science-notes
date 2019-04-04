## Python数据科学学习笔记
《Python数据科学手册》

### 常见数学函数

[例子](https://github.com/kenly333/python-starter/tree/master/math-function)

### NumPy数组
将所有数据简单地看作数字数组非常有助于我们理解和处理数据。例如，可以将图像（尤其是数字图像）简单地看作二维数字数组，这些数字数组代表各区域的像素值；声音片段可以看作时间和强度的一维数组；文本也可以通过各种方式转换成数值表示，一种可能的转换是用二进制数表示特定单词或单词对出现的频率。不管数据是何种形式，第一步都是将这些数据转换成数值数组形式的可分析数据。正因如此，有效地存储和操作数值数组是数据科学中绝对的基础过程。

[例子](https://github.com/kenly333/python-starter/tree/master/numpy)

### Pandas数据处理
Pandas 是在 NumPy 基础上建立的新程序库，提供了一种高效的 DataFrame 数据结构。 DataFrame 本质上是一种带行标签和列标签、支持相同类型数据和缺失值的多维数组。 Pandas 不仅为带各种标签的数据提供了便利的存储界面，还实现了许多强大的操作，这些操作对数据库框架和电子表格程序的用户来说非常熟悉。建立在 NumPy 数组结构上的 Pandas，尤其是它的 Series 和 DataFrame 对象，为数据科学家们处理那些消耗大量时间的“数据清理”（data munging）任务提供了捷径。

[例子](https://github.com/kenly333/python-starter/tree/master/pandas)

### Matplotlib数据可视化
Matplotlib 是建立在 NumPy 数组基础上的多平台数据可视化程序库，最初被设计用于完善 SciPy 的生态环境。Matplotlib 最重要的特性之一就是具有良好的操作系统兼容性和图形显示底层接口兼容性（graphics backend）。 Matplotlib 支持几十种图形显示接口与输出格式，这使得用户无论在哪种操作系统上都可以输出自己想要的图形格式。

[例子](https://github.com/kenly333/python-starter/tree/master/matplot)

### Scikit-Learn机器学习
目前， Python 有不少可以实现各种机器学习算法的程序库。 Scikit-Learn 是最流行的程序包之一，它为各种常用机器学习算法提供了高效版本。 Scikit-Learn不仅因其干净、统一、管道命令式的 API 而独具特色，而且它的在线文档又实用、又完整。

[例子](https://github.com/kenly333/python-starter/tree/master/sklearn)
