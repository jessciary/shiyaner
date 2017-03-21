# 实验二 Git的使用

## 一、实验目的
1. 掌握git使用
2. 掌握使用Github作为远程仓库

## 二、实验任务
1. 练习本地git操作
2. 用SSH同步本地与Github仓库

## 三、实验步骤与结果

### 实验步骤如下：
### 同步本地与Github仓库：
1. 下载Github客户端，并安装Git客户端
2. 打开Git客户端并登陆
3. 在Github中创建一个新的项目testGit
4. 点击Open in Desktop将testGit克隆到Git客户端
5. 在Github的testGit文件夹中新建一个测试文件test
6. 在test文件中写入一句测试语句并保存
7. 打开Git客户端可看到一个未提交的修改，填写评论并提交修改
8. 可看到提示有一个未同步的修改，点击右上角的Sync同步按钮将其提交到Github上
9. 在Github上可看到新增的commits，表示已实现同步，重复修改同步即可

### 分支开发与合并：
1. 打开Git客户端，点击左上角的create new branch，填写分支名称
2. 在test文件重新写入一句测试语句并保存
3. 提交修改并同步到Github
4. 在Github上打开，点击Compare & pull request并提交并将该分支合并到master中
5. 在master中可看到已经更新了这次修改，表示已实现分支合并

### 实验结果如下：
1. 本地操作log截图

![http://i2.buimg.com/567571/2abcfe81d0069370.png]

2. Github上commits截图

![http://i1.piimg.com/567571/690b213a8323c6b1.png]

![http://i4.buimg.com/567571/3ae00a5160a0937e.png]

![http://i2.buimg.com/567571/8c8577e6b9eb198c.png]

## 四、实验小结

### 同步本地与Github仓库：
可在Git客户端查看每次增加或修改操作。

### 分支开发与合并：
有新的需求或紧急bug需要修复时，在默认分支不便实现，可开发一个新的分支实现，即可实现不改变现有操作开发新需求或修复bug。而后可将新分支合并到默认分支中。
