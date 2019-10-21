# VEngine 基于v2ray开发的VPN服务器软件
### 特点 
+ 配置简单

+ 支持自动tls+websocket配置

+ Web 管理页面方便用户管理

### 操作系统支持
+ linux AMD64
#### 其它系统未编译，有需要可以提[issue](https://github.com/vengine-admin/VEngine/issues)
### VEngine 安装
#### 1.安装需要root权限(非root用户先运行命令`sudo -s`)，运行如下命令
`bash <(curl -L https://github.com/vengine-admin/VEngine/releases/latest/download/install.sh)`

#### 2.复制你的服务器屏幕输出的vmess链接, vemss://eyJ2I...这个很长的一行（如：以下是VEngine输出示例），顺便记一下最后一行Server Key
```
VEngine version(0.1.2)
Loading VEngine config from network...
VEngine config load ok!
Proxy tls websocker:
        Address:        3.23.12.204
        Domain:         rufous.supereasy.ml
        Path:           /djgukw
        Port:           433

UUID:8c0d3a8e-55be-4a2e-9789-6c327e0237f9  alterid:64  level:0

vmess://eyJ2IjoiMiIsInBzIjoicnVmb3VzLnN1cGVyZWFzeS5tbC04YzBkM2E4ZSIsImFkZCI6InJ1Zm91cy5zdXBlcmVhc3kubWwiLCJwb3J0IjoiNDQzIiwiaWQiOiI4YzBkM2E4ZS01NWJlLTRhMmUtOTY2OS02YzMyN2UwMjM3ZjkiLCJhaWQiOiI2NCIsIm5ldCI6IndzIiwidHlwZSI6Im5vbmUiLCJob3N0IjoicnVmb3VzLnN1cGVyZWFzeS5tbCIsInBhdGgiOiIvZGpndWt3IiwidGxzIjoidGxzIn0= 

Server Key : 44d128764293474ca4fedd99245cb7a7
```
#### 3.粘帖vmess链接到你的[V2RayN(windows用户)](https://github.com/233boy/v2ray/wiki/V2RayN%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B) V2RayX(mac 用户），服务器配置中。现在可以科学上网了！
+ iOS,Android客户端，网上教程很多，这里不说了。。。

### Mac 用户的V2rayX 导入vmess链接流程
###### 1.打开菜单 选择Configure
![](https://github.com/vengine-admin/VEngine/blob/master/v2rayx1.png "menu")

###### 2.点击import按钮
![](https://github.com/vengine-admin/VEngine/blob/master/v2rayx2.png "import")
###### 3.选择import from other links...
![](https://github.com/vengine-admin/VEngine/blob/master/v2rayx3.png "import")
###### 4.粘贴vmess链接到输入框，点击OK后可以看到新的Server配置完成，名子大概是这样 rufous.supereasy.ml-8c0d3a8e
![](https://github.com/vengine-admin/VEngine/blob/master/v2rayx4.png "import")
###### 5.之后在Server菜单中选择刚刚加入的Server，再单击菜单Load core。打开浏览器，输入 www.google.com 回车！无墙的感觉真好。。。

### VEngine Web 管理设置(非必须）

#### 目前功能，添加删除帐号（UUID）

#### 1.注册用户
访问 [vengine.cf](https://www.vengine.cf) ，点 [快速注册帐号](https://www.vengine.cf/sign-up) 填写EMail,然后接收邮件认证就可以了。

#### 2.绑定主机
登录后可以看到绑定主机，要求输入Server Key，输入上面VEngine运行输出的最后一行32位的字符串，绑定主机之后可以添加用户了。

#### 3.生成帐号
点击右侧生成帐号按钮，会弹出新生成帐号的UUID与vmess链接。





      
