# Virgol - 渗透测试综合工具

![GitHub release](https://img.shields.io/github/release/VirgoLee/Virgol.svg)
[![License](https://img.shields.io/badge/微信公众号-安全处女座-orange.svg)](https://mp.weixin.qq.com/s/Nz32s0LLVLiT64HeNtYi8A)

## 简介

Virgol 是一个面向安全研究人员和渗透测试员设计的综合型渗透测试工具集。它整合了多种功能模块。Virgol 的目标是为用户提供一个一站式解决方案，以满足在不同场景下的安全测试需求。

## 特性

- **基本资产信息**：获取目标的基本网络信息，包括IP地址、域名注册详情等。
- **资产测绘**：通过网络空间测绘引擎搜索，支持FOFA、Quake、Hunter、ZoomEye、00信安。
- **子域名收集**：利用域名爆破来发现子域名。
- **指纹识别**：自动检测Web服务器、应用程序和服务的类型及其版本，辅助识别已知漏洞。
- **端口探测**：执行TCP/UDP端口扫描，确定开放的服务和潜在的可利用点。
- **敏感信息**：搜索URL页面中的敏感信息，如JSFinder功能。
- **目录扫描**：基于字典攻击或智能猜测，检测Web应用中未列出的文件和目录。
- **Fuzz 测试**：对URL参数、表单输入等进行模糊测试，用于发现注入漏洞或其他输入验证错误。
- **编码加解密**：支持多种常见的编码和加密算法，方便处理各种格式的数据。
- **社工字典生成**：根据特定的人物信息或组织结构生成个性化的密码猜测列表。
- **反弹Shell生成**：创建定制化的shell代码，以便于在授权环境中进行远程命令执行。
- **程序启动器**：内置系统常用软件启动方式，亦可自行配置其他软件，形成自己的工具箱。
- **网站导航**：集合了多个网络安全领域的权威资源链接，便于快速查阅。

## 安装与使用

### 系统要求

- Windows、MAC、Linux
- v2.x.x版本及以上，下载对应版本的Virgol即可！
- 另外：v1.x.x版本需 Java 1.8（更高版本也可，但需安装JavaFX，请自行搜索）

### 使用方式
#### v2.x.x及以上版本
- 双击即可使用
#### v1.x.x版本
![](https://i-blog.csdnimg.cn/direct/8257f9dc9f084846a72084e1ef27ee69.png)
- windows双击 start.bat
- mac、linux运行 start.sh

### 界面

#### 基本资产信息

![](https://i-blog.csdnimg.cn/direct/7f040e757a2b47cba5bf77a4268b3b06.png)

#### 资产测绘

![](https://i-blog.csdnimg.cn/direct/09f0d44d07b94f06bfce90a7323d7fb7.png)

#### 目录扫描

![](https://i-blog.csdnimg.cn/direct/93b7ade9642d4e8f8dc3d404634492ab.png)

#### 子域名收集

![](https://i-blog.csdnimg.cn/direct/7fb4d104df0f4b4eacc47e9316150a24.png)

#### 编码加解密

![](https://i-blog.csdnimg.cn/direct/ce53046148324e24ad89256d202c51e2.png)

#### 端口探测

![](https://i-blog.csdnimg.cn/direct/ad31c32685c24b02897ba1ff7e798b0f.png)

#### 指纹识别

![](https://i-blog.csdnimg.cn/direct/4f4771ae383e408a8e17e4cfc74ad499.png)

#### Toolsets

![](https://i-blog.csdnimg.cn/direct/f83110be0f224f3ba6d35b733b7afeb3.png)

#### 社工字典生成

![](https://i-blog.csdnimg.cn/direct/258dc4e979374ab296e095b3dd5904a4.png)

#### 反弹Shell生成

![](https://i-blog.csdnimg.cn/direct/130df838d8564c3ea379fe003bdb9b97.png)

#### 知识库

![](https://i-blog.csdnimg.cn/direct/648e620f83694c779cbbcac19385e9bd.png)

#### 网站导航

![](https://i-blog.csdnimg.cn/direct/a88fc93b1b6443dbbe6a273295c3b04c.png)

## 联系作者

### 邮箱

- a_leyilea@163.com

### 个人微信
<img src="https://images.cnblogs.com/cnblogs_com/blogs/769113/galleries/2422690/o_250102060507_%E4%B8%AA%E4%BA%BA%E5%BE%AE%E4%BF%A1.png" alt="个人微信" width="300">

### 微信公众号
<img src="https://images.cnblogs.com/cnblogs_com/blogs/769113/galleries/2422690/o_250102060507_%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7.png" alt="微信公众号" width="600">

### 打赏码
<img src="https://images.cnblogs.com/cnblogs_com/blogs/769113/galleries/2422690/o_250102060507_%E6%89%93%E8%B5%8F%E7%A0%81.png" alt="打赏吗" width="300">

## 致谢

工具开发中参考了很多知名工具，在此一并感谢。

- 重剑无锋大佬的无影项目：[https://github.com/TideSec/TscanPlus](https://github.com/TideSec/TscanPlus)
- kkbo(虎哥)大佬的密探项目：[https://github.com/kkbo8005/mitan](https://github.com/kkbo8005/mitan)

## 免责声明

请注意，Virgol 是一款渗透测试工具，其设计初衷是为了帮助专业人士进行合法的安全评估。开发者不对因非法或未经授权使用本软件而导致的任何损害负责。在使用Virgol之前，请确保您拥有目标系统的明确书面授权，并遵守当地法律法规。对于任何违法活动，我们将不承担任何责任。

## Star History  

![Star History Chart](https://api.star-history.com/svg?repos=VirgoLee/Virgol&type=Date)
