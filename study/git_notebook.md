touch            创建文件
美丽姐补充：
了解gitflow
git push                    推到GitHub上
git pull                    拉回本地
git reset --hard HEAD
git reset --hard HEAD^
git reset --soft HEAD^
git fetch                   刷新分支
git branch                  只显示本地的分支
git branch -a               显示本地以及github上的分支
git merge （） into （）      合并分支命令  
！！！！！测试分支、预发布分支绝对不可以往个人分支熵合！！！！！！
正式分支可以合并到个人分支，对个人账户代码的功能进行补充、更新
！！！！合并冲突：找到人对接之后再决定用谁的版本，不可🙅擅自更改！！！！


git add                      将文件添加到暂缓区      
git add .                    该文件夹下的所有文件全部上传
git status -s                查看项目的当前状态： (A代表已经上传，AM代表修改过，需要重新git add）
git commit -m                将暂缓区的内容添加到本地仓库中： 
git commit -am
git branch (branchname)        创建分支命令 
git checkout (branchname)      切换分支命令   
git checkout -b (branchname)   新建分支并立即切换到该分支下  
git branch -d (branchname)     删除分支 

git log  （参数）               查看历史提交记录 
参数：
--oneline                      简洁版本
--graph                        拓扑图选项  
--reverse                      逆向显示所有日志 
-- author                      只查找指定用户的提交日志 
--since、--before、--until、 --after     指定日期  
git blame <file>                        查看指定文件的修改记录

git tag -a  (标签名)            打标签： 
git tag                        查看所有标签 

git tag -a <tagname> -m "runoob.com标签"      指定标签信息命令
git tag -s <tagname> -m "runoob.com标签"      PGP签名标签命令

添加一个新的远程仓库: git remote add [shortname] [url]
要查看当前配置有哪些远程仓库，可以用命令： git remote

提取远程仓库：
从远程仓库下载新分支与数据： git fetch  （仓库名）
从远端仓库提取数据并尝试合并到当前分支： git merge
删除远程仓库 : git remote rm [别名]


echo 'runoob.com' > test.txt
把runoob.com写入test.txt文件中
