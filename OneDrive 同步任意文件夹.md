

# OneDrive 同步任意文件夹

## 打开onedrive复制资源管理器中的地址

> 地址一：C:\Users\卢华源\OneDrive - stu.haut.edu.cn\其余文件夹备份

## 打开需要同步的文件夹

> 地址二：E:\SourceCode

## 用管理员权限打开cmd

输入如下指令：

> mklink /j "C:\Users\卢华源\OneDrive - stu.haut.edu.cn\SourceCode" "E:\SourceCode"

需要注意：

- `C:\Users\卢华源\OneDrive - stu.haut.edu.cn`是onedrive的工作目录，仅仅进入onenote的根目录无法看到：如图：

![1547889843403](images\1547889843403.png)

​	必须要进入任意onedrive下的文件夹，此时资源管理器的路径则可以显示真正的工作目录：

​	如下图：

​	![1547890044361](images\1547890044361.png)

