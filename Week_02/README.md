学习笔记
1.首先创建地图编辑器：
    （1）css需要注意，fontsize：0；否则每一行都会有很大的间距
    （2）两个for循环可以实现一维数组map【100*x + y】
    （3）mouseup按下后给mouseup一个状态，在mouseover给移动到的cell背景色，右键clear也需要一个状态来在mouseover清除背景色
    （4）这样就可以实现一道轨迹，并用localstorge记住轨迹的状态
2.广度优先搜索
    （1）数组有pop，unshift，push，shift方法yigedui
    （2）push和相对shift相对，unshift和pop相对都是一个队列；shift和unshift，pop和push就是一个栈
    （3）首先从queue取出一个位置，如果找到终点的位置，return为true，再从四个方向去查找
    （4）如果遇到墙，就什么不做；把找到的点给与标记，避免重复查找，在push道队列