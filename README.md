## git 命令
### 1. 本地初始化
```
git init
```
### 2. 克隆仓库
```
git clone url:xxx
```
### 3. 显示本地修改的文件
```
git status
```
### 4. 添加需要提交的文件
```
git add . (添加全部文件)

git add xxx (添加单个文件)
```
### 5. 添加备注
```
git commit -m'xxx'
```
### 6. 推送到远端服务器
```
git push origin url:xxx
-f 强制推送
```
### 7. 拉取代码
```
git pull origin url:xxx
```
### 8. 查看提交历史
```
git log
```
### 9. 合并commit\
```
git rebase -i HEAD~x
git rebase --abort 停止合并commit
```
### 10. 查看当前分支
```
git branch
git branch xxx 基于当前分支，创建新分支
git branch -D xxx 删除分支
```




