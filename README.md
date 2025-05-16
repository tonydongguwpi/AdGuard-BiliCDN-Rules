# AdGuard-BiliCDN-Rules
**屏蔽 Bilibili 低质量 PCDN/MCDN，强制使用高速镜像 CDN！**  

通过 DNS/代理规则过滤 B 站的低质量 PCDN（如 `mcdn.bilivideo.cn`）和京东云 MCDN，自动选择阿里云、腾讯云等优质 CDN 节点，提升视频加载速度和稳定性。  

👉 **适用于**：AdGuard Home / DNS 服务器 / 代理工具（Clash、Surge）  

---

## 📦 功能特性  
- ✅ 屏蔽所有已知 B 站 PCDN 域名（`mcdn.bilivideo.cn`, `szbdyd.com` 等）  
- ✅ 保留高质量 Mirror CDN（阿里云、腾讯云、华为云节点）  
- ✅ 可选支持京东云 MCDN 屏蔽  
- ✅ 兼容 IPv6 环境优化  
- 📌 基于社区实测数据，持续更新规则  

---

## 🛠️ 快速使用  
### 1. AdGuard Home 用户  
将以下规则添加到 **自定义过滤列表**：  
```plaintext
[https://raw.githubusercontent.com/tonydong/AdGuard-BiliCDN-Rules/adguard.txt](https://raw.githubusercontent.com/tonydongguwpi/AdGuard-BiliCDN-Rules/refs/heads/main/adguard.txt)  
