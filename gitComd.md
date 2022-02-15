

## 基本命令

1. ### brew install git :mac install git

2. ### git --version : check version

3. ### git init :初始化本地仓库

4. ### git clear: clear gitResp

5. ### git config --global user.name "kker" :set userName

6. ### git config --global user.email "kker062899@gmail.com" : set emailAddress

7. ### git add fileName : put file to cacheZoon

8. ### git commit -m "describe for commit resoion" : put cacheZoon files to localRepository

9. ### git log --oneline :一行展示

10. ### git reflow ：带指针日志

11. ### git reset --hard fileId:指针跳转到指定版本 可以前后或后退 

    ### 	--hard参数会同步更新 工作区，暂存区，本地库（基本只用hard)

    ### 	--mixed参数 不会同步工作区

    ### 	--soft参数 只同步本地库

12. ###  git删除文件的过程 ，rm删除本地文件，add 被删除的文件，commit，完成删除

13. ### git diff filename ： 查看单独文件工作区与缓存区版本差异，不加filename参数 则表   示比对所有暂存区和工作区的差异

14. ### git diff HEAD(版本id)  fileName(cache)  :查看本地仓库与缓存区的版本差异

    

    ------

    

## 分支branch

### 1.git branch -v :check branch

### 2.git branch branch01 :create branch

### 3.git checkout branch01 :switched to branch01 

### 4.git merge branche01：分支的合并，切换到主分支，合并到主分支产生新版本



### <font color=blue><u>注意 当分支之间产生冲突时 需要人为解决冲突问题，之后add到 缓存区,然后commit。 注意 此时commit不能带文件名 否则报错</u></font>





