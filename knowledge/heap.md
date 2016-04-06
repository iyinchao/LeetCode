# Heap 堆

## 概念
* 可看作近似的完全二叉树（仅有深的一层不满）  
* 使用数组模拟二叉树，以1为base的情形：  
<img src="./img/heap/1.png" height="200"/>
	* parent = floor( son / 2 ) 
	* left = parent * 2
	* right = parent * 2 + 1
	* 以0为base，son均减去1即可
* 最大堆：父大于子，根最大。

## 堆排序
* 时间复杂度nlogn 
* 
 