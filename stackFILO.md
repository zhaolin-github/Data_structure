2.入栈出栈规则

先进后出，不一定要全部入栈之后再出栈，没入栈完也可以先出栈

3.任何出栈元素后面的元素必须满足两条规则

1.在原序列（也就是入栈序列）中顺序比**出栈元素小**的，**必须是逆序**

2.在原序列（也就是入栈序列）中顺序比出栈元素大的，顺序无所谓

3.出栈元素表示的是出栈后面的所有元素

比如入栈的是12345，有下面两种情况：

a. 1 5 4 3 2  这个先看第一个元素1,1后面的元素每一个都比这个**大**，所以无所谓什么顺序，再看第二个元素5，5后面的元素都比这个数小，所以都必须遵循逆序，而432遵循逆序，所以没问题，情况成立。

b. 4 3 5 1 2  这个先看第一个元素4,4后面比它**小**的是312，而这个12明显不按逆序，也就是倒序排列，所以是有问题的 。
