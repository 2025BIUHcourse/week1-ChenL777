# Week1 实验报告
## 1.实验任务
1. 安装Windows+Ubuntu双系统，完成对应截图；
2. 安装并配置VSCode，在VSCode中运行C++的Hello world程序；
3. 学习Git核心命令，加入GitHub小组并将作业提交至对应仓库；
4. 编写Markdown实验报告，完整记操过程，问题与总结
## 2.实现过程（含主要步骤与截图）
### 2.1双系统安装
1. 前期准备：下载Ubuntu镜像并制作启动盘，调整BIOS设置；
2. 系统安装：完成Ubuntu安装后，配置GRUB启动菜单，确保双系统可正常切换；
3. 截图收集：！[双系统界面](image/12.5截图3.jpg)
！[Ubuntu桌面](image/12.5截图2.png)
![hello](/home/chenl777/图片/2025-12-05 16-04-07屏幕截图.png)
### 2.2 VSCode安装与配置
1. 安装VSCode：在Ubuntu终端执行指令完成VSCode安装；
2. 扩展安装：安装必要的扩展
3. 程序运行：编写Hello World C++程序，在VSCode中完成编译与运行，验证环境正常
4. 截图收集！[hello world](image/12.5截图1.png)
### 2.3 Git学习与作业上传
1. 环境配置：Ubuntu下安装git工具，执行sudo apt install git -y完成安装；
2. 仓库操作：

   ◦ 进入项目文件夹：cd ~/hello\ world；

   ◦ 初始化仓库：git init；

   ◦ 配置用户身份：
    git config --global user.name "ChenL777"
    
    git config --global user.email "770902703@qq.com"
   
   ◦ 提交代码：git add . → git commit -m "week1 submit"；

   ◦ 关联远程仓库：git branch -M main → git remote add origin https://github.com/小组仓库地址.git；

◦ 推送作业：git push -u origin main（解决TLS连接异常后完成推送）；

3. 截图收集：
## 3.遇到的问题与解决方法
###