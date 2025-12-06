# 创作自由：音乐
#### 更新日期：2025.12.07

## 注意事项

#### <center>事先声明：Linux环境不支持Wine+加密狗，如果软件要求iLOK等方式激活，请选择绕行</center>
#### <center>本站尽量不提供破解版本的测试，部分软件如果提供了破解版本的测试也不会提供下载链接，</center>
#### <center>来自yabridge issue内的提醒，Arch建议使用，5.1.1-1+Wine-Staging 9.21</center>
#### <center>部分插件冻结请安装DXVK和VKD3D</center>
#### <center>如果出现插件转译报错：Low memory locking limit detected（检测到低内存锁定限制）</center>
#### <center>请安装realtime-privileges(Arch)/realtime-setup(RHEL)/rtkit（SUSE）包，并将自己用户加入realtime/rtkit（并启动rtkit守护程序）实时组，并重新登录</center>

## 图例

OSS：Open Source（开源） // NOS：Non-Open Source / Proprietary（专有） // P：Paid（收费） // F：Free（免费）<br>
⭕：需要解决方案 // ✅：可用 // ❌：不可用 // 🔧：需要测试<br>
Native：原生软件 // NC：Need Compliant需要兼容层<br>

## DAW

#### 仅 Linux 客户端

| 软件名称 | 软件类型 | 是否可用 | 备注 | 使用兼容层 |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| Zyrthm | OSS-FP | Native✅ | 自行编译/AUR GIT版本（免费）/买断  |  |
| Ardour | OSS-FP | Native✅ | 自行编译/AUR GIT版本（免费）/捐赠下载 | |
| Audacity | OSS-F | Native✅ |  | |
| Bitwig Studio | NOS-P | Native✅ | 闭源推荐 | |
| Traction Waveform | NOS-FP | Native✅ |  | |
| Reaper | NOS-P | Native✅ |  | |
| Studio One 7 | NOS-P | Native✅ | Fuck Fender | |

## 软音源

| 软件名称 | 软件类型 | 是否可用 | 备注 | 使用兼容层 |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| SurgeXT | OSS-F | Native✅ |  |  | 
| Zebralette 3 | NOS-F | Native✅ |  |
| Vital | NOS-F | Native✅ | Clap可能出现无法打开的情况 | |
| Analog Lab V | NOS-FP | NC✅ | ASC可能无法下载，建议去官网下载 | Wine 10.19 + Yabridge Wine 10分支 |
| Ample Bass P Lite 2 | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Ample Guitar M Lite 2 | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Ample Percussion Cloudrum Lite | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Air Bassline | NOS-P | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Bloom KSHMR | NOS-P | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Serum 1 | NOS-P | NC✅ | 需要关闭d2d1函数库，测试版本为Crack | Wine 9.21 + Yabridge 主线 |
| Massive | NOS-P | NC✅ |  | Wine 9.21 + Yabridge 主线 |
| Massive X | NOS-P | ❌ | 疑似技术栈问题，正版无法正常使用库，破解1.4.1正常使用 | Wine 9.21 + Yabridge 主线 |
| Serun 2 | NOS-P | ❌ | UI严重问题, 建议直接使用Vital |
| Kontakt 8 | NOS-FP | ❌ | 无法正常安装 | Wine 10.19 + Yabridge Wine 10分支 |
| Kontakt 7 | NOS-FP | ❌ | (Player版本)疑似技术栈问题，正版无法正常使用库，（完整版本【破解】）正常使用） | Wine 10.19 + Yabridge Wine 10分支 |
| Spirtfire BBCSO 探索版 | NOS-F | ❌ | UI无法正常加载，会让宿主挂起 | Wine 9.21 + Yabridge 主线 |
| Spitfire Labs | NOS-F | ❌ | UI无法正常加载，会让宿主挂起 | Wine 9.21 + Yabridge 主线 |
| Pneuma | NOS-F | ❌ | 会让整个系统挂起 | Wine 9.21 + Yabridge 主线 |
| BFD Drum Player | NOS-F | ❌ | 无法正常安装 | Wine 9.21 + Yabridge 主线 |

## 效果器

| 软件名称 | 软件类型 | 是否可用 | 备注 | 使用兼容层 |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| Plugin Allance Free | NOS-F | NC✅ | Wine 10.19 + Yabridge Wine 10分支 |
| Raum | NOS-F | NC✅ |  | Wine 9.21 + Yabridge 主线 |
| Analog Obsession Bundle | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Baby Comeback | NOS-F | NC✅ | | Wine 10.19 + Yabridge Wine 10分支 |
| Magic Switch | NOS-F | NC✅ | | Wine 10.19 + Yabridge Wine 10分支 |
| Magic Dice | NOS-F | NC✅ | | Wine 10.19 + Yabridge Wine 10分支 |
| KClip Zero | NOS-F | NC✅ | | Wine 10.19 + Yabridge Wine 10分支 |
| Wider | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| theTAPE | NOS-P | NC✅ | | Wine 10.19 + Yabridge Wine 10分支 |
| Initial Dynamic EQ | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| OTT | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| TDR Nova | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Initial Clipper | NOS-F | NC✅ |  | Wine 10.19 + Yabridge Wine 10分支 |
| Gravity Granular Reverb | NOS-F | NC✅ | UI可能存在问题 | Wine 10.19 + Yabridge Wine 10分支 |
| GraterLight | NOS-F | NC✅ | 推荐选择OpenGL | Wine 10.19 + Yabridge Wine 10分支 |
| LoFi-FluxLight | NOS-F | NC✅ | 推荐选择OpenGL | Wine 10.19 + Yabridge Wine 10分支 |
| SpreadLight | NOS-F | NC✅ | 推荐选择OpenGL | Wine 10.19 + Yabridge Wine 10分支 |
| CrispyClipLight | NOS-F | NC✅ | 推荐选择OpenGL | Wine 10.19 + Yabridge Wine 10分支 |
| Valhalla DSP Bundle | NOS-P | NC✅ | 测试版本为Crack | Wine 10.19 + Yabridge Wine 10分支 |
| FabFilter Bundle | NOS-P | NC✅ | 测试版为Crack，正版状态未知 | Wine 10.19 + Yabridge Wine 10分支 |
| LFOTools | NOS-P | NC✅ | UI可能闪烁，测试来源为Crack | Wine 9.21 + Yabridge 主线 |
| BlackRooster Audio 套件 | NOS-FP | ❌ | 无法载入到Wine插件主机 | Wine 9.21 + Yabridge 主线 |
| LANDR Mastering | NOS-P | ❌ | 无法载入UI | Wine 9.21 + Yabridge 主线 |
| iZotope Bundle | NOS-F | ❌ | 加密问题，正版无法正常激活 |Wine 9.21 + Yabridge 主线 |
| Fresh Air | NOS-F | ❌ | 使用iLOK，正版无法正常激活 | Wine 9.21 + Yabridge 主线 |
| Heatware | NOS-F | ❌ | 使用iLOK，正版无法正常激活 | Wine 9.21 + Yabridge 主线 |
| Softube Saturation Knob | NOS-F | ❌ | 使用iLOK，正版无法正常激活 | Wine 9.21 + Yabridge 主线 |
| Efx REFRACT | NOS-P | ❌ | UI 卡死 | Wine 10.19 + Yabridge Wine 10分支 |

## 厂商管理工具

| 软件名称 | 软件类型 | 是否可用 | 备注 | 使用兼容层 |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| Native Access | NOS | ❌ | 仅限经典版本，无法正常挂载，新版NodeJS可能无法打开且安装库困难 | Wine 9.21 |
| Spitfire | NOS | ❌ | Labs和喷火无法正常使用，能用管理工具是何意味 | Wine 9.21 |
| iZotope | NOS | ❌ | 无法正常激活 | Wine 9.21 |
| Softube | NOS | ❌ | 绑定iLok | Wine 9.21 |
| UAD | NOS | ❌ | 绑定iLok | Wine 9.21 |
