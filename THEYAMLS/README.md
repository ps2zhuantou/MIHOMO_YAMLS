# 📦 mihomo_yamls

> 🔄 **自动同步的 Mihomo (Clash.Meta) 配置文件仓库**  
> 通过 GitHub Actions 每日同步上游配置，并生成技术分析文档与 OpenClash 覆写配置。

> [!NOTE]
> 本文件已根据最新目录清单及 `fetch` 脚本中的实际抓取源重新整理，绝大部分来源已核实。仅剩 2 处来源仍无法确认（见下方 ⚠️ 标注），其余抓取脚本中未出现的条目已据此补全真实仓库地址。

---

## 📂 快速导航

| 分类 | 说明 | 配置数量 | 文档 |
| :--- | :--- | :--- | :--- |
| **通用进阶配置** | 适合 PC、Mac 及普通手机端 | 68 个（31 个来源） | [查看](General_Config/README.md) |
| **Smart 模式 / 路由专用** | 需配合 Smart 魔改内核使用 | 至少 12 个（6 个来源，均已核实；目录清单末尾曾被截断，实际文件数可能更多） | [查看](Smart_Mode/README.md) |
| **Android 模块专用** | 适合已 Root 的 Android 设备 | 4 个 | [查看](Mobile_Modules/README.md) |
| **Mihomo 官方示例** | 纯净基础，适合学习 | 2 个 | [查看](Official_Examples/README.md) |

---

### ⚙ 通用进阶配置 (General Config)

> 适合 PC、Mac 及普通手机端使用的全功能配置。

| 👤 作者 | 📦 配置清单 | 📝 描述 | 🔗 溯源 |
| :--- | :--- | :--- | :--- |
| **CRules** | 📄 [`AIB.yaml`](General_Config/JohnsonRan/AIB.yaml)<br>📄 [`AIO.yaml`](General_Config/JohnsonRan/AIO.yaml) | 社区精选配置 | [CRules](https://github.com/JohnsonRan/CRules) |
| **MIHOMO_AIO** | 📄 [`MihomoAIO.yaml`](General_Config/HenryChiao/MihomoAIO.yaml)<br>📄 [`MihomoProMax.yaml`](General_Config/HenryChiao/MihomoProMax.yaml)<br>📄 [`MihomoProPlus.yaml`](General_Config/HenryChiao/MihomoProPlus.yaml) | 社区精选配置 | [MIHOMO_AIO](https://github.com/HenryChiao/MIHOMO_AIO) |
| **ProxyResource** | 📄 [`Clash_Sample.yaml`](General_Config/iKeLee/Clash_Sample.yaml)<br>⚠️ 📄 [`backup.yaml`](General_Config/iKeLee/backup.yaml) | Clash_Sample 来自下方仓库；backup.yaml 未在抓取脚本中出现，来源待确认 | [ProxyResource](https://github.com/luestr/ProxyResource) |
| **Rules** | 📄 [`configfull.yaml`](General_Config/Lanlan13-14/configfull.yaml)<br>📄 [`configfull_lite.yaml`](General_Config/Lanlan13-14/configfull_lite.yaml)<br>📄 [`configfull_NoAd.yaml`](General_Config/Lanlan13-14/configfull_NoAd.yaml) | 社区精选配置 | [Rules](https://github.com/Lanlan13-14/Rules) |
| **Self-Configuration** | 📄 [`Clash.yaml`](General_Config/ClashConnectRules/Clash.yaml) | 社区精选配置 | [Self-Configuration](https://github.com/ClashConnectRules/Self-Configuration) |
| **Share** | 📄 [`redir-host.yaml`](General_Config/Yiteei/redir-host_config.yaml)<br>📄 [`fake-ip.yaml`](General_Config/Yiteei/fake-ip_config.yaml) | 社区精选配置（来自 `Proxy` 分支） | [Share](https://github.com/yiteei/Share/tree/Proxy) |
| **YYDS** | 📄 [`MihomoPro.yaml`](General_Config/666OS/MihomoPro_Config.yaml)<br>📄 [`OneTouch.yaml`](General_Config/666OS/OneTouch_Config.yaml)<br>📄 [`Lite_en.yaml`](General_Config/666OS/Lite_en.yaml)<br>📄 [`Mini_en.yaml`](General_Config/666OS/Mini_en.yaml)<br>📄 [`Pro_en.yaml`](General_Config/666OS/Pro_en.yaml) | 社区精选配置（新增 3 个英文版变体） | [YYDS](https://github.com/666OS/YYDS) |
| **gist** | 📄 [`config.yaml`](General_Config/liuran001/config.yaml) | 社区精选配置 | [gist](https://gist.github.com/liuran001/5ca84f7def53c70b554d3f765ff86a33) |
| **iNg** | 📄 [`ConfigForClash.yaml`](General_Config/fufu/ConfigForClash.yaml) | 社区精选配置 | [iNg](https://github.com/sunfing/iNg) |
| **little** | 📄 [`clash-all-fallback.yaml`](General_Config/liandu2024/clash-all-fallback.yaml)<br>📄 [`clash-fallback-all.yaml`](General_Config/liandu2024/clash-fallback-all.yaml)<br>📄 [`clash-fallback-dialer.yaml`](General_Config/liandu2024/clash-fallback-dialer.yaml)<br>📄 [`clash-fallback-std.yaml`](General_Config/liandu2024/clash-fallback-std.yaml)<br>📄 [`clash-fallback.yaml`](General_Config/liandu2024/clash-fallback.yaml) | 社区精选配置（fallback 系列，实际文件名已更新） | [little](https://github.com/liandu2024/little) |
| **my-backup** | 📄 [`config.yaml`](General_Config/wanswu/config.yaml) | 社区精选配置 | [my-backup](https://github.com/wanswu/my-backup) |
| **proxy** | 📄 [`mihomo.yaml`](General_Config/echs-top/mihomo.yaml) | 社区精选配置 | [proxy](https://github.com/echs-top/proxy) |
| **rule** | 📄 [`config.yaml`](General_Config/qichiyuhub/config.yaml) | 社区精选配置 | [rule](https://github.com/qichiyuhub/rule) |
| **selfproxy** | 📄 [`mihomo_single.yaml`](General_Config/yyhhyyyyyy/mihomo_single.yaml)<br>📄 [`mihomo_multi.yaml`](General_Config/yyhhyyyyyy/mihomo_multi.yaml) | 社区精选配置 | [selfproxy](https://github.com/yyhhyyyyyy/selfproxy) |
| **Kerronex**（社区投稿） | 📄 [`config.yaml`](General_Config/Kerronex/config.yaml) | 收录于 MIHOMO_AIO 仓库内的社区投稿配置 | [MIHOMO_AIO](https://github.com/HenryChiao/MIHOMO_AIO/blob/main/CONFIG/General/Kerronex_config.yaml) |
| **Mitchell**（社区投稿） | 📄 [`config.yaml`](General_Config/Mitchell/config.yaml)<br>📄 [`config_version2.yaml`](General_Config/Mitchell/config_version2.yaml) | 收录于 MIHOMO_AIO 仓库内的社区投稿配置 | [MIHOMO_AIO](https://github.com/HenryChiao/MIHOMO_AIO/blob/main/CONFIG/General/Mitchell_config.yaml) |
| **Repcz/Tool** | 📄 [`config.yaml`](General_Config/Repcz/config.yaml)<br>📄 [`config_lite.yaml`](General_Config/Repcz/config_lite.yaml) | 社区精选配置（来自 `X` 分支） | [Tool](https://github.com/Repcz/Tool/tree/X) |
| **clash** | 📄 [`mihomo.yaml`](General_Config/lvbibir/mihomo.yaml) | 社区精选配置 | [clash](https://github.com/lvbibir/clash) |
| **Yaml** | 📄 [`Seven1_fallback_Geo.yaml`](General_Config/Seven1echo/Seven1_fallback_Geo.yaml)<br>📄 [`Seven1_fallback_Rule-Set.yaml`](General_Config/Seven1echo/Seven1_fallback_Rule-Set.yaml) | 社区精选配置 | [Yaml](https://github.com/Seven1echo/Yaml) |
| **AirRules** | 📄 [`2-subscription-clash-rule-set.yaml`](General_Config/Pililink/2-subscription-clash-rule-set.yaml)<br>📄 [`3-subscription-clash-rule-set.yaml`](General_Config/Pililink/3-subscription-clash-rule-set.yaml)<br>📄 [`base-clash-ruleset.yaml`](General_Config/Pililink/base-clash-ruleset.yaml) | 社区精选配置 | [AirRules](https://github.com/Pililink/AirRules) |
| ⚠️ **SHICHUNHUI88** | 📄 [`Clash-Airport.yaml`](General_Config/SHICHUNHUI88/Clash-Airport.yaml)<br>📄 [`us_la.yaml`](General_Config/SHICHUNHUI88/us_la.yaml) | 两份 fetch 脚本均未出现该来源，仓库地址仍待确认 | [SHICHUNHUI88](https://github.com/SHICHUNHUI88) |
| **ClashMi**（gist）⚠️ | 📄 [`Clashmi.yaml`](General_Config/bgpeer/Clashmi.yaml) | 通过加速代理拉取的匿名 gist，原作者未知 | [代理链接](https://gh.669588.xyz/gist/01f635bc410f3503a218e03e537cb135/raw/ClashMi.yaml) |
| **ClashMi-fx**（gist） | 📄 [`Clashmi-fx.yaml`](General_Config/bgpeer/Clashmi-fx.yaml) | 社区精选配置 | [gist/bgpeer](https://gist.github.com/bgpeer/cfd6fcf7bc40c166984b87ecf4fbf920) |
| **MyClash** | 📄 [`mihomoConfigLite.yaml`](General_Config/AIsouler/mihomoConfigLite.yaml)<br>📄 [`mihomoconfig.yaml`](General_Config/AIsouler/mihomoconfig.yaml) | 社区精选配置 | [MyClash](https://github.com/AIsouler/MyClash) |
| **mihomo_rules** | 📄 [`mihomo.yaml`](General_Config/loneshu7/mihomo.yaml) | 社区精选配置 | [mihomo_rules](https://github.com/loneshu7/mihomo_rules) |
| **Ayanami0-configs** | 📄 [`Ayanami0_config.yaml`](General_Config/Ayanami0-configs/Ayanami0_config.yaml)<br>📄 [`Ayanami0_config_full.yaml`](General_Config/Ayanami0-configs/Ayanami0_config_full.yaml)<br>📄 [`Ayanami0_config_geo-lite.yaml`](General_Config/Ayanami0-configs/Ayanami0_config_geo-lite.yaml) | 社区精选配置（仓库所有者为 Ayanami0xL1l1th） | [Ayanami0-configs](https://github.com/Ayanami0xL1l1th/Ayanami0-configs) |
| **Proxy-override** | 📄 [`Proxy-override.yaml`](General_Config/Sgraqwq/Proxy-override.yaml) | 社区精选配置 | [Proxy-override](https://github.com/Sgraqwq/Proxy-override) |
| **Clash_Configuration_Template** | 📄 BlackList 系列 ×3<br>📄 [Desktop]-WhiteList 系列 ×3<br>📄 [Mobile]-WhiteList 系列 ×3<br>📄 [通用模版]-WhiteList 系列 ×3（共 12 个，含超大号规则文件，最大约 2 MB） | 黑白名单规则合集 | [Clash_Configuration_Template](https://github.com/Accademia/Clash_Configuration_Template) |
| **mihomo_rules_profile** | 📄 [`mihomo.yaml`](General_Config/Tangerinell/mihomo.yaml) | 社区精选配置（来自 `master` 分支） | [mihomo_rules_profile](https://github.com/Tangerinell/mihomo_rules_profile) |
| **rules** | 📄 [`mihomo.yaml`](General_Config/YiXuanZX/mihomo.yaml) | 社区精选配置 | [rules](https://github.com/YiXuanZX/rules) |
| **mihomo-config-self** | 📄 [`mihomo.yaml`](General_Config/XVSVTSAMA/mihomo.yaml) | 社区精选配置（仓库所有者用户名为 XVSVTsama） | [mihomo-config-self](https://github.com/XVSVTsama/mihomo-config-self) |
| **Clash-Rule** | 📄 [`mihomo.yaml`](General_Config/ameyukisora/mihomo.yaml) | 社区精选配置（来自 `master` 分支） | [Clash-Rule](https://github.com/ameyukisora/Clash-Rule) |

[🔙 返回顶部](#-mihomo_yamls)

---

### 🧠 Smart 模式 / 路由专用 (Smart Mode)

> 专为 Smart 核心、OpenClash 或软路由环境优化。

| 👤 作者 | 📦 配置清单 | 📝 描述 | 🔗 溯源 |
| :--- | :--- | :--- | :--- |
| **MIHOMO_AIO** | 📄 [`MihomoSmartAIO.yaml`](Smart_Mode/HenryChiao/MihomoSmartAIO.yaml)<br>📄 [`MihomoSmartProMax.yaml`](Smart_Mode/HenryChiao/MihomoSmartProMax.yaml)<br>📄 [`MihomoSmartProPlus.yaml`](Smart_Mode/HenryChiao/MihomoSmartProPlus.yaml)<br>📄 [`THESmart.yaml`](Smart_Mode/HenryChiao/THESmart.yaml) | 社区精选配置；THESmart.yaml 实际取自 `CONFIG/Test_Final/mihomo-final-v6.yaml` | [MIHOMO_AIO](https://github.com/HenryChiao/MIHOMO_AIO) |
| **YYDS** | 📄 [`OneSmart_Config.yaml`](Smart_Mode/666OS/OneSmart_Config.yaml)<br>📄 [`OneSmart_Lite_Config.yaml`](Smart_Mode/666OS/OneSmart_Lite_Config.yaml) | 社区精选配置（源文件分别为 legacy/OneSmartPro.yaml、legacy/OneSmart.yaml） | [YYDS](https://github.com/666OS/YYDS) |
| **little** | 📄 [`clash-all-fallback-smart.yaml`](Smart_Mode/liandu2024/clash-all-fallback-smart.yaml)<br>📄 [`clash-all-smart.yaml`](Smart_Mode/liandu2024/clash-all-smart.yaml)<br>📄 [`clash-fallback-smart-std.yaml`](Smart_Mode/liandu2024/clash-fallback-smart-std.yaml) | 社区精选配置 | [little](https://github.com/liandu2024/little) |
| **proxy** | 📄 [`mihomo_smart.yaml`](Smart_Mode/echs-top/mihomo_smart.yaml) | 社区精选配置 | [proxy](https://github.com/echs-top/proxy) |
| **rule** | 📄 [`smart.yaml`](Smart_Mode/qichiyuhub/smart.yaml) | 社区精选配置 | [rule](https://github.com/qichiyuhub/rule) |
| **MIHOMO_YAMLS**（同名分支项目） | 📄 [`OneSmartProMCX.yaml`](Smart_Mode/edison/OneSmartProMCX.yaml) | 社区精选配置，来自用户 EdisonLe12 维护的同名分支仓库 | [MIHOMO_YAMLS](https://github.com/EdisonLe12/MIHOMO_YAMLS) |

[🔙 返回顶部](#-mihomo_yamls)

---

### 📱 Android 模块专用 (Mobile Modules)

> 适合 Magisk / KernelSU / APatch 用户。

| 👤 作者 | 📦 配置清单 | 📝 描述 | 🔗 溯源 |
| :--- | :--- | :--- | :--- |
| **Clash-MIX** | 📄 [`config.yaml`](Mobile_Modules/ClashMix/config.yaml) | 社区精选配置 | [Clash-MIX](https://github.com/AXEVO/Clash-MIX) |
| **Surfing** | 📄 [`config.yaml`](Mobile_Modules/Surfing/config.yaml) | 社区精选配置 | [Surfing](https://github.com/GitMetaio/Surfing) |
| **akashaProxy** | 📄 [`config.yaml`](Mobile_Modules/AkashaProxy/config.yaml) | 完整国家/地区分组 | [akashaProxy](https://github.com/akashaProxy/akashaProxy) |
| **box** | 📄 [`config.yaml`](Mobile_Modules/BoxProxy/config.yaml) | 社区精选配置 | [box](https://github.com/boxproxy/box) |

[🔙 返回顶部](#-mihomo_yamls)

---

### 📘 Mihomo 官方 Wiki 示例 (Official)

> 最纯净、最基础的学习模板。

| 👤 来源 | 📦 配置清单 | 🔗 溯源 |
| :--- | :--- | :--- |
| **Metacubex Wiki** | 📄 [`mrs`](Official_Examples/Metacubex/rule-set_config.yaml)<br>📄 [`geox`](Official_Examples/Metacubex/geox_config.yaml) | [官方 Wiki](https://wiki.metacubex.one/example/mrs) |

[🔙 返回顶部](#-mihomo_yamls)

<!-- AUTO_GENERATED_START -->
<!-- 这里会自动插入配置列表 -->
<!-- AUTO_GENERATED_END -->
