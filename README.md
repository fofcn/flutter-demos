# flutter组件代码碎片
flutter代码碎片



flutter国内镜像

1 flutter清华镜像

1.1 windows设置方式

临时设置方式：

xcode: 菜单栏-》Terminal-》New Terminal

打开Terminal后执行命令：

```
set FLUTTER_STORAGE_BASE_URL="https://mirrors.tuna.tsinghua.edu.cn/flutter"
set PUB_HOSTED_URL="https://mirrors.tuna.tsinghua.edu.cn/dart-pub"
```

永久设置方式：设置系统环境变量：



1.2 mac设置方式

临时设置方式：

打开终端，执行以下命令：

```
export FLUTTER_STORAGE_BASE_URL="https://mirrors.tuna.tsinghua.edu.cn/flutter"
export PUB_HOSTED_URL="https://mirrors.tuna.tsinghua.edu.cn/dart-pub"
```



永久设置方式：

如果~/.bashrc不存在，手动新建即可

```
echo 'export FLUTTER_STORAGE_BASE_URL="https://mirrors.tuna.tsinghua.edu.cn/flutter"' >> ~/.bashrc
echo 'export PUB_HOSTED_URL="https://mirrors.tuna.tsinghua.edu.cn/dart-pub"' >> ~/.bashrc
```