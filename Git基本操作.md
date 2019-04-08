# Git基本操作

## Git的四种文件

- blob ： 文本文件、 二进制文件

- tree：目录

- commit：历史提交

- tag：指向固定历史提交

  ![1554697813230](C:\Users\卢华源\AppData\Roaming\Typora\typora-user-images\1554697813230.png)

## Git仓库连接

```git
git init (+ repName) 会创建一个.git目录
git init --bare (+repName) 不会创建一个.git目录

---
git clone [URL]/ [自定义名称]   获取一个远程裸仓库的地址(也可以是本地)

```



## Git的基本工作流程

![1554698686256](images/1554698686256.png)

```git
//初试化仓库
git init (+repName)

//进入仓库
cd repName (或者.git)

//跟踪并添加文件到暂存区
touch a (a、b都是文件名)
touch b
git add a b

//获取暂存区信息
git status 
"提示信息"

//提交
git commit -m "提交信息"

//修改a
vim a (修改a)
*****

//获取暂存区信息
git status
"提示信息"

//添加到暂存区a并提交
git add a
git commit -m "modify a"

//删除
git rm a
ls
git status


//只删除暂存区的a
git rm --cached a

//提交
git add a
git commit -m "xxxx"

//重命名
git mv a c
git status
git add a c
git status

// 添加全部
git add . 
git add -A

//剔除不需要添加的(以'*'开头则是不需要的)
vim .gitignore
*.[oa]
*~
*.pyc
!test.pyc//纳入此文件，以'!'开头文件则\!test.pyc
foo/
**/res
build/
Documentation/
src/
.DS_Store  

git status




```

