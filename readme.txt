1我在github上直接建立了一个新的仓库changjiaqi
2在"D:\好玩的matlab\20240711测试"右键打开Open Git Bash here
3git clone git@github.com:jqchang1/changjiaqi.git
4提示复制了一个空的仓库 生成了changjiaqi文件夹
5然后我打开changjiaqi文件夹，新建了demo文件
6!git status
7!git add .  ////  这个d.是提交了所有文件到缓存区  git add readme.txt是只提交这个文件
8!git status
9!git commit -m"提交demo文件" 提交到本地仓库
10!git status
11!git push 推送到远程了
12!git log  查看提交记录
13!git log --oneline 查看简要版本的提交记录

===================配置了一次SSH以后  我这次没有配置新的SSH了
查看了git log以后 发现用的就是以前配置的SSH
所以我现在认为只需要配置一次即可 后续有bug的话 再修改吧

