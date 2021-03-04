# 清华大学部分课程推荐

## 前言

我是李博文，清华大学生命学院大三本科生，我将通过这个网页向大家推荐几门清华大学的课程。

## 课程目录
- 数据结构
- C++程序设计基础

### 数据结构

数据结构课程是清华大学计算机系的必修课程，同时该课程也开设全校性选修班级。

在这里，我仅向大家推荐邓俊辉老师开设的全校性选修班级，课程号为：**00240074**。该班级每年**秋季学期**开课，上课时间通常为**2-5（全周），4-5（全周）**。

通过这门邓老师的课程，你将能够学习到计算机表示、处理、组织数据的方法，同时，你还能了解到一系列数据结构。这些技能对于编写大型程序特别重要。

想要了解更多课程细节，请点击[了解更多](http://dsa.cs.tsinghua.edu.cn/~deng/ds/tsinghua/ "邓俊辉老师数据结构课程官网")进入官网网站。

### C++程序设计基础

清华大学的*C++程序设计基础*课程属于国家精品课、国家精品资源共享课。 

本课程为高级语言程序设计的入门课程，完全针对零起点的学生，可作为其他信息类相关课程的基础课。目标是使学生通过本课程的学习，掌握面向对象程序设计的基本概念和方法、C++的基本语法和编程方法；学会使用集成开发环境；掌握程序调试方法；初步了解常用数据结构和非数值算法；初步了解C++标准模板库的使用方法。

C++代码示例：

```C++
{
    class fruit()
    {
    private: 
        double fruit_weight;
        double fruit_cost;
    public:
        fruit(double fw, double fc)
        {
            fruit_weight = fw;
            fruit_cost = fc;
        }
        double show_fruit_weight()
        {
            return fruit_weight;
        }
        double show_fruit_cost()
        {
            return fruit_cost;
        }
        void change_data(double fw, double fc)
        {
            fruit_weight = fw;
            fruit_cost = fc;
        }      
    }
}
