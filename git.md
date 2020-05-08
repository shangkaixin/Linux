### Git工作区域
1. 仓库(Git Repository)
最终确定的文件保存到仓库，成为一个新的版本，并且对他人可见

2. 暂存区
暂存已经修改的文件最后统一提交到git仓库中

3. 工作区(Working Directory)
添加、编辑、修改文件等动作

### Git操作
+ 查看当前状态
```shell
git status
```

+ 将工作区的文件提交到暂存区
```shell
git add hello.c
```

+ 将暂存区的文件提交到仓库
```shell
git commit -m "description"
```

### Git配置
#### 1. Git基本信息设置
```shell
git config --global user.name "name" # 设置用户名
git config --global user.email "emai"#设置用户邮箱
```

#### 2. 初始化Git仓库
```shell
mkdir test #创建一个文件夹
git init #初始化仓库
```

#### 3. 向仓库添加文件
```shell
# 创建文件
git add hello.cpp #将文件放到暂存区
git commit -m 'new hello.cpp file' #将文件提交到仓库
```

#### 4. 删除文件
```shell
rm hello.cpp #删除文件
git rm hello.cpp #从git删除文件
git commit -m "description" #提交操作
```

### Git远程仓库管理
```shell
git push #将仓库同步推送到远程仓库
```

#### 1. git克隆
```shell
git clone 仓库地址 #克隆远程仓库地址到本地
```
其中，仓库地址是在github中clone按钮生成









