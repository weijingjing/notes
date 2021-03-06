### Heap
 
1. 使用堆实现的优先队列:对于总共N个请求,使用普通数组或者顺序数组,最差情况O(n^2),使用堆O(nlgn)
2. 优先队列的实现. 

	| | 入队时间复杂度 | 出队时间复杂度 | 
	| :-----: |:-------:| :-----:| 
	| 普通数组 | O(1) | O(n)  | 
	| 顺序数组 | O(n)) | O(1) |
	| 堆    | O(lgN) | O(lgN) |


### Heap(Binary Heap)的实现
1. 二叉树:每个节点最多有两个子树的树结构.
2. 完全二叉树：叶节点只能出现在最下层和次下层,并且最下面一层的结点都集中在该层最左边的若干位置的二叉树.
3. 二叉堆有两种:最大堆和最小堆.最大堆:父结点的键值总是大于或等于任何一个子节点的键值;最小堆:父结点的键值总是小于或等于任何一个子节点的键值.
4. 二叉堆是完全二叉树.


### 应用
1. 在N个元素中选出前M个元素, 如果先用MergeSort或者QuickSort,时间复杂度是NlogN,如果使用堆实现的优先队列的话,时间复杂度是NlogM.




![alt](http://oylc9q7dv.bkt.clouddn.com/20171103/2sTTWvCL7Z9ZU6Jfgy75rQBq.png)

![alt](http://oylc9q7dv.bkt.clouddn.com/20171103/ny5YnA7ouxhv3KD6s2Fyez7Z.png)