# 独显笔记本 配置

1. 不要联网，完成微软的设置
2. 卸载mcafaa，包括上网和本体
3. 打开添加和删除功能，勾选**linux子系统**和**虚拟机平台**
4. 重启电脑
5. 下载内核更新包：https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi
6. 下载ubuntu发行版：https://aka.ms/wslubuntu2004
7. 下载wsl的显卡驱动
8. 重启
9. 安装cuda-toolkit，百度搜索wsl cuda，进入英伟达文档后，按步骤进行安装。注意把11.4改为pytorch支持的11.3
10. 安装anaconda
11. 安装pytorch