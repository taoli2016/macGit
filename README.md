# macGit
mac通过git上传代码至github

### 1.安装git 
	```
	brew install git	
	```
### 2.设置username、useremail
	```
	git config --global user.name "xx"
	git config --global user.email "xx@163.com"
	```
### 3.终端创建ssh key
	```
	ssh-keygen -t rsa -C "xx@163.com"
	```
### 4.查看
	```
	cat .ssh/id_rsa.pub
	```
### 5.github中setting ssh key
### 6.验证链接
	```
	ssh -T git@github.com 
	```
### 7.新建repository或者project
### 8.下载项目
	```
	git clone https://github.com/vanliant/macGit.git
	```
### 9.提交代码
	```
        //切换到项目根目录下
	//文件添加到仓库（.代表提交所有文件）
	git add .
	//把文件提交到仓库
	git commit -m "First Commit"
	//上传到github
	git push
	```
