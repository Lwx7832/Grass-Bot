 # Grass-Bot
这是一个专为Grass小草第二季空投设计的挂机机器人

## 功能
✅ 支持多个 UID

✅ 支持自定义代理

## 安装步骤
将此仓库克隆到你的本地环境：

 ```bash
git clone https://github.com/Lwx7832/grass-bot.git


 ```
进入项目目录：
 ```bash
cd grass-bot
 ```
## 安装所需依赖项：
 ```bash
npm install
 ```

## 使用说明
获取用户 ID：

注册并且登录到 Grass 网站: https://app.getgrass.io/register/?referralCode=kVk6fmWmq_kEWLN

打开浏览器开发者工具（通常按 F12 或右键选择“检查”）。

切换到“控制台”选项卡。

输入以下命令并按回车：

```bash
localStorage.getItem('userId');
 ```
复制返回的值，这就是你的用户 ID。

创建用户 ID 文件：

在项目目录中创建一个名为 uid.txt 的文件，每行写一个用户 ID，例如：

```bash
123123213
12313123
```
添加代理信息：

创建一个名为 proxy.txt 的文件，并按行添加你的代理 URL，格式如下：
```bash

http://username:password@hostname:port
socks5://username:password@hostname:port
```
启动机器人：

在终端中执行以下命令运行 Grass-Bot：
```bash
npm start

```
推荐代理：
https://iproyal.com/?r=696527
https://www.webshare.io/?referral_code=2dqzq35te8tq
