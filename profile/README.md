<p align="center">
  <img src="https://raw.githubusercontent.com/justmysocks-guide/.github/main/assets/logo.png" width="120" height="120" alt="Just My Socks Guide Logo" />
</p>

# Just My Socks 教程（2026最新全场景指南）：官方优惠码、机房选型对比与全平台客户端订阅配置手册
**中文完整指南** | 🌐 [English Version / Promo Codes](./README_EN.md)


> 💡 **核心定位**：搬瓦工官方（BandwagonHost / IT7 Networks）旗下运营的高端企业级网络加速与代理托管服务。三网直连 CN2 GIA / 软银 / 香港 IPLC 高速优化线路，**智能监控 IP 状态，被墙自动秒级切换可用 IP，彻底告别自建 VPS 频繁封锁烦恼**。

> 🛠 **开源配套工具生态**：
> - 📖 **[justmysocks](https://github.com/justmysocks-guide/justmysocks)**：2026 最新官方购买指南与全场景知识库（[在线网页版](https://justmysocks-guide.github.io/justmysocks/)）
> - ⚡️ **[jms-speedtest](https://github.com/justmysocks-guide/jms-speedtest)**：JMS 全球机房延迟实测、三网丢包率体检与 ChatGPT / Claude / Gemini 原生 IP 解锁一键脚本
> - 🎯 **[clash-rules](https://github.com/justmysocks-guide/clash-rules)**：专为 Just My Socks 与海外 AI 优化的高性能 Clash Verge Rev / Sing-box 分流规则包

---

## 📌 快速导航与文章目录

- [一、先搞清楚：Just My Socks 到底是什么？跟自建 VPS 比好在哪？](#一先搞清楚just-my-socks-到底是什么跟自建-vps-比好在哪)
  - [1. 搬瓦工官方直营背书](#1-搬瓦工官方直营背书)
  - [2. 为什么它比自己折腾 VPS 更省心？](#2-为什么它比自己折腾-vps-更省心)
  - [3. 深度评测：Just My Socks 到底怎么样？好用吗？为什么有人说它贵或不稳定？](#3-深度评测just-my-socks-到底怎么样好用吗为什么有人说它贵或不稳定)
- [二、2026 官方最新优惠码（永久循环折扣 5.2%）](#二2026-官方最新优惠码永久循环折扣-52)
- [三、全机房核心套餐横向选型对比表（怎么选最划算？）](#三全机房核心套餐横向选型对比表怎么选最划算)
- [四、手把手购买与结算流程（支持支付宝）](#四手把手购买与结算流程支持支付宝)
- [五、全平台现代客户端一键订阅与配置实战（2026最新）](#五全平台现代客户端一键订阅与配置实战2026最新)
  - [1. Windows & macOS：Clash Verge Rev 最佳现代配置](#1-windows--macosclash-verge-rev-最佳现代配置)
  - [2. iOS（苹果手机/平板）：Shadowrocket（小火箭）扫码导入](#2-ios苹果手机平板shadowrocket小火箭扫码导入)
  - [3. Android（安卓系统）：Sing-box 与 Clash Meta 指南](#3-android安卓系统sing-box-与-clash-meta-指南)
  - [4. 软路由与家庭网关：OpenWrt / OpenClash / PassWall 配置实战](#4-软路由与家庭网关openwrt--openclash--passwall-配置实战)
  - [5. 进阶：Just My Socks 订阅转换与 Clash 格式导出防泄露](#5-进阶just-my-socks-订阅转换与-clash-格式导出防泄露)
- [六、海外 AI（ChatGPT / Claude）与流媒体分流防封实战](#六海外-aichatgpt--claude与流媒体分流防封实战)
- [七、高频疑难排查与退款售后政策（FAQ）](#七高频疑难排查与退款售后政策faq)

---

## 一、先搞清楚：Just My Socks 到底是什么？跟自建 VPS 比好在哪？

很多第一次出海、跨境或需要海外学术科研的朋友，都会在**“自己买云服务器自建”**与**“买托管节点（机场）”**之间纠结。

### 1. 搬瓦工官方直营背书
Just My Socks（业内简称 **JMS**）不是小作坊个人搭建的影子服务，而是由加拿大老牌知名 VPS 厂商 **IT7 Networks（即搬瓦工 BandwagonHost 母公司）** 于 2018 年底正式推出的官方网络加速产品。

### 2. 为什么它比自己折腾 VPS 更省心？
| 对比维度 | 个人自己买 VPS 搭建 | Just My Socks 官方托管服务 |
| :--- | :--- | :--- |
| **IP 被墙风险** | **极高**。一旦 IP 进黑名单，换 IP 需额外花费 $8~$15 美元，折腾且费钱。 | **零风险**。后台 7×24 自动探活，**IP 一旦受阻，系统自动秒级分配全新可用 IP**，全程无感。 |
| **线路质量** | 普通入门 VPS 晚高峰丢包率高达 30%~50%，CN2 GIA 线路机器动辄年付上百刀。 | **标配 CN2 GIA / 日本软银顶级线路**，直通中国电信、联通、移动骨干网，晚高峰不卡顿。 |
| **技术门槛** | 需熟悉 Linux 命令行、SSH 证书、防火墙规则、防探测加密，维护成本高。 | **零技术门槛**。购买后直接提供通用订阅 URL，复制进客户端即开即用。 |
| **协议安全性** | 容易因配置漏洞被主动探测阻断。 | 官方运维团队统一持续更新 V2Ray / Shadowsocks / Obfs 混淆协议，抗封锁能力强。 |

### 3. 深度评测：Just My Socks 到底怎么样？好用吗？为什么有人说它贵或不稳定？

针对刚接触或正在挑选的用户最关心的几个高频疑问，做一次客观、真实的深度评测：

- **Q1：为什么有人觉得 Just My Socks 比市面上的小机场贵？**  
  **答**：普通机场普遍严重超售，采用随时可能跑路的个人黑卡合租或廉价专线；而 Just My Socks 是搬瓦工官方运营的正规企业级产品，**不限速、不超售、每台服务器标配真 CN2 GIA / 软银物理千兆大带宽，并承担 IP 被墙的无限次免费换新成本**。算上省下的换 IP 费用与折腾时间成本，综合性价比极高。
- **Q2：为什么有人反映“速度慢”或“偶尔不稳定”？如何彻底解决？**  
  **答**：**90% 觉得不稳定的用户，都是因为误用了默认的 `s1` 或 `s2` 普通骨干线路！**  
  JMS 每个套餐分配 5 条独立路由线路：
  - `s1`、`s2`：普通国际骨干线路，晚高峰容易受电信国际出口拥堵影响；
  - `s3`、`s4`：**中国电信 CN2 GIA / 联通 9929 顶级双程直连优化专线**；
  - `s5`：移动 CMI 高速直连线路。  
  👉 **只要在客户端中把节点手动切换为 `s3` 或 `s4`（或设置 URL-Test 自动测速切换），丢包率立即降为 0%，4K 视频秒开，彻底告别不稳定！**
- **Q3：它适合做海外业务、TikTok 运营、跨境电商与学术科研吗？**  
  **答**：非常适合。搬瓦工母公司自有的机房 IP 纯净度高，没有普通共享机场那种滥用黑名单记录，访问 Google Scholar、ChatGPT、Claude、Stripe 均极其稳定，不轻易弹验证码。

---

## 二、2026 官方最新优惠码（永久循环折扣 5.2%）

Just My Socks 官方提供长期有效的循环减免优惠券，**该优惠码在首次购买、未来每次月付或年付续费时，均自动享受终身 5.2% 减免**。

| 官方最新专属优惠码 | 折扣力度 | 适用范围 | 使用说明 |
| :---: | :---: | :---: | :--- |
| `JMS9272283` | **5.2% 永久折扣** | 全场所有套餐方案通用 | 结算页填入并点击 `Validate Code` 生效 |

> 📌 **省钱技巧**：选择 **年付（Annual）** 本身享有“买 10 个月送 2 个月”的折上折优惠，再叠加优惠码 `JMS9272283`，综合折扣低至 **8 折左右**，性价比最高。

---

## 三、全机房核心套餐横向选型对比表（怎么选最划算？）

Just My Socks 目前在全球布局了洛杉矶（LA）、东京（Tokyo）、香港（Hong Kong）、伦敦（London）等多个核心节点。每个套餐均配备 **5 条独立路由线路**，可随时自由切换。

| 方案名称 | 核心线路优势 | 带宽 | 每月流量 | 限制设备数 | 官方标价 | 选型与适用场景推荐 | 购买直达入口 |
| :--- | :--- | :---: | :---: | :---: | :---: | :--- | :---: |
| **JMS LA 500**<br>*(爆款明星)* | 洛杉矶 CN2 GIA / 联通 9929<br>移动 CMI 三网直连 | **2.5 Gbps** | 500 GB | 5 台 | $5.88 / 月<br>$58.88 / 年 | **【最推荐入门首选】**<br>性价比之王，三网优化极佳，畅刷 4K 视频，适合个人与小微工作室。 | [👉 立即选购](https://justmysocks.net/members/aff.php?aff=24082&pid=2) |
| **JMS LA 1000** | 洛杉矶 CN2 GIA 高速冗余 | **5 Gbps** | 1000 GB | 无限制 | $9.88 / 月<br>$98.88 / 年 | **【高带宽多设备首选】**<br>大流量重度用户、跨境团队多人共享办公无压力。 | [👉 立即选购](https://justmysocks.net/members/aff.php?aff=24082&pid=3) |
| **JMS Tokyo 100** | 日本东京优质软银专线<br>极低物理延迟 (40~70ms) | **100 Mbps** | 100 GB | 3 台 | $29.99 / 月<br>$299.99 / 年 | **【游戏与低延迟敏感型】**<br>华东/沿海地区极速体验，外贸实时沟通、外服游戏推荐。 | [👉 立即选购](https://justmysocks.net/members/aff.php?aff=24082&pid=4) |
| **JMS Tokyo 500** | 日本软银优质大带宽 | **200 Mbps** | 500 GB | 5 台 | $34.99 / 月<br>$349.99 / 年 | **【日本节点重度商业户】**<br>大流量兼顾低延迟首选。 | [👉 立即选购](https://justmysocks.net/members/aff.php?aff=24082&pid=5) |
| **JMS HK 100** | 香港优质 GIA / IPLC 极速直连<br>全国延迟 20~40ms | **100 Mbps** | 100 GB | 3 台 | $34.50 / 月<br>$345.00 / 年 | **【高端企业商务专线】**<br>媲美内地专线的极致低延迟体验，商务应急首选。 | [👉 立即选购](https://justmysocks.net/members/aff.php?aff=24082&pid=6) |
| **JMS London 500** | 欧洲伦敦移动 CMI 优质线路 | **2.5 Gbps** | 500 GB | 5 台 | $5.88 / 月<br>$58.88 / 年 | **【欧洲业务专属】**<br>适合专门从事英国/欧洲跨境电商合规运营、欧洲业务爬虫等。 | [👉 立即选购](https://justmysocks.net/members/aff.php?aff=24082&pid=7) |

---

## 四、手把手购买与结算流程（支持支付宝）

### 第一步：挑选心仪套餐
进入上方对比表格中的直达入口，选择计费周期（建议按年付结算，省下 2 个月月租）。

### 第二步：应用优惠码省钱
在购物车订单界面（Order Summary）中找到 `Promotional Code` 输入框，填入：
```text
JMS9272283
```
点击 **Validate Code** 按钮，系统会提示折扣生效，订单总额即刻减少 5.2%。随后点击 **Checkout** 进入结账页。

### 第三步：填写基础注册信息
- **Email Address**：建议填写常用国外邮箱或 QQ/163 邮箱（用于接收账单与订阅通知）；
- **Password**：设置后台管理密码；
- **Payment Method**：选择 **Alipay（支付宝）** 或 **UnionPay（银联）**，支持国内手机扫码直接人民币支付。

### 第四步：获取专属订阅链接
支付成功后，登录 Just My Socks 用户后台：
1. 点击顶部导航栏的 **Services（我的服务）** -> 选择刚购买的产品；
2. 进入服务详情页（Service Details），页面向下滚动可以看到：
   - **Subscription URL**（通用订阅链接，最推荐方式）；
   - **二维码与单节点参数**（包含服务器域名、端口、加密方式、UUID 密钥）。

---

## 五、全平台现代客户端一键订阅与配置实战（2026最新）

> ⚠️ **老旧教程避坑提示**：网上很多旧教程仍在使用早期的单节点扫码或已停止维护的老版 Shadowsocks / V2RayN 客户端，容易遇到协议报错。**强烈推荐使用以下支持自动分流、智能测速与核心保活的现代化客户端**：

### 1. Windows & macOS：Clash Verge Rev 最佳现代配置
Clash Verge Rev 是当前主流跨平台桌面客户端，原生集成开源 Mihomo 核心，界面现代化且支持全局规则分流。

1. **下载安装**：前往 [Clash Verge Rev 官方开源仓库](https://github.com/clash-verge-rev/clash-verge-rev) 下载适配你操作系统的安装包。
2. **导入订阅**：
   - 打开 Clash Verge Rev -> 点击左侧 **订阅（Profiles）**；
   - 在顶部输入框粘贴在 JMS 后台复制的 **Subscription URL**，点击 **下载（Import）**；
   - 订阅下载完成后，点击右键激活该配置（变为高亮选中状态）。
3. **开启代理**：
   - 点击左侧 **代理（Proxies）**，选择 **Rule（规则分流）** 模式；
   - 选择延迟最低的一条线路（如 `s3` 或 `s4` CN2 GIA 直连路线）；
   - 切换到 **设置（Settings）** -> 打开 **系统代理（System Proxy）** 开关，即可畅通访问全球网络！

### 2. iOS（苹果手机/平板）：Shadowrocket（小火箭）扫码导入
1. 在非国区 App Store 登录并下载安装 **Shadowrocket**。
2. 打开 Shadowrocket，点击右上角 `+` 号：
   - **类型** 选择 `Subscribe` 或直接点击左上角扫描按钮，扫描 JMS 后台的订阅二维码；
   - 备注填写 `JustMySocks`，点击保存。
3. 客户端会自动拉取 5 条优质线路，首页全局路由建议设为 **配置（Config）**（实现国内直连、海外加速的自动分流）。
4. 打开顶部主连接开关，首次使用允许安装 VPN 描述文件即可。

### 3. Android（安卓系统）：Sing-box 与 Clash Meta 指南
- **推荐客户端**：**Clash Meta for Android** 或 **Sing-box Android**。
- **配置步骤**：打开软件 -> 点击“配置” -> 添加 URL 订阅 -> 粘贴订阅链接并保存更新 -> 在代理组选择自动测试（URL-Test）选择最低延迟节点启动。

### 4. 软路由与家庭网关：OpenWrt / OpenClash / PassWall 配置实战
对于软路由（N1、x86、NanoPi 等）用户：
1. **OpenClash**：
   - 进入 OpenWrt 后台 -> `服务` -> `OpenClash` -> `配置文件订阅`；
   - 填入 JMS 后台提供的 **Clash Profile 链接**，在线订阅转换建议选择关闭（推荐使用官方原生格式）；
   - 保存并更新配置，启动 OpenClash 即可实现全屋设备自动无感分流。
2. **PassWall / SSR-Plus**：
   - 支持将 JMS 通用节点参数通过 V2Ray/Shadowsocks 订阅一键导入，搭配 ChinaDNS-NG 实现防 DNS 污染与低延迟直连。

### 5. 进阶：Just My Socks 订阅转换与 Clash 格式导出防泄露
很多新手在搜索 `justmysocks 订阅转换` 时，会去使用不可信的公开在线订阅转换工具，这是导致节点密钥泄露的最大元凶！
- **官方原生支持**：JMS 官方后台现已原生支持多种格式。登录后台 `Service Details`，在订阅地址下拉菜单直接切换为 **Clash** 或 **Surge** 格式，直接复制专属链接即可，**无需经过任何第三方第三方转换服务，从根源规避节点泄露风险**。

---

## 六、海外 AI（ChatGPT / Claude）与流媒体分流防封实战

使用外网节点访问海外 AI 服务时，常因节点 IP 污染遭遇 `Access Denied` 或账户封禁。Just My Socks 在 IP 纯净度上具有天然优势：

1. **AI 服务适配表现**：
   - **ChatGPT (OpenAI)**：推荐使用 **LA（洛杉矶）的 s3、s4 线路** 或 **Tokyo 线路**，原生解锁，对话响应迅速，不报 403 错误。
   - **Claude (Anthropic)**：Anthropic 对数据中心 IP 审查极严。建议在 Clash 策略组中单独将 `anthropic.com` 与 `claude.ai` 域名绑定到 **JMS 英国伦敦（London）** 或 **美国原生机房** 线路，实测稳定性优异。
2. **分流防封规则设置**：
   - 在客户端内务必开启 **规则分流（Rule Mode）**，严禁使用“全局代理（Global Mode）”同时访问国内常用软件和海外敏感金融/社交平台，避免因频繁跨国 IP 漂移被判定异地异常。
   - 搭配本组织维护的专用规则集：[clash-rules](https://github.com/justmysocks-guide/clash-rules)。

---

## 七、高频疑难排查与退款售后政策（FAQ）

### Q1：如果 IP 被封了，我需要自己手动联系客服吗？
**答：完全不需要！**  
这是 Just My Socks 最核心的技术壁垒。后台自动化巡检引擎以秒级频率检测全网连通性。一旦某条线路被墙，后台系统会在数分钟内自动完成新 IP 解析分配。**对于使用订阅链接的用户，客户端每隔几个小时自动拉取一次，或者手动点击“刷新订阅”，新 IP 就会无缝更新到你的设备中。**

### Q2：给的 5 条线路（c1s1~c1s5）有什么区别？哪条速度最快？
JMS 洛杉矶方案通常包含 5 条不同路由的线路配置：
- **s1、s2**：普通骨干大带宽线路，适合大文件下载；
- **s3**：中国电信 CN2 GIA 直连加速优化线路；
- **s4**：中国电信 CN2 GIA + 联通 9929 顶级优质双程直连；
- **s5**：移动 CMI 高速直连（部分方案支持 UDP / 游戏加速）。  
👉 **日常使用推荐优先选择 s3 或 s4 线路，晚高峰稳定性极佳。**

### Q3：购买后如果不满意，怎么申请全额退款？
Just My Socks 支持严格且透明的 **3 天内全额退款政策**：
- **退款条件**：
  1. 账号注册在 3 天之内；
  2. 方案使用流量不超过总额度的 10%；
  3. 历史未发生过恶意争议或退款滥用。
- **退款申请步骤**：登录后台 -> 点击左侧菜单 **Billing（账单服务）** -> 选择该账单 -> 提交工单（Support Ticket）选择 Request Refund，系统审核符合条件后款项将原路退回至支付宝/付款账户。

### Q4：Just My Socks 支持多设备同时使用吗？可以和朋友拼车合租吗？
**答：完全支持！**  
各套餐均明确标注了同时在线设备上限（例如最热销的 JMS LA 500 套餐支持 **5 台设备同时在线**，JMS LA 1000 套餐**不限制设备数**）。只要同时发起连接的设备数不超出套餐限制，你可以在自己的电脑、手机、平板同时使用，或者与信任的朋友合租拼车，平摊后每月仅需几元钱。

### Q5：到期如何续费？优惠码在续费时还能享受 5.2% 折扣吗？
**答：终身有效，自动扣减！**  
使用专属优惠码 `JMS9272283` 购买后，该折扣会自动绑定至你的产品服务周期中。无论是按月续费还是按年续费，系统生成的续费账单（Invoice）都会**自动永久立减 5.2%**，不需要每次手动重复输入。

### Q6：如何测试当前节点到国内的实际延迟、丢包率与 AI 解锁情况？
**答：使用组织开源的一键测速诊断工具**  
我们在 GitHub 组织下维护了轻量级开源诊断工具 [jms-speedtest](https://github.com/justmysocks-guide/jms-speedtest)，只需在终端运行一行命令：
```bash
curl -sSL https://raw.githubusercontent.com/justmysocks-guide/jms-speedtest/main/check.sh | bash
```
即可自动测试当前网络到洛杉矶 CN2 GIA、东京软银、香港 IPLC 的握手延迟，并一键体检 ChatGPT、Claude 原生 IP 解锁状态。

---

### 💬 官方置顶精选技术问答（FAQ Issues）

- 📌 **[Issue #1: 2026 最新专属优惠码是多少？如何在购买与续费时享受 5.2% 永久循环折扣？](https://github.com/justmysocks-guide/.github/issues/1)**
- 📌 **[Issue #2: 觉得偶尔速度慢或不稳定？为什么必须切换到 s3 / s4 (CN2 GIA / 9929) 优化线路？](https://github.com/justmysocks-guide/.github/issues/2)**
- 📌 **[Issue #3: 访问 ChatGPT / Claude 报错 403 Access Denied 怎么办？机房选型与分流防封配置详解](https://github.com/justmysocks-guide/.github/issues/3)**

---

## 📢 总结与快速通道

对于不愿把时间耗费在写脚本、防封锁、换 IP 的个人开发者、科研人员和跨境从业者而言，Just My Socks 凭借 **搬瓦工大厂背书 + 自动秒切 IP + 顶级 CN2 GIA 线路**，依然是目前最省心、高可用的出海基础设施之一。

👉 **[点击前往 Just My Socks 官方安全镜像通道选购](https://justmysocks.net/members/aff.php?aff=24082)**  
*(结账记得输入永久折扣码：`JMS9272283`)*  
👉 **[查看完整 2026 选型与配置指南（GitHub 仓库）](https://github.com/justmysocks-guide/justmysocks)** | **[网页版直达](https://justmysocks-guide.github.io/justmysocks/)**

---
*声明：本指南仅供跨国学术研究、跨境软件开发与合规外贸业务使用，请自觉遵守当地网络法律法规。*
