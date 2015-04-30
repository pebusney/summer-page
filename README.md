# Teambition · 暑期实习生计划  
  
  [https://summer.teambition.com](https://summer.teambition.com)

一周左右完成整个项目的构建+编码，花了4天左右调整动画效果和排版。  

目前存在以下问题：  

1. 路由很烂  
2. 没有做返回功能  
3. 内聚性太强，功能的调用栈太长不易管理  
4. 事件机制很弱，有几个情况会重复触发事件  
5. 莫名其妙的兼容性问题  
  
能想到的改进：  
1. 动画依靠路由控制，路由依靠hash触发  
2. view,paint,animate 三个模块去耦合，依靠一个route管理  
3. 数据计算由webworker完成  
  
做之前没有考虑好这个项目的整体架构，完成度较高时重构代价又太大，只能先挖个坑，等以后有时间了再填。

##How to  
  
  npm i  
  bower i  
  gulp  
  gulp serve
