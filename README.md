# git-study
## 如何删除远程文件保留本地文件
- 在项目更目录下建立.gitignore 文件,把要删除或者不需要提交到远程的文件名 写上去
- 在终端命令运行 
```bash
    git rm -r node_modules && git add . && git commit -m "message" && git push -u origin master
```
## develop
```bash
    建立分支 git checkout -b develop
    切换分支 git checkout master
    查看分支 git branch
    合并分支 git merge feach-01
    删除分支 git branch -D feach-01
```
