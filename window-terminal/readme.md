# [地址](https://www.cnblogs.com/xiaojiluben/p/15524315.html)

## 效果

![右键菜单](https://img2020.cnblogs.com/blog/1846511/202111/1846511-20211108150032590-1287448283.png)

![在当前目录打开终端](https://img2020.cnblogs.com/blog/1846511/202111/1846511-20211108150121570-1400029299.png)

## 开始
1. 下载[ContextMenuManager](https://github.com/BluePointLilac/ContextMenuManager)

2. 安装window terminal，并配置好各种终端（cmd,powershell,wsl,git Bash)

3. 打开ContextMenuManager，
>目录背景 - 新增 - 类型（shell)
```shell
# 菜单命令，如果window terminal的环境变量配好了，直接输wt就可以
# 如果没有配环境变量，直接选择windowTerminal.exe的那个文件

# 打开cmd的命令
wt -p "命令提示符" -d .

# 打开centos wsl2的命令
wt -p "CentOS" -d .

# 打开git Bash的命令
wt -p "Git Bash" -d .
```

