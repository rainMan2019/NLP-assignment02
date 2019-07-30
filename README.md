# NLP-assignment02
- 这是NLP的第二次作业,包括一个爬虫文件,一个画地铁经纬度和搜索策略以及波士顿房价预测的文件,其余文件是保存一些地铁数据的文件
- 
# 回答问题
1. Why do we need machine learning methods instead of creating a complicated formula?

Ans: 靠人工来定义复杂函数非常难，而且不能面对随时改变的数据，不能应付实际需求。而机器学习是从历史数据出发，自动生成一个函数表达式，并且通过损失函数来调整参数，从而把误差控制到很小的范围内。

2. Wha't's the disadvantages of the 1st Random Choosen methods in our course?

Ans: 尝试次数的次数比较多，误差会比较大，随着次数的增加，得到的最优解也不一定会变优

3. Is the 2nd method supervised direction better than 1st one? What's the disadvantages of the 2nd supversied directinmethod?

Ans:第二种方法比第一种方法更优，第二种方法的缺点是每次方向的选择还是随机的，不一定朝着损失函数减少的方向运动

4. Why do we use Derivative / Gredient to fit a target function?

Ans: 让参数向损失减少的方向移动，最终最小化损失函数值

5. In the words 'Gredient Descent', what's the Gredient and what's the Descent?

Ans: 梯度即导数，下降是指让损失函数的值变小，即最小化损失函数的值

6. What's the advantages of the 3rd gradient descent method compared to the previous methods?

Ans: 最小化损失时更快，花时间更少
有方向性，预测函数的参数一直朝着损失函数值减少的方向运动，并且可以控制学习率，因此可以加快求解最小损失函数所对应的最优参数

7. Using the simple words to describe: What's the machine leanring. 

Ans: 从历史数据出发，自动生成函数表达式，并且使得损失函数值最小来调整函数参数

