---
title: daylog
---
##
>  iscroll v5.2.0 无法左右移动(overflow:auto)
### 解决方法：阻止事件冒泡即可
### ```window.event? window.event.cancelBubble = true : e.stopPropagation();```
