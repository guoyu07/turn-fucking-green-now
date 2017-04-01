## github首页全绿攻略 turn-fucking-green-now

#### 步骤
- [x] 进入项目目录 新建test.txt
- [x] 写批处理命令 将下面代码写入test.bat
- [x] 进入命令行运行 test.bat 文件
```javascript
@echo off
@echo January-31 February-28 March-31 April-30 May-31 June-30 July-31 August -31 September-30 October-31 November-30 December-31
:start
set /a var+=1
echo a >> test.txtgit 
git add .
git commit --date=" April %var% 9:05:20 2016 +0800" -am "turns fucking green"
if %var% leq 30 GOTO start
git push origin master
@echo Mission finished !
```
#### 用法
- [x] %var% 代表日期变量 倒数第三行的30代表日期%var%会从1遍历到31 
- [x] 如果想让16年2月全绿 你可以把上面倒数第四行April改成February 二月只有28天 那么倒数第三行30就改成27  
- [x] 第三行的set /a var+=1表示变量每次自增1 你可以把1改成3 这样就不是全绿 :-)


#### 广告来一波 代写本科java毕业设计和论文
- [x] 要项目源码的可以联系我 如有技术相关问题 还请不吝赐教 qq783808649 
- [x] 本人计算机专业毕业，基础扎实，熟悉j2ee开发，效率惊人，近期空闲时间多，可代写本科java毕业设计和论文，包括各种web后台管理系统
- [x] 本人承诺一周内完成任务 满意后付佣金 
- [x] 关于佣金，根据难度而异，代码大概300-600，代码+论文大概600-1000 ，先支付定金20%，远程演示满意后再支付余下80%







