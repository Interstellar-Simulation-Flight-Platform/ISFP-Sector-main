# ISFP 云际模拟飞行连飞平台管制扇区 (Interstellar Simulation Flight Platform Sector)

**由于中国港澳台地区使用不同的飞行规则，我们暂时没有制作相关扇区。**

ISFP 云际模拟飞行连飞平台管制扇区致力于提供**免费**、**开源**的 EuroScope 扇区，以帮助来自世界各地的模拟管制爱好者获得更好的模拟飞行体验。

如果您在使用扇区的过程中遇到了任何问题、或者有任何好的建议，欢迎在 [ISFP GitHub](https://github.com/Interstellar-Simulation-Flight-Platform) 向我们提出！

> 本扇区基于 [AirAmaz-Sector](https://github.com/AirAmaz/AirAmaz-Sector) 制作，按照 [GPL-3.0 许可证](LICENSE)开源。

### 飞行情报区

| 情报区名称 | 导航数据版本 |
| --- | --- |
| ZBPE | AIRAC2610 |
| ZGZU | AIRAC2610 |
| ZHWH | AIRAC2610 |
| ZJSA | AIRAC2610 |
| ZLHW | AIRAC2610 |
| ZPKM | AIRAC2610 |
| ZSHA | AIRAC2610 |
| ZWUQ | AIRAC2610 |
| ZYSH | AIRAC2610 |

*FSS（PRC_FSS）席位使用全国合并扇区数据（AIRAC2610）。*

### 连飞服务器

| 服务 | 地址 |
| --- | --- |
| FSD（EuroScope / Swift） | `fsd.flyisfp.com`（默认端口 `6809`） |
| TeamSpeak 语音 | `ts.flyisfp.com` |
| 官网 | [www.flyisfp.com](https://www.flyisfp.com) |
| 文档站 | [docs.flyisfp.com](https://docs.flyisfp.com) |

> 服务器地址已预置于 `Data\Settings\Servers.txt`，如端口有调整请在 EuroScope 连接窗口中自行修改。

### 前置要求

1. 为保证扇区能够正常加载，您需要安装最新的 Microsoft Visual C++ (x86) 可再发行程序包版本：https://aka.ms/vs/17/release/vc_redist.x86.exe
2. 同时您需要安装 DirectX Runtime 以支持我们的渲染库运行：https://www.microsoft.com/en-us/download/details.aspx?id=35

### 使用教程

- 持续更新中，参见 [ISFP 文档站](https://docs.flyisfp.com)

### 配置扇区

由于版权原因，本扇区**不提供** Navigraph 导航数据，您需要订阅 Navigraph Unlimited 以获取最新的导航数据。

1. 在浏览器中打开 https://navigraph.com/downloads ，下载 `FSNavigator` 导航数据。
2. 下载后安装导航数据到任意位置，然后将安装的 `AIRWAY.txt` 和 `ISEC.txt` 复制进扇区的 `Data\NAV\` 目录内。
3. 【可选】将你的 MTEP 配置文件放入 `Data\Plugins\MTEP\` 目录内。

尽情享受吧！

### 包含插件

| 插件名称 | 主要作者 |
| --- | --- |
| TopSky Plugin（闭源） | Juha Holopainen |
| Ground Radar plugin（闭源） | Juha Holopainen |
| MTEPlugin | [KingfuChan](https://github.com/KingfuChan/MTEPlugin-for-EuroScope) |
| RDF Plugin | [KingfuChan](https://github.com/KingfuChan/RDF) |
| VCH Plugin | [Jan Fries](https://github.com/DrFreas/VCH) |
| Compass for Euroscope（闭源） | [William He](https://github.com/fwilliamhe) |
| AirAmaz RenderPlugin（闭源） | [William He](https://github.com/fwilliamhe) |
| ISFPPlugin（语音 / TSLink） | ISFP 云际模拟飞行连飞平台 |

### 外部内容

| 名称 | 来源 |
| --- | --- |
| TopSky Symbols | [uk-controller-pack](https://github.com/VATSIM-UK/uk-controller-pack) |
| ICAO_* files | 2313 [VATPRC](https://www.vatprc.net/) Sector |
| TopSky Cursors | [VATPRC](https://www.vatprc.net/) |

### 贡献者

- [William He](https://github.com/fwilliamhe)
- [Bradley.L](https://github.com/BradleyLu)
- [天真永不消逝](https://github.com/shiguanglindi)
- [Yifan Jin](https://github.com/N28888)
- [8305](https://github.com/wvemil)
- [fulkarl](https://github.com/fulkarl)
- [Dapeng Liu](https://github.com/DapengLiu01)
- [F̶i̶n̶a̶l̶.̶]()
- [tn.]()
- [Zihan Wang]()
- [QuanQuan](https://github.com/DamnQuan)

### 声明

本项目可能包含来源于公开互联网资源的数据或信息。所有此类内容均为其各自所有者的知识产权。使用这些资源仅限于教育和非商业目的，并遵守适用的版权法律。如果您是所使用内容的所有者并希望其被移除或获得适当的署名，请与我们联系，我们将采取相应措施。

### 遇到 Bug？

请在 Issues 中报告。

## 许可证

本项目按照 [GPL-3.0](LICENSE) 许可证开源。本项目为 [AirAmaz-Sector](https://github.com/AirAmaz/AirAmaz-Sector) 的修改版本，依照 GPL-3.0 许可证第 5(a) 条要求，修改内容记录于 [CHANGELOG.md](CHANGELOG.md)。
