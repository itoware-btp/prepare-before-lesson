# 课程准备

（此文档后续同步更新，建议收藏该链接）

## 1. 注册BTP账户
1. 详细步骤请参照[https://developers.sap.com/tutorials/hcp-create-trial-account..html](https://developers.sap.com/tutorials/hcp-create-trial-account..html)，使用邮箱（个人或者公司均可）创建并激活BTP Trial账户。注意：请选择“US East (VA) - AWS”地区，请勿选择新加坡地区。
2. 注册[https://github.com/](https://github.com/)账户，注册成功之后，将注册邮箱发到群里并@Stefan老师汇总，后续会统一分配代码仓库的权限。

## 2. 软件

1. 自行下载并安装Chrome浏览器（强烈建议使用Chrome，如果公司电脑有管控不允许安装软件，也可以使用FireFox或者Edge浏览器）
2. 自行下载并安装Postman软件[https://www.postman.com/downloads/](https://www.postman.com/downloads/)（建议在本地电脑上安装该软件，如果公司电脑有管控不允许安装软件，后续会演示在线版本[https://web.postman.co/workspace/btp_training_202410~23e87d4f-2948-406b-904c-924f9410fefb/overview](https://web.postman.co/workspace/btp_training_202410~23e87d4f-2948-406b-904c-924f9410fefb/overview)）
3. 在这里下载课程所需要的软件包[https://cloud.189.cn/web/share?code=eQRJrmFBba6f](https://cloud.189.cn/web/share?code=eQRJrmFBba6f)（访问码：8fmf）

## 3. 课程代码仓库

Github的注册邮箱发送给老师之后，会分配课程仓库的权限，之后即可打开[课程代码仓库](https://github.com/itoware-btp/btp_training_202410)

## 4. Github打不开时的解决办法

如果Github打不开，按照以下方式手动修改电脑的Host文件：
Windows系统：打开 C:\Windows\System32\drivers\etc 找到hosts文件，增加以下内容

```
185.199.108.154                                     github.githubassets.com
140.82.112.21                                            central.github.com
185.199.109.133                               desktop.githubusercontent.com
185.199.111.153                                       assets-cdn.github.com
185.199.108.133                                  camo.githubusercontent.com
185.199.109.133                                       github.map.fastly.net
151.101.129.194                                github.global.ssl.fastly.net
140.82.112.4                                                gist.github.com
185.199.108.153                                                   github.io
140.82.114.4                                                     github.com
140.82.114.6                                                 api.github.com
185.199.108.133                                   raw.githubusercontent.com
185.199.109.133                           user-images.githubusercontent.com
185.199.110.133                              favicons.githubusercontent.com
185.199.110.133                              avatars5.githubusercontent.com
185.199.109.133                              avatars4.githubusercontent.com
185.199.108.133                              avatars3.githubusercontent.com
185.199.109.133                              avatars2.githubusercontent.com
185.199.109.133                              avatars1.githubusercontent.com
185.199.110.133                              avatars0.githubusercontent.com
185.199.109.133                               avatars.githubusercontent.com
140.82.113.9                                            codeload.github.com
54.231.132.25                                 github-cloud.s3.amazonaws.com
52.216.76.180                                   github-com.s3.amazonaws.com
52.217.12.116       github-production-release-asset-2e65be.s3.amazonaws.com
54.231.161.1           github-production-user-asset-6210df.s3.amazonaws.com
52.217.38.196     github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.110.153                                            githubstatus.com
140.82.114.17                                              github.community
185.199.110.133                                 media.githubusercontent.com
185.199.111.133                               objects.githubusercontent.com
185.199.111.133                                              raw.github.com
20.221.80.166                           copilot-proxy.githubusercontent.com
```