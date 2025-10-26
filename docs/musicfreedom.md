# 创作自由：音乐
#### 更新日期：2025.10.26
#### <center>事先声明：Linux环境不支持Wine+加密狗，如果软件要求iLOK等方式激活，请选择绕行</center>
#### <center>本站尽量不提供破解版本的测试，部分软件如果提供了破解版本的测试也不会提供下载链接，</center>
#### <center>来自yabridge issue内的提醒，Arch建议使用，5.1.1-1+Wine-Staging 9.21</center>
#### <center>部分插件冻结请安装DXVK和VKD3D</center>
#### <center>如果出现插件转译报错：Low memory locking limit detected（检测到低内存锁定限制），请安装realtime-privileges包，并将自己用户加入realtime实时组，并重新登录</center>

## 图例

OS：Open Source（开源） // NOS：Non-Open Source / Proprietary（专有） // P：Paid（收费） // F：Free（免费）<br>
⭕：需要解决方案 // ✅：可用 // ❌：不可用 // 🔧：需要测试<br>
Native：原生软件 // NC：Need Compliant需要兼容层<br>

| 软件名称 | 软件类型 | 是否可用 | 备注 |
| :-----: | :-----: | :-----: | :-----: |
| Sample 1 | NOS-P（非开源，收费软件） | NC✅ |  |
| Sample 2 | OOS-FP（开源，免费软件、有收费版） | ❌ | |

## DAW

#### 仅 Linux 客户端

| 软件名称 | 软件类型 | 是否可用 | 备注 |
| :-----: | :-----: | :-----: | :-----: |
| Zyrthm | OSS-FP | Native✅ | 自行编译/AUR GIT版本（免费）/买断 **开源推荐** | 
| Ardour | OOS-FP | Native✅ | 自行编译/AUR GIT版本（免费）/捐赠下载 | 
| Audacity | OSS-F | Native✅ |  | 
| Bitwig Studio | NOS-P | Native✅ | 闭源推荐 |
| Traction Waveform | NOS-FP | Native✅ |  |
| Reaper | NOS-P | Native✅ |  |
| Studio One 7 | NOS-P | Native✅ | Fuck Fender | 

## 软音源

| 软件名称 | 软件类型 | 是否可用 | 备注 |
| :-----: | :-----: | :-----: | :-----: |
| SurgeXT | OOS-F | Native✅ |  |
| Zebralette 3 | NOS-F | Native✅ |  |
| Vital | NOS-F | Native✅ | Clap可能出现无法打开的情况 |
| Analog Lab V | NOS-FP | NC✅ | ASC可能无法下载，建议去官网下载 |
| Ample Bass P Lite 2 | NOS-F | NC✅ |  |
| Ample Guitar M Lite 2 | NOS-F | NC✅ |  |
| Ample Percussion Cloudrum Lite | NOS-F | NC✅ |  |
| Air Bassline | NOS-P | NC✅ |  |
| Bloom KSHMR | NOS-P | NC✅ |  |
| Serum 1 | NOS-P | NC✅ | 需要关闭d2d1函数库，测试版本为Crack |
| Massive | NOS-P | NC✅ |  |
| Massive X | NOS-P | ❌ | 疑似技术栈问题，正版无法正常使用库，破解1.4.1正常使用 |
| Serun 2 | NOS-P | ❌ | UI严重问题, 建议直接使用Vital |
| Kontakt 8 | NOS-FP | ❌ | 无法正常安装 |
| Kontakt 7 | NOS-FP | ❌ | (Player版本)疑似技术栈问题，正版无法正常使用库，（完整版本【破解】）正常使用）
| Spirtfire BBCSO 探索版 | NOS-F | ❌ | UI无法正常加载，会让宿主挂起 | 
| Spitfire Labs | NOS-F | ❌ | UI无法正常加载，会让宿主挂起 |
| Pneuma | NOS-F | ❌ | 会让整个系统挂起 |
| BFD Drum Player | NOS-F | ❌ | 无法正常安装 |

## 效果器

| 软件名称 | 软件类型 | 是否可用 | 备注 |
| :-----: | :-----: | :-----: | :-----: |
| Efx REFRACT | NOS-P | NC✅ |  |
| Plugin Allance Free | NOS-F | NC✅ |  |
| Raum | NOS-F | NC✅ |  |
| Analog Obsession Bundle | NOS-F | NC✅ |  |
| Baby Comeback | NOS-F | NC✅ | |
| Magic Switch | NOS-F | NC✅ | |
| Magic Dice | NOS-F | NC✅ | |
| KClip Zero | NOS-F | NC✅ | |
| Wider | NOS-F | NC✅ |  |
| Wider | NOS-F | NC✅ |  |
| theTAPE | NOS-P | NC✅ | |
| Initial Dynamic EQ | NOS-F | NC✅ |  |
| OTT | NOS-F | NC✅ |  |
| TDR Nova | NOS-F | NC✅ |  |
| Initial Clipper | NOS-F | NC✅ |  |
| Gravity Granular Reverb | NOS-F | NC✅ | UI可能存在问题 |
| GraterLight | NOS-F | NC✅ | 推荐选择OpenGL |
| LoFi-FluxLight | NOS-F | NC✅ | 推荐选择OpenGL |
| SpreadLight | NOS-F | NC✅ | 推荐选择OpenGL |
| CrispyClipLight | NOS-F | NC✅ | 推荐选择OpenGL |
| Valhalla DSP Bundle | NOS-P | NC✅ | 测试版本为Crack |
| FabFilter Bundle | NOS-P | NC✅ | 测试版为Crack，正版状态未知 |
| LFOTools | NOS-P | NC✅ | UI可能闪烁，测试来源为Crack |
| BlackRooster Audio 套件 | NOS-FP | ❌ | 无法载入到Wine插件主机 |
| LANDR Mastering | NOS-P | ❌ | 无法载入UI |
| iZotope Bundle | NOS-F | ❌ | 加密问题，正版无法正常激活 |
| Fresh Air | NOS-F | ❌ | 使用iLOK，正版无法正常激活 | 
| Heatware | NOS-F | ❌ | 使用iLOK，正版无法正常激活 | 
| Softube Saturation Knob | NOS-F | ❌ | 使用iLOK，正版无法正常激活 | 

## 厂商管理工具

| 软件名称 | 软件类型 | 是否可用 | 备注 |
| :-----: | :-----: | :-----: | :-----: |
| Native Access | NOS | ❌ | 仅限经典版本，无法正常挂载，新版NodeJS可能无法打开且安装库困难 |
| Spitfire | NOS | ❌ | Labs和喷火无法正常使用，能用管理工具是何意味 |
| iZotope | NOS | ❌ | 无法正常激活 | 
| Softube | NOS | ❌ | 绑定iLok |
| UAD | NOS | ❌ | 绑定iLok |
