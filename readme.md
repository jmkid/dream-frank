这是一个学习git用的仓库

git创建文件夹：mkdir `<your file>`

进入文件夹：cd `<your file>`

显示目录:`pwd`

初始化仓库：`git init`

创建文档：`vi <your file>`

退出编辑：`esc` `:wq`

添加和提交文件：

`git add <your file>`

`git commit -m "bz"`

bz可以自己随便写，就是防止你自己忘掉这是哪个版本写的一个备注

删除工作区内容:`git checkout -- file`

删除暂存区内容：`git reset HEAD <file> && git checkout -- file`

查看历史修改记录：`git log`

加参数显示更清晰：`git log --pretty=oneline`

版本回退到上一个版本：`git reset --hard HEAD^`

查看文档内容：`cat readme.txt`

回到未来或过去某个版本：`git reset --hard <id号>`

查找过去的每一次命令：`git reflog`

查看当前状态：`git status`

把本地master文件上传到远程库：`git push -u origin master`

注：第一次上传需要-u参数，之后就可以省略了

创建克隆库：在github上创建克隆库勾选`Initialize this repository with a README`，这样GitHub会自动为我们创建一个README.md文件。创建完毕后，可以看到README.md文件然后使用命令git clone克隆一个本地库

`$ git clone git@github.com:jmkid/gitskills.git`

注：github.com:后面写的是自己的账户名