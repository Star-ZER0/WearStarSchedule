<div align="center">

# 腕上星课表 · WearStarSchedule

<a href="assets/app-icon.svg" title="腕上星课表 · WearStarSchedule">
  <img src="assets/app-icon.svg" width="128" height="128" alt="腕上星课表 应用图标">
</a>

一款为 WearOS 和 Android 手表打造的智能课程表应用，让课程信息随时触手可及。
A WearOS / Android Watch timetable application that brings your courses to your wrist with a native smartwatch experience.

[![Wear OS](https://img.shields.io/badge/Wear%20OS-API%2028%20to%2037-1A73E8?style=flat-square&logo=wearos&logoColor=white)](#系统要求)
[![Android Watch](https://img.shields.io/badge/Android%20Watch-round%20%2F%20square-3DDC84?style=flat-square&logo=android&logoColor=white)](#功能特性)

[![APK](https://img.shields.io/badge/APK-Download-3DDC84?style=flat-square&logo=android&logoColor=white)](https://github.com/Star-ZER0/WearStarSchedule/releases)

[![Kotlin Multiplatform](https://img.shields.io/badge/Kotlin%20Multiplatform-shared%20backend-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](#技术栈)
[![Wear Compose](https://img.shields.io/badge/Wear%20Compose-Material%203-4285F4?style=flat-square&logo=android&logoColor=white)](#技术栈)

[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)](#技术栈)
[![Lit](https://img.shields.io/badge/Lit-2F6BFF?style=flat-square&logo=lit&logoColor=white)](#技术栈)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](#技术栈)

[![Offline](https://img.shields.io/badge/100%25%20offline-no%20cloud%2C%20no%20account-2EA043?style=flat-square)](#隐私)
[![Web manager](https://img.shields.io/badge/web%20manager-LAN%20HTTP%20%2B%20code-0969DA?style=flat-square)](#功能特性)
[![MCP](https://img.shields.io/badge/AI%20via%20MCP-Streamable%20HTTP-7C3AED?style=flat-square)](#功能特性)
[![i18n](https://img.shields.io/badge/lang-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%20%2F%20English-5B6CAD?style=flat-square)](#功能特性)

[![License](https://img.shields.io/badge/license-closed%20source%20for%20now-E8833A?style=flat-square)](#开源状态)
[![Status](https://img.shields.io/badge/status-active%20development-brightgreen?style=flat-square)](https://github.com/Star-ZER0/WearStarSchedule/releases)
[![Issues](https://img.shields.io/github/issues/Star-ZER0/WearStarSchedule?style=flat-square&logo=github&label=feedback)](https://github.com/Star-ZER0/WearStarSchedule/issues)
[![QQ Group](https://img.shields.io/badge/QQ%20Group-1124571903-12B7F5?style=flat\&logo=qq\&logoColor=white)](https://qm.qq.com/q/hfBDpyJkeO)

</div>

---

## 开源状态

**本项目暂时不开源。**

当前仓库不包含源代码，仅作为产品主页使用：版本发布与更新说明、功能文档、问题反馈与讨论都在这里进行。

- **后续有机会会开源。** 一旦具备开源条件，会选择合适的许可证公开源码，并在 Releases 与本页公告中说明。
- 在此期间，欢迎提交问题反馈、功能建议与适配信息（机型 / 屏幕形状 / 系统版本）。你的反馈会直接影响后续版本的优先级。

> 如果你需要反馈问题，请通过 [Issues](https://github.com/Star-ZER0/WearStarSchedule/issues) 提出。

---

## 系统要求

| 项目 | 要求 |
|---|---|
| 设备 | Wear OS 及兼容的 Android 手表（圆形 / 方形屏幕） |
| 系统版本 | API 28 及以上（Android 9 起），面向 API 37 构建 |

## 安装与更新

1. 在 [Releases](https://github.com/Star-ZER0/WearStarSchedule/releases) 下载最新 APK。
2. 将 APK 安装到手表（侧载安装，或通过手机侧载工具推送）。
3. 首次启动会创建一张空课表，默认进入「今天」。

---

## 功能特性

**极简APP**
- 仅个位数MB大小
- 功能齐全，可完全离线在手表管理课程
- 无需手机配套APP

**课表与学期**

- 今天 / 学期 / 设置三页滑动
- 周 → 日期 → 课程三级浏览
- 多课表管理，每张课表独立学期配置
- 课程状态实时刷新：已结束灰显、进行中高亮
- 命名节假日整段停课、整日调课
- 学期进度卡片

**提醒**

- 课前提醒与全屏上课闹钟
- 早间当日 / 晚间次日课程总结
- 内置、系统与自定义音频铃声
- 通知、闹钟、网络、文件权限集中管理

**外观**

- 圆形 / 方形两种屏幕样式
- 预设主题色 + RGB 自定义 + 跟随系统主题色
- 课程颜色独立取色
- Wear Compose Material 3 组件

**数据**

- JSON 导入导出，内置文件选择器
- 自动与手动本地备份，多版本保留
- 私有目录与公共存储两种备份位置

**网页管理（手机 / 电脑）**

- 局域网 HTTP + 6 位验证码
- 课程、课表与设置全量编辑
- 权限状态查看与授权命令复制
- 独立网页主题：跟随系统 / 深色 / 浅色
- 资产离线打包，无 CDN、无云端后端

**AI 与 MCP**

- Streamable HTTP MCP 服务，临时 Bearer 令牌
- 课程范围工具：课表、课程、学期、节假日、调课
- `mcp.json` 与 `wearstarschedule-skill` 下载

---

## 隐私

- 课表与设置全部保存在手表本地，无云端后端、无账号、无遥测上报。
- 网页管理仅走局域网 HTTP，关闭服务后端口即不可访问。
- 文件访问只用于导入导出与备份，不会上传数据。

## 技术栈

手表端 **Wear Compose Material 3**；网页端 **Vite + Lit + TypeScript + Material Design 3**；两端共用 **Kotlin Multiplatform** 课程后端。

## 赞助

如果这个项目对你有帮助，欢迎通过 Ko-fi 或微信赞赏支持开发。

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I1J826UQFX)

微信赞赏码：

[![星澪 Star_ZER0 的微信赞赏码](assets/tipcode.jpg)](assets/tipcode.jpg)

## 关于

作者：星澪 Star_ZER0 · [个人主页](https://star0.cc)

本项目部分实现由 AI 辅助生成。

## 许可

暂时不开源，未授予任何源代码使用许可；本 README 与文档内容可用于了解与试用本产品。后续开源计划见[开源状态](#开源状态)。
