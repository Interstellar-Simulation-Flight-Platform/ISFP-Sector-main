# 更新日志 / Changelog

本项目为 [AirAmaz-Sector](https://github.com/AirAmaz/AirAmaz-Sector) 的修改版本。依照 GPL-3.0 许可证第 5(a) 条要求，在此记录全部修改。

## 2026-10-11 — ISFP 云际模拟飞行连飞平台版 (Interstellar Simulation Flight Platform)

### 新增
- 扇区品牌化为 ISFP 云际模拟飞行连飞平台管制扇区（Interstellar Simulation Flight Platform）
- 新增 ISFP 连飞服务器配置：`fsd.flyisfp.com:6809`（`Data\Settings\Servers.txt`）
- 集成 ISFPPlugin 语音插件（`Data\Plugins\ISFPPlugin\`，x86，含 TSLinkBridge 与音效资源），并在全部 19 个 `.prf` 中默认加载

### 数据迁移
- 全部 9 个 FIR 扇区文件（`sct`/`ese`）由 AIRAC 2413 升级至 AIRAC 2610
- FSS 席位改用全国合并扇区数据（PRC，AIRAC 2610）
- ICAO 数据（飞机 / 航司 / 机场）更新至 2610
- 导航数据（`AIRWAY.txt` / `ISEC.txt` / `ICAO.txt`）更新至 2610 周期（仍需自行更新以获取最新周期）

### 目录结构
- 插件布局维持原状：TopSky / GRplugin / DxRenderPlugin 及其配置保留在各 FIR 的 `Plugins\` 目录内。曾尝试将 TopSky、GRplugin 统一收纳至 `Data\Plugins\<插件>\<FIR>\` 并更新其数据文件，因旧版插件与新版数据格式不兼容（GRpluginStands 无法读取、跑道延长线异常显示、滑行道编号丢失），已按原备份完整回归
- 仅新增 `Data\Plugins\ISFPPlugin\`（ISFP 语音插件），全部 19 个 `.prf` 默认加载

### 文档
- 修复损坏的 `README.md`，重写为 ISFP 品牌（中文）
- 移除赞助二维码图片（`Data\wechat_support.jpg`）与"Buy us a coffee"打赏章节
- 贡献者名单新增 QuanQuan；保留原贡献者与第三方素材致谢（GPL-3.0 合规）
