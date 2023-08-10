# 预告：教程将有大改，大纲已基本列出
# 置顶教程：
**[全网最详细的解锁 SSH ShellClash 搭配 AdGuardHome 安装和配置教程](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%85%A8%E7%BD%91%E6%9C%80%E8%AF%A6%E7%BB%86%E7%9A%84%E8%A7%A3%E9%94%81%20SSH%20ShellClash%20%E6%90%AD%E9%85%8D%20AdGuardHome%20%E5%AE%89%E8%A3%85%E5%92%8C%E9%85%8D%E7%BD%AE%E6%95%99%E7%A8%8B.md)**  
**[ShellClash 和 AdGuardHome 快速安装教程](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/ShellClash%20%E5%92%8C%20AdGuardHome%20%E5%BF%AB%E9%80%9F%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B.md)**

---

# Clash 教程合集
# 一、 geo 方案
- 此方案采用 `GEOSITE` 和 `GEOIP` 规则搭配 geosite.dat 和 geoip.dat（或 Country.mmdb） 路由规则文件
## 1. 基础篇
### ① [生成带有自定义规则和代理组的配置文件 yaml 直链 geo 方案](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%9F%BA%E7%A1%80%E7%AF%87/%E7%94%9F%E6%88%90%E5%B8%A6%E6%9C%89%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A7%84%E5%88%99%E5%92%8C%E4%BB%A3%E7%90%86%E7%BB%84%E7%9A%84%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6%20yaml%20%E7%9B%B4%E9%93%BE%20geo%20%E6%96%B9%E6%A1%88.md)
### ② [ShellClash 设置](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%9F%BA%E7%A1%80%E7%AF%87/ShellClash%20%E9%85%8D%E7%BD%AE.md)
### ③ [Clash Verge 设置](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%9F%BA%E7%A1%80%E7%AF%87/Clash%20Verge%20%E9%85%8D%E7%BD%AE.md)
## 2. 进阶篇
### 1. [ShellClash 本地配置自定义规则和代理组 geo 方案](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E8%BF%9B%E9%98%B6%E7%AF%87/ShellClash%20%E6%9C%AC%E5%9C%B0%E9%85%8D%E7%BD%AE%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A7%84%E5%88%99%E5%92%8C%E4%BB%A3%E7%90%86%E7%BB%84%20geo%20%E6%96%B9%E6%A1%88.md)
### 2. [ShellClash 使用 Clash.Meta 内核进行 DNS 分流教程 geo 方案](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E8%BF%9B%E9%98%B6%E7%AF%87/ShellClash%20%E4%BD%BF%E7%94%A8%20Clash.Meta%20%E5%86%85%E6%A0%B8%E8%BF%9B%E8%A1%8C%20DNS%20%E5%88%86%E6%B5%81%E6%95%99%E7%A8%8B%20geo%20%E6%96%B9%E6%A1%88.md)
### 3. [Clash Verge 使用 Clash.Meta 内核进行 DNS 分流教程 geo 方案](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E8%BF%9B%E9%98%B6%E7%AF%87/Clash%20Verge%20%E4%BD%BF%E7%94%A8%20Clash.Meta%20%E5%86%85%E6%A0%B8%E8%BF%9B%E8%A1%8C%20DNS%20%E5%88%86%E6%B5%81%E6%95%99%E7%A8%8B%20geo%20%E6%96%B9%E6%A1%88.md)
## 3. 分享自己使用的 geo 方案和配置
### 1. 分享自己使用的一套 ShellClash geo 方案
### 2. 分享自己使用的一套 Clash Verge geo 方案
# 二、 rule-set 方案
- 注：此方案采用 `RULE-SET` 规则搭配 `rule-providers` 配置项
## 1. 基础篇
### ① [生成带有自定义规则和代理组的配置文件 yaml 直链 ruleset 方案](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%9F%BA%E7%A1%80%E7%AF%87/%E7%94%9F%E6%88%90%E5%B8%A6%E6%9C%89%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A7%84%E5%88%99%E5%92%8C%E4%BB%A3%E7%90%86%E7%BB%84%E7%9A%84%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6%20yaml%20%E7%9B%B4%E9%93%BE%20ruleset%20%E6%96%B9%E6%A1%88.md)
### ② [ShellClash 设置](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%9F%BA%E7%A1%80%E7%AF%87/ShellClash%20%E9%85%8D%E7%BD%AE.md)
### ③ [Clash Verge 设置](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%9F%BA%E7%A1%80%E7%AF%87/Clash%20Verge%20%E9%85%8D%E7%BD%AE.md)
### ④ [Clash.Meta for Android 推荐设置](https://github.com/DustinWin/clash-tutorials/blob/main/%E6%95%99%E7%A8%8B%E5%90%88%E9%9B%86/%E5%9F%BA%E7%A1%80%E7%AF%87/Clash.Meta%20for%20Android%20%E6%8E%A8%E8%8D%90%E8%AE%BE%E7%BD%AE.md)
## 2. 进阶篇
### 1. ShellClash 本地配置自定义规则和代理组 rule-set 方案
ShellClash 相关设置
### 2. ShellClash 使用 Clash.Meta 内核进行 DNS 分流教程 rule-set 方案
ShellClash 相关设置
### 3. Clash Verge 使用 Clash.Meta 内核进行 DNS 分流教程 rule-set 方案
Clash Verge 相关设置
## 3. 分享自己使用的 rule-set 方案和配置
### 1. 分享自己使用的一套 ShellClash rule-set 方案
### 2. 分享自己使用的一套 Clash Verge rule-set 方案
# 给作者加鸡腿：
## 支付宝
![167673823486183](https://user-images.githubusercontent.com/45238096/219877760-b385af34-ebbd-438e-a31f-cd2b985047bb.png)
# 机场推荐（薯条 CNIX，自用，我愿称之为打不死的小强）：  
## [邀请链接 1](https://av1.wtf/auth/register?code=nPLT)  
## [邀请链接 2](https://av1.wtf/#/auth/register?code=nPLT)
