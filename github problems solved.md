- [FAQ](#faq)  

### FAQ
Q1: `git pull` `error: Your local changes to the following files would be overwritten by merge:`  

A1:  
```
git stash
git pull origin master
git stash pop
```

Q2: `readme.md` 图片居中  

A2:  
```
方法一：居中
<div align=center> 
  ![图片描述][图片链接] 
</div>
方法二：改变图片大小、居中
<div align=center> 
<img src="./xxx.png" width = "300" height = "200" alt="图片名称" />
</div>
```
Q3: `git checkout -b dev` 本地新建分支第一次`push`提示:
  
  fatal: The current branch develop has no upstream branch.
  To push the current branch and set the remote as upstream, use
  git push --set-upstream origin dev

A3: 按提示输入即可，以后`push`仅需要`git push origin`  
或者`git push -u origin dev`  



