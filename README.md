###Xcode常用快捷键
---
快捷键        | 含义 
------------ | ------------- 
Command+0                     |     显示/隐藏导航器面板（左侧）
Command+Option+0              | 显示/隐藏实用工具面板（右侧)                  
shift + command + Y           | 显示debug栏（下面）       
Command+Shift+F               | 搜索导航器(Find Navigator，搜索)                          
Control+6                     | 键入方法/变量名+Enter跳转                           
Command + Shift + O           | 快速打开                      
Control + Command + Up / Down | .h/.m文件之间快速跳转                        
Command + Shift + K           | 清除工程                         
Command + Shift + 0           | 快速查找文档和参考                          
Command + Shift + J           | 快速跳转到指定文件 
command  + L                  |跳转到指定行
shift + command +L  |跳转到光标所在的行


                     
<br>

###Vim常用快捷键
---

####移动

快捷键        | 含义 
------------ | ------------- 
h、j、k、l    | 左下上右 移动光标
e   end      |  移动光标到下一个单词的末尾
b   begin    |  移动光标到上一个单词的开头
$            |  光标移动到行尾
0            |  光标移动到行首
G            |  光标移动到最后一行的起始位置
gg           |  光标移动到第一行的起始位置
:n           |  移动到第n行
n\| (\|是enter键上方)   |  移动到第n列
####剪切, 复制 & 粘贴
快捷键        | 含义
------------ | ------------- 
y            |  复制选中内容到剪切板
p            |  粘贴
dd           |  剪切当前行
yy           |  复制当前行
y$           |  复制当前光标到行尾的内容
D            |    复制当前光标到行尾的内容  
####搜索
快捷键        | 含义
------------ | -------------  
/word        |  从上往下搜索
?word        |  从下往上搜索      
/\cstring    |  Search STRING or string, case insensitive
/jo[ha]n     |  Search john or joan       匹配 h 或者 a［ha］
/\< the      |  Search the, theatre or then  搜索 the 开头的单词
/the\>       |  Search the      
/fred\|joe   |  Search fred or joe
/\<\d\d\d\d\>|  Search exactly 4 digits     
/^\n\{3}     |  Find 3 empty lines   
####替换
快捷键        | 含义
------------ | -------------  
:%s/old/new/g   |  替换      

