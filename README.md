# gitFlowStudy
学习版本控制，记录每个命令

第一步：
	创建dev 分支： git checkout dev;
	新建一个文件： touch devBranch;

提交分支内容到远程仓库：
	git add README.md
	git add devBranch
	git commit -m "message"
	git push orign dev
	在服务器可以查看到两个分支dev、master。

第二：
	从远程克隆dev分支
 	git clone  -b dev https://github.com/urielyan/gitFlowStudy.git
	创建release分支
	git  checkout -b feature
