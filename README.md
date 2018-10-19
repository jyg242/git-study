# git-study
## 如何删除远程文件保留本地文件
- 在项目更目录下建立.gitignore 文件,把要删除或者不需要提交到远程的文件名 写上去
- 在终端命令运行 git rm -r node_modules && git add . && git commit -m "message" && git push -u origin master
