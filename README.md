# 前言
本项目专为宝塔主机设计，用于扫描所有文件以检测是否存在敏感词汇，包括涉黄、涉赌、涉毒以及政治违法网站链接等内容。项目初衷是帮助免费公益主机维护网络健康环境，防止不法分子利用主机进行非法活动，避免运营者因此被约谈。
## 应用场景
本人已将该项目应用于自己的免费 API 项目，旨在为所有用户提供方便快捷的 API 测试服务，实现高效、零成本上云体验。
公益主机获取方式：访问 https://api.aa1.cn/user，注册账号后即可在“免费产品”中领取免费主机。
违禁词列表公示网站：https://mgcku.api.aa1.cn

# 部署环境
以下是运行该项目所需的依赖和部署环境提示：
## 1. 必要的依赖库
请确保安装以下 Python 库，可通过 pip 安装：
pip install requests smtplib mysql-connector-python flask
### 依赖说明：
os: Python 内置模块，无需安装。
requests: 用于发送 HTTP 请求。
smtplib: Python 内置模块，用于发送电子邮件。
email.mime: Python 内置模块，用于构造电子邮件内容。
datetime: Python 内置模块，用于时间和日期处理。
mysql.connector: 用于连接和操作 MySQL 数据库。
flask: 用于构建 Web 服务和前端界面渲染。
time: Python 内置模块，用于时间操作。
threading: Python 内置模块，用于多线程处理。
queue: Python 内置模块，用于线程间的任务队列管理。
## 2. 部署环境要求
系统要求：
操作系统: Linux (推荐，如 Ubuntu)、Windows、macOS。
Python 版本: 3.7 或更高版本。
数据库：
MySQL: 请确保已安装并运行 MySQL 数据库，推荐版本 5.6 或更高版本。
配置数据库连接信息时，需要确保正确设置 host、user、password 和 database。

### 3. 前端环境
PHP 7.2 
