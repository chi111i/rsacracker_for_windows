# rsacracker_for_windows
rsacracker windows打包版本

由于在windows中pacman和`cargo build --release` 占用大量C盘空间，且有大量报错。将自己编译好的exe供大家使用

![图片](https://github.com/user-attachments/assets/ce54c7c0-85f0-4324-9792-3c76f0cc75ab)
# 使用
安装 https://developer.microsoft.com/zh-cn/windows/downloads/windows-sdk/ 和 https://slproweb.com/products/Win32OpenSSL.html 并加入环境变量

`rsacracker -r data.txt`

data.txt数据格式

```
n=3421434....
e=1242....
c=324....
dp=312....
dq=24234....
```
