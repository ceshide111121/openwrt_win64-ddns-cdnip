
### 相关教程请查看[甬哥博客与视频教程](https://ygkkk.blogspot.com/2023/09/openwrt-cdnip.html)

### 一键脚本
```
curl -ksSL https://gitlab.com/rwkgyg/cdnopw/raw/main/cdnopw.sh -o cdnopw.sh && bash cdnopw.sh
```
### 进入脚本快捷方式：```bash cdnopw.sh```
--------------------------------------

![47918a52b4d93487e5e7935d5916d34](https://github.com/yonggekkk/openwrt_win64-ddns-cdnip/assets/121604513/dd6758ec-f8d4-4a6c-b51d-9144ec993193)

-----------------------------------------------------
### 交流平台：[甬哥博客地址](https://ygkkk.blogspot.com)、[甬哥YouTube频道](https://www.youtube.com/@ygkkk)、[甬哥TG电报群组](https://t.me/+jZHc6-A-1QQ5ZGVl)、[甬哥TG电报频道](https://t.me/+DkC9ZZUgEFQzMTZl)
-----------------------------------------------------
### 感谢你右上角的star🌟
[![Stargazers over time](https://starchart.cc/yonggekkk/openwrt_win64-ddns-cdnip.svg)](https://starchart.cc/yonggekkk/openwrt_win64-ddns-cdnip)

----------------------------------------
### 参考项目：[lee1080](https://github.com/lee1080/CloudflareSpeedTestDDNS)

### 感谢：CF优选IP库及程序作者[badafans](https://github.com/badafans/Cloudflare-IP-SpeedTest)、[XIU2](https://github.com/XIU2/CloudflareSpeedTest)

---------------------------------------
#### 声明：

#### 该项目使用base64加密，可自行解密，介意者请勿使用，[加密原因在此](https://ygkkk.blogspot.com/2022/06/github.html)

#### 所有代码来源于Github社区与ChatGPT的整合；如您需要开源代码，请提Issues留下您的联系邮箱

注意计划任务里面加上定时优选
0 3 * * * cd /root/cfipopw/ && bash cdnip.sh

