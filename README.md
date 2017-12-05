# Hello-world
- [FAQ](#faq)  

Q1: `git pull` `error: Your local changes to the following files would be overwritten by merge:`  

A1:  
```
git stash
git pull origin master
git stash pop
```

Q2: `readme.md` 图片居中  

A1:  
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


