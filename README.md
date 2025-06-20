# Virgol - 渗透测试综合工具

![GitHub release](https://img.shields.io/github/release/VirgoLee/Virgol.svg)
[![License](https://img.shields.io/badge/微信公众号-安全处女座-orange.svg)](https://mp.weixin.qq.com/s/Nz32s0LLVLiT64HeNtYi8A)

![欢迎](https://i-blog.csdnimg.cn/direct/9a6fe224f0e1443b9dbbf6a91962ba70.png)

## 简介

Virgol 是一个面向安全研究人员和渗透测试员设计的综合型渗透测试工具集。它整合了多种功能模块。Virgol 的目标是为用户提供一个一站式解决方案，以满足在不同场景下的安全测试需求。

## 功能

- **基本资产信息**：获取目标的基本网络信息，包括IP地址、域名注册详情等。
- **资产测绘**：通过网络空间测绘引擎搜索，支持FOFA、Quake、Hunter、ZoomEye、00信安。
- **子域名收集**：利用域名爆破来发现子域名。
- **指纹识别**：自动检测Web服务器、应用程序和服务的类型及其版本，辅助识别已知漏洞。
- **端口探测**：执行TCP/UDP端口扫描，确定开放的服务和潜在的可利用点。
- **敏感信息**：搜索URL页面中的敏感信息，如JSFinder功能。
- **目录扫描**：基于字典攻击或智能猜测，检测Web应用中未列出的文件和目录。
- **代理功能**：代理探测流量至其他工具，进行联动。
- **漏洞扫描**：基于POC进行漏洞扫描，包含POC自定义、POC导入、POC管理等功能。
- **Fuzz测试**：对URL参数、表单输入等进行模糊测试，用于发现注入漏洞或其他输入验证错误。
- **编码加解密**：支持多种常见的编码和加密算法，方便处理各种格式的数据。
- **社工字典生成**：根据特定的人物信息或组织结构生成个性化的密码猜测列表。
- **反弹Shell生成**：创建定制化的shell代码，以便于在授权环境中进行远程命令执行。
- **程序启动器**：内置系统常用软件启动方式，亦可自行配置其他软件，形成自己的工具箱。
- **网站导航**：集合了多个网络安全领域的权威资源链接，便于快速查阅。
- ...

## 安装与使用

### 系统要求

- Windows、MAC、Linux
- v2.x.x版本及以上，下载对应版本的Virgol即可！
- 另外：v1.x.x版本需 Java 1.8（更高版本也可，但需安装JavaFX，请自行搜索）

### 使用方式
#### v2.x.x及以上版本
- 双击即可使用
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/3133c75181934b929e4e27a7b437a3b8.png)
#### v1.x.x版本
![](https://i-blog.csdnimg.cn/direct/8257f9dc9f084846a72084e1ef27ee69.png)
- windows双击 start.bat
- mac、linux运行 start.sh

### Virgol界面
#### 首页
![首页](https://i-blog.csdnimg.cn/direct/7fd90dfca00d47229d12562c370dcbea.png)
#### 漏洞扫描
![漏扫扫描](https://i-blog.csdnimg.cn/img_convert/5181d111bd71e46e1629cf2d2dc64243.png)
#### POC管理
![POC管理](https://i-blog.csdnimg.cn/img_convert/c3741fe2c5a66b03178cfb60d60e0b5f.png)
#### 自定义POC功能
![自定义POC功能](https://i-blog.csdnimg.cn/img_convert/f055b1ab03bec95bf7338e7483b6e0eb.png)
#### 敏感信息
![敏感信息](https://i-blog.csdnimg.cn/direct/7b813a1218914621b716cc31cbd83a2f.png)
#### 编码加解密
![编码加解密](https://i-blog.csdnimg.cn/direct/9f9b66cb41674255975c6298243be56a.png)
#### 反弹Shell生成
![反弹Shell生成](https://i-blog.csdnimg.cn/direct/214494ffc9c440f183ad0c54dafb507d.png)
#### 社工字典生成
![社工字典生成](https://i-blog.csdnimg.cn/direct/7a1fa2b74a02498aaec1528082ef2e89.png)
#### 命令查询
![命令查询](https://i-blog.csdnimg.cn/direct/26e674683cf942c7888f82136d4d7af1.png)
#### 工具箱-JWT
![工具箱-JWT](https://i-blog.csdnimg.cn/direct/6c9443c8e53a4ab780f3e61dfc7230c0.png)
#### Markdown编辑器
![Markdown编辑器](https://i-blog.csdnimg.cn/direct/d01770d437e84fa8a5c04693a54a3e7c.png)
#### 程序启动器
![程序启动器](https://i-blog.csdnimg.cn/direct/37b9879a9d774effaabe62a6278b6d3e.png)
#### 网址导航
![网址导航](https://i-blog.csdnimg.cn/direct/3a749922dedb41f1b0dec3a65312b64e.png)


## 联系作者

### 邮箱

- a_leyilea@163.com

| 个人微信 | 微信公众号 | 打赏码 |
|--|--|--|
| ![个人微信](https://images.cnblogs.com/cnblogs_com/blogs/769113/galleries/2422690/o_250102060507_%E4%B8%AA%E4%BA%BA%E5%BE%AE%E4%BF%A1.png) | ![微信公众号](https://images.cnblogs.com/cnblogs_com/blogs/769113/galleries/2422690/o_250102060507_%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7.png) |![赞赏码](https://images.cnblogs.com/cnblogs_com/blogs/769113/galleries/2422690/o_250102060507_%E6%89%93%E8%B5%8F%E7%A0%81.png)|


## 免责声明

请注意，Virgol 是一款渗透测试工具，其设计初衷是为了帮助专业人士进行合法的安全评估。开发者不对因非法或未经授权使用本软件而导致的任何损害负责。在使用Virgol之前，请确保您拥有目标系统的明确书面授权，并遵守当地法律法规。对于任何违法活动，我们将不承担任何责任。

## Star History  

![Star History Chart](https://api.star-history.com/svg?repos=VirgoLee/Virgol&type=Date)
