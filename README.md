<p align="center">
  <img src="https://github.com/qingshan2048/img/blob/main/bice.png" width="248">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Full Name-BC TradeSystem-brightgreen?logo=Windows Terminal" alt="Full Name"/>
  <img src="https://img.shields.io/badge/Operating System-Winodws 7/8/9/10/11-success?logo=Windows" alt="Operating System"/>
  <img src="https://img.shields.io/badge/Trade Style-Hedging Transaction-brightgreen?logo=Untangle" alt="Miner Core"/>
</p>

# 🔥 币策  `对冲交易系统`

- **适用场景**：通过在交易所对冲交易实现虚拟货币盈利
- **图形界面**：操作界面干净整洁，清晰易懂，配置简洁方便
- **程序设计**：采用计算机底层纯C语言编写，运行稳定流畅不卡顿
- **软件算法**：内置性能优良的算法引擎，确保行情掌控的精准性灵敏性
- **特色功能**：兼容大多数交易所，并且和交易所的数据接口实现了高速优化
- **数据安全**：软件处理的数据采用数据加密处理，确保了数据传输过程中的安全
- **更新升级**：软件常年保持高频率的更新，最大限度的保证了性能和市场的高度匹配

## 💡 软件展示

<p align="center">
<img src="https://github.com/qingshan2048/img/blob/main/bice_zhanshi.png" width="640">
</p>

## 📝 文件下载

- 文件可在上方 <img src="https://img.shields.io/badge/code-brightgreen"/> 按钮中点击 `Download ZIP` 下载，或者右侧 Releases 里下载

|  文件名称  |  说明  |  格式  |
|---|---|---|
|  BICE v1.xx.b.exe  |  币策对冲交易系统主程序  |  Windows系统 二进制可执行文件  |
|  README.md  |  程序介绍及使用说明文件  |  Github程序社区md格式说明文件  |

## 🔧 安装使用

- 运行系统 Windows 7/8/10/11

```bash
1.双击运行软件，填写参数及交易方式，点击开始交易即可

2.如账户余额不足可以选择充值，点击充值完成龙币的充值
```

## 🌭 参数格式

- 需要正确配置交易所的密钥才可以访问交易所的账户进行交易

|  密钥  |  格式  |  说明  |
|---|---|---|
|  Access Key  |  fr2wer5t6y-c270284b-125387ca-4b0b9  |  公钥，需要在交易所中提取  |
|  Secret Key  |  1b7w338c-84ea5d6w-edfa778e-1a125  |  私钥，需要在交易所中提取  |

## 🔨 更新日志

- 参考 [vue](https://github.com/vuejs/vue/blob/dev/.github/COMMIT_CONVENTION.md) 规范 ([Angular](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-angular))
```bash
2023-00-00 - v1.00.b（即将发布）
2022.12.00 进一步解决了内存泄漏的问题
2022.12.00 完成配比功能，规范交易所代码，实现网络访问交易信息并可一键清空
2022.12.19 (X)对交易发起前进行交易安全审查，无法根据交易量准确判断订单被吃的进度
2022.12.15 (X)由于交易所跑路时间频发，计划考虑开发去中心化交易所的对冲交易功能
2022.12.15 增加了授权日期，增加了网络验证功能
2022.12.14 增加了四级阶梯交易模式，增加了保存日志的功能
2022.12.13 (X)增加交易量可根据交易深度数据动态调整的功能模块
2022.12.12 引入了交易偏移量，根据火币交易所的规则变动调整了最小交易量（10USDT）
2022.12.10 优化为先交易后显示，避免由于界面显示对交易线程造成阻塞
2022.12.10 (X)对币策交易数据处理采用多线程处理机制，避免造成交易相对行情的时空滞后
2022.12.10 (F)计划开发多边交易
2022.12.07 设计了交易强度（交易量），和交易手续费抵消算法，增加了任意交易功能
2022.12.06 修复了由于网络延迟导致的软件崩溃，修复了交易信息面板的数据混乱问题
2022.12.01 精准校正了UTC时钟，月初年初时间不错乱
2022.11.29 优化了交易信息显示面板的数据乱窜问题并优化了软件界面启动默认按钮
2022.11.28 基本完成了对冲交易的功能
2022.11.26 修复了账户余额显示不稳定的问题，并可以自定义货币种类余额查询
2022.11.23 修复了数组定义导致的内存增长
2022.11.19 完成了火币的网络交易功能，币策采用脉冲交易模式
2022.11.17 完成了UnixTimestamp时间戳模块
2022.11.10 找到了稳定的JSON数据处理方案
2022.11.03 替换掉了不稳定的网络通信模块
2022.10.20 完成的软件的LOGO最终设计方案
2022.10.19 Yang第一次提出使用币策这个名字并决定采用币策作为软件的名字
2022.10.18 决定采用付费币模式进行软件的使用计费
2022.10.14 在Yang的调研下决定设计搬砖机器人
```

## 🚑 疑难解决

- 软件在使用VPN的系统上出现联网卡顿的问题：可能是由于VPN的防火墙阻止了网络连接请求，可以考虑使用香港服务器
- 系统提示无法找到 VCRUNTIME140.DLL，MSVCP140.DLL，VCRUNTIME140_1.DLL 的解决方法：https://github.com/qingshan2048/resource/tree/main#%E5%B8%81%E7%AD%96%E7%B3%BB%E7%BB%9F%E6%8F%90%E7%A4%BA%E6%97%A0%E6%B3%95%E6%89%BE%E5%88%B0-vcruntime140dllmsvcp140dllvcruntime140_1dll-%E7%9A%84%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95

## 🐛 相关资源 

- **机场推荐**：http://www.xihoogsi.com/index.php#/register?code=lCEyvEDI
- **关于作者**：如有其他业务可以通过下面的方式联系作者
- <img src="https://github.com/qingshan2048/img/blob/main/weixin_bice.png" width="400">
