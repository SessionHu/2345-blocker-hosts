# 2345 BLOCKER HOSTS
- 使用`HOSTS`文件阻止对`2345.com`及其附属网站的访问，以保护您和您的家人的设备免受其的困扰。

## 原理
- 通过`hosts`文件，跳过DNS服务器，将2345的网站解析至`0.0.0.0`以达到无法访问的目的。

## 使用方法
1. 打开本存储库中的[hosts](./hosts)文件并下载
2. 将下载的`hosts`文件的内容覆盖或添加至您设备的`hosts`文件中
  - **Windows**的`hosts`文件为`%windir%\System32\drivers\etc\hosts`
  - **Linux**的`hosts`文件为`/etc/hosts` *(Android基于Linux)*
3. 为确保作用，请刷新设备DNS缓存，并重新启动操作系统

## 许可证
- 本项目使用`CC-BY-SA-4.0`许可证进行使用和传播
- 灵感来源：[zoln/baidu-hosts](https://github.com/zoln/baidu-hosts.git "屏蔽百度的hosts配置")
