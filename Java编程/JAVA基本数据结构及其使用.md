# JAVA编程

```java
/*数组
	1、数组排序
	2、数组翻转
*/
```

```java
/*链表
	1、链表翻转
*/
```

```java
/*map
	1、
*/
```

```java
/*stack
	1、先进后出
*/
```

```java
/*queue
	1、先进先出
*/
```

```java
/*priorityqueue
	1、优先级高，先出
*/
```

```java
/*Heap
	1、最大堆 or 最小堆
*/
```



```java
/*算法：排序
	1、冒泡、快速排序、选择排序、堆排序
*/
public static int[] bubbleSort(int[] array){
    if (array.length==1){
        return array；//为什么没有return
    }
    for (int i=array.length-1;i>0;i--){
        for (int j=0;j<i;j++){
            if (array[j]>array[j+1]){
                int temp=array[j+1]；
                array[j+1]=array[j]；
                array[j]=temp；
            }
        }
    }
    return array；//为什么没有return
}
```

