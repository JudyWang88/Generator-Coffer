1设计一个接口，该接口可以产生一个对象的方法
2让生成器创建一个具体的对象
3设置一个计数器用来产生id
4甚至生成id的序号
5设置一个tostring的方法返回class名字和id
6生成很多种咖啡类型，继承父咖啡
7咖啡生成器实现（生成器负责生成咖啡）
8由此可知我们需要返回一个可迭代接口和一个next方法
9当next方法实现之后，实现iterator，当时目前来说没有迭代的方法
10在实现Iterator的方法里面我们需要实现hashnext和next还有remove方法
11写main方法测试，他们会一次的去执行iterator中的方法

1利用自己写的迭代器实现斐波那契数列（前两个数相加）

得出结论：先走全局数据成员，再走的是实现的接口的方法，然后再走的是构造方法

![image](https://github.com/JudyWang88/Generator-Coffer/blob/master/snipaste20181023_105856.png)
