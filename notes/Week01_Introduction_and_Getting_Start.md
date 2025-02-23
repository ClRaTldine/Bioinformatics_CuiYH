# Week01: Introduction and Getting Start

崔钰涵 2024.02.21

### 课程目标：

> 我们将教授生物信息学方面的专业技能，这些技能不是单纯地运行软件的能力，而是让你们拥有**探索各种真实数据的自由**。

### 教学内容：

<img src="https://raw.githubusercontent.com/ClRaTldine/Pictures/main/屏幕截图 2025-02-23 110429.png" alt="屏幕截图 2025-02-23 110429" style="zoom:50%;" />

### 评分标准：

1. 课堂互动（20%）
2. 当堂与课后作业（80%）
3. Presentation（本组于第16周）
4. 加分题

## Part I. Introduction

**Question/Hypothesis-driven Science**

Question--Information--Analysis--Modeling

**Big Data-driven Science (The Fourth Paradigm)**

Information--Analysis--Modeling--Question

The key technique that leads to bioinformation explosion: **NGS (Next Generation Sequencing)**

**Key Difference between Model and Algorithm**(Partially referred to Deepseek)

|      | 模型（Model）                                                | 算法（Algorithm）                                            |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 定义 | 对现实问题或数据的 **抽象表示** ，通常是一个数学结构（如方程、概率分布、图结构等） | 一组明确的、可执行的 **步骤** ，用于解决问题或完成任务（如训练模型、优化参数、搜索数据等） |
| 功能 | 通过参数（或结构）捕捉 **数据中的规律** ，用于 **预测、分类或生成结果**  | 解决某一类问题、训练模型等                                   |
| 实例 | Linear/Logistic Regression Model; <br />Neural Network Model | Number Sorting Algorithm; <br />Dynamic Programming Algorithm |

**模型与算法的联系：** 模型依赖于算法（模型的构建和优化需要算法）,算法服务于模型（算法的设计服务于训练和优化模型）

e.g. 使用最小二乘法 **（算法）** 生成线性回归 **（模型）**

## Part II. Getting Start

### Tools for Learning Bioinformatics

1. Github--代码托管平台，构建仓库以存储个人笔记与代码
2. Markdown--简洁的通用标记语言，格式为``.md``，用于编写网页，学习中可以用于编写笔记
3. 清华云盘--校内访问方便，可用于备份工作文件
4. Docker--轻量化的虚拟机，用于运行Linux环境
5. Typora--简洁的Markdown语言编辑器
6. VS Code--常用的编辑器，现支持AI插件
7. Vim--Linux环境常用的编辑器

### Backup My Work

建议经常备份自己的工作文件，以防丢失或损坏

可使用**清华云盘**和**Github**

<ins>Tips: 不要每天都备份工作！建议每2-3天备份一次</ins>

## Part III. 我的生信学习计划

### 自己的一些想法

1. 听课时注意记笔记！（如果熟练了就能在课上直接用Markdown语言直接记笔记了）
2. 课下用<ins>每周4-5h</ins>的时间完成**课后作业**以及**Tutorial**的学习和练习
3. 由于本人几乎没有编程基础，故打算在课下抽出<ins>每周2-3h</ins>的时间自主学习练习**Linux bash**和**R**两门语言，计划将 **《鸟哥Linux私房菜》** 和 **Quick R**作为参考书
4. 已经与身边同学建立了学习交流群，那就有问题及时问
5. 记得<ins>每3天</ins>把自己写的代码备份至Github的ClRaTldine/Bioinformatics_CuiYH

### 阶段性自学计划与学习建议（参考Deepseek）

|   时间    |     阶段     |                             任务                             |
| :-------: | :----------: | :----------------------------------------------------------: |
|  Week1-4  | 基础知识补充 | 补充Linux、R基础知识，提升编程能力<br />复习生物学基础知识（如基因组学、测序技术、etc.） |
|  Week5-8  | 生信工具基础 | 学习从数据库下载序列，并使用R处理序列<br />复习统计学知识（假设检验、方差分析、etc.）并尝试用R实现 |
| Week9-12  | 小型项目实践 | 学习经典分析流程（序列比对、建树、RNA-seq分析、etc.）<br />尝试实现小型项目（突变位点分析、基因表达热图绘制等） |
| Week13-16 |  拓展与整合  | 深入学习感兴趣的方向（基因组学、蛋白组学、宏基因组学、etc.）<br />尝试独立完成完整项目（从原始序列数据到差异基因筛选）并撰写报告 |

**学习建议：**

1. 多练习、多实践，可以参考HackerRank/LeetCode生物信息学题目，或者尝试完成一些小项目
2. 善用工具和社区（社区如Stack Overflow、Biostars、GitHub Issues）
3. 不要纠结“完美代码”，先实现功能再优化
4. 尝试复现经典论文的分析流程
5. 用思维导图整理技术关键词
