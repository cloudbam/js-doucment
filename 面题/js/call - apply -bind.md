#### call  apply bind说说它们是干什么的？









#### call  apply bind说说它们的区别？

- call、apply的区别

> 他们俩之间的差别在于参数的区别，call和aplly的第一个参数都是要改变上下文的对象，而call从第二个参数开始以参数列表的形式展现，apply则是把除了改变上下文对象的参数放在一个数组里面作为它的第二个参数。



##### bind方法传递给调用函数的参数可以逐个列出，也可以写在数组中。bind方法与call、apply最大的不同就是前者返回一个绑定上下文的函数，而后两者是直接执行了函数。因此，以上代码也可以这样写：



#### 手写一个它们？

