# pyfinal
你好，这里存储的是2022 Fall 编程基础期末大作业的相关文件。

## 课程论文背景
本文基于多因子$\alpha$模型，以研究超额收益$\alpha$为目标，选取成交金额等交易数据，首先计算$\alpha$收益，将基本面的市盈率、每股收益、市销率等作为自变量，进行主成分分析，并通过各种机器学习方法，探究$\alpha$收益与各成分之间的干系，从而预测$\alpha$收益是否大于零，形成投资意见。本文数据选取范围为2019年6月1日至2021年5月31日，取用所有A股上市股票，最终结果发现一系列变量可以有效解释$\alpha$收益，并且较准确地预测$\alpha$收益且进行分类。
## 主要文件说明
1. `data.zip`: 为本课程论文利用的原始数据集。因为其大部分数据来自WIND等付费金融端，对压缩包进行了加密。**解压密码为我的学号**。
2. `python_final.ipynb`: 是本课程论文利用的代码合集，其包括代码中为展示的详细运行结果、内容。
3. 其他。为代码运行过程中保存的用于报告的图片、表格等内容，可以忽略。

## 使用说明
1. 利用我的**学号**将该压缩包解压，会得到一个`.rar`文件，再次解压，会得到一个`数据`文件夹。
2. 将第一步得到的“数据”文件夹和**ipynb文件放在同一级目录**，打开ipynb文件即可复现运行。

## 其他
1. 文章主要利用了 numpy, pandas, matplotlib, seaborn, sklearn 和 statsmodels 包；
2. 压缩文件是在M1 Macbook MacOS Ventura下生成，若存在解压失败等问题请联系我： yecong@ruc.edu.cn 或是通过课程群加我好友~（名字拼音）。
