##Scan Line

####来自图像处理的算法
[可参考的资料](http://yacare.iteye.com/blog/2009769)

	^
	|
	|			[----------------------------]
	|
	|								[------------------]
	|
	|		[---------]
	|
	|[--------]
	|		[--------------------]
	|
	------------------------------------------------------------->

去计算区间的重叠
这样就可以根据x轴 去找是否在区间内,来得到经过某x点有多少个区间

加强用法
设置一个数据类,只去记录区间首尾
如[0,start] [3,end] 是第一个区间
这样就不需要去遍历每个x点,而只需要出现过的点
