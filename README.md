# VEngine 基于v2ray开发的VPN服务器软件
  特点 
    1.配置简单
    2.支持自动tls+websocket配置
    3.Web 管理页面方便用户管理
### 操作系统支持
#### 1.linux AMD64
#### 其它系统未编译，有需要可以提[issue](https://github.com/vengine-admin/VEngine/issues)
### VEngine 安装
#### 1.安装需要root权限(非root用户先运行命令`sudo -s`)，运行如下命令
`bash <(curl -L https://github.com/vengine-admin/VEngine/releases/latest/download/install.sh)`

#### 2.复制你的服务器屏幕输出的vmess链接,在最后一行（如下是VEngine输出示例）
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
```
#### 3.粘帖vmess链接到你的[V2RayN(windows用户)](https://github.com/233boy/v2ray/wiki/V2RayN%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B) V2RayX(mac 用户）配置中
      Mac 用户的V2rayX 导入vmess链接以下流程
      
