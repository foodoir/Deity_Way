# openCV SVM简单使用
***

&ensp;&ensp;&ensp;&ensp;这个机器学习自己也是现在才刚开始接触，要说清楚它的原理感觉是误导人的,所有我现在就不说原理了，等以后有更深的体会能说出一些道道的时候再补上哈。
&ensp;&ensp;&ensp;&ensp;在一年的代码学习中一直感觉最好的学习就是边用边学，你懂的，一开始看啥理论和源码那叫一个枯燥无味啊，就想打瞌睡。个人感觉打代码就是一个代码体验啊！在这个漫长的技术道路上成就感这个东西很重要，所以我们先简单的来弄一个成果。下面直径上详细的代码步骤，注意环境是win7，版本是2.4.4，我们以图片为例，其他自己类推，估计和这个差不多：

## 设置训练数据
&ensp;&ensp;&ensp;&ensp;在给机器的训练中需要两个数据：一个是原始的数据，一个是相应原始数据的判断标记（通常是 1 和 -1）。