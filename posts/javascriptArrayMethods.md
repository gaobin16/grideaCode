---
title: '数组的方法'
date: 2020-03-28 14:40:56
tags: [javascript]
published: true
hideInList: false
feature: 
isTop: false
---
1、join()

> join(separator): 将数组的元素组起一个字符串，以separator为分隔符，省略的话则用默认用逗号为分隔符，该方法只接收一个参数：即分隔符。
```
var arr = [1,2,3];
console.log(arr.join()); // 1,2,3
console.log(arr.join("-")); // 1-2-3
console.log(arr); // [1, 2, 3]（原数组不变）
```