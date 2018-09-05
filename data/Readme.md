# BZOJ Java Server/data
 
在这里，所有HTML文件均带有HTTP文件头。  

## 如何添加题目？

1. 在BZOJ Java Server/data/problems.html中<tbody>与</tbody>之间添加：<tr><td>`PID`</td><td><a href="/problem/`PID`.html">`题目名称`</a></td></tr>
2. 进入BZOJ Java Server/data/problem文件夹，添加`PID`.html文件。
3. 进入BZOJ Java Server/oj/data文件夹，创建`PID`文件夹。
4. 进入BZOJ Java Server/oj/data/`PID`文件夹，粘贴测试数据后创建`PID`.txt文件，  
里面输入类似这样的东西：
```plain
data1
data2
...
data10
```

5. 添加题目完成！