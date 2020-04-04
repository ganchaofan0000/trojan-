# trojan-一键脚本（三步）搭建
网址：https://www.v2rayssr.com/trojan-2.html

1.解析域名
## 域名申请

### 一.进入[freenom](https://www.freenom.com/zh/index.html?lang=zh)注册域名

#### 1.进入[身份大全](http://shenfendaquan.com/)获得一个美国身份信息

#### 2.在freenom选择(1)Partners->(2)Developers->(3)Get a random..today!->(4)邮箱验证->(5)重复（1）（2）（3）->(6)填写从身份大全得到的信息->完成注册直接申请域名（选择12个月有效期）

### 二.进入[Cloudflare](https://www.cloudflare.com/)解析域名

#### 1.将域名绑定的地址更改为它提示的地址等待片刻就可以

#### 2.生成二级域名

2.一键脚本三步

（1）wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojansh/master/trojan1.sh" && chmod +x trojan1.sh && ./trojan1.sh

（2）wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojansh/master/trojan2.sh" && chmod +x trojan2.sh && ./trojan2.sh

（3）wget -N --no-check-certificate "https://raw.githubusercontent.com/V2RaySSR/Trojansh/master/trojan3.sh" && chmod +x trojan3.sh && ./trojan3.sh

3.安装bbrplus加速

wget -N --no-check-certificate "https://github.com/ylx2016/Linux-NetSpeed/releases/download/sh/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
