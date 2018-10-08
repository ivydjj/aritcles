# 1、repository

### ssh克隆
git clone git@github.com:ivydjj/aritcles.git

### https克隆
git clone https://github.com/ivydjj/aritcles.git

### create a new repository on the command line
### and push an existing repository from the command line
git init
git remote add origin https://github.com/ivydjj/ivy-elastic.git
git commit -m "first commit"
git push -u origin master

# 2、标签
### 查看本地tag
git tag

### 获取远程tag
git fetch --tags

### 推送本地tag到远程
git push --tags

### 删除本地tag
git tag -d v20180809

### 删除远程tag
git push origin :v20180809

git push origin --delete tag v1.1.0.Final

### 给当前文件打特定版本标签
git tag -a  beta0.1 -m "some 注释" 

### 回退到某个tag 
git tag beta0.1



