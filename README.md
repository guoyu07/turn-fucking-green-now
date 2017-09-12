## github首页全绿攻略 turn-fucking-green-now

#### 步骤
- [x] 进入项目目录 新建test.txt
- [x] 写批处理命令 将下面代码写入test.bat
- [x] 进入命令行运行 test.bat 文件
```javascript
@echo off
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
- [x] 第三行的set /a var+=1表示变量每次自增1 你可以把1改成3 这样就不是全绿 
- [x] 提交次数越多绿色越深 如果想每天提交两次 那就 把第4 5 6行复制粘贴在第6行之后 以此类推 

#### 联系我
- [x]  forgeekscn@gmail.com 
- [x]  QQ783808649 







