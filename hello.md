	1. 在GitHub创建一个同名的空仓库：youkeda
	2. 用cd命令进入本地的youkeda这个文件夹
	3. 初始化为git仓库
	git init
	如果初始化错了，就在该文件夹内删除.git这个文件夹（这是一个隐藏文件）
	rm -rf .git
	4. 查看当前git仓库的绑定情况
	git remote -v
	刚刚初始化的仓库一般来说是没有绑定远程仓库的，而从线上clone下来的仓库是必然有远程绑定的
	5. 绑定远程仓库
	git remote add origin 仓库地址
	//origin可以替换
	6. 如果绑定错误，移除绑定
	git remote remove origin
	//origin可以替换
绑定完成后，我们就可以将本地的仓库提交到GitHub了