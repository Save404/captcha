第一类验证码为四则运算验证码，包含一个四则运算，验证方法为要求用户输出运算结果。

关于数据集，详细说明如下：

一、训练集train中共有10000个样本，序号0000~9999，其中包含一个四则运算，包含三个数字和两个运算符，运算符不包括除号，运算本身不包含括号。

二、mappings.txt中为该训练集的输出结果，每一行对应一个样例，其中：
    1. 第一列为样例的序号；
    2. 第二列为样例图片中四则运算内容及计算结果，结果可为负数；

比赛结果评判：比赛时会给出格式与训练集相同的测试集，要求参赛者使用开发的程序识别测试集并输出mappings.txt，评分按最终识别的准确率评判。