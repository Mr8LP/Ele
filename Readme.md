### 关于git的必要说明

初始化git本地仓库：git init

选中目录下所有文件：git add .

把缓存里的文件提交到本地git仓库：git commit -m "仓库说明"

本地git仓库与云端github仓库建立通道：git remote add origin + github库地址

把本地git库中的文件上传到github：git push -u origin + 分支



### 有可能出现的问题

1. Author identity unknown：

   ```
   git config --global user.email "you@example.com"
   git config --global user.name "Your Name"
   ```

   

2. error: src refspec main does not match any

   由于仓库名称不一样，导致远程和本地的仓库不能关联上

   把本地的 master 仓库名称修改为远端的 main

   ```
   git branch -m master main
   ```

3. ! [rejected]main -＞ main (fetch first) error: failed to push some refs to ‘https://github.com/x

   ```
   git push -u origin main --force
   ```


### 有关Markdown语法

```
&emsp;&emsp;两个全角的空格（用的比较多）
```

