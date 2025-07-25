# myune\_music

一个基于 **Flutter (Dart)** 实现的简易本地音乐播放器。

## ✨ 特性

* 使用歌单管理歌曲
* 使用 [**Material 3**](https://m3.material.io/) 配色
* 支持导入多种**本地音频格式**，自动读取**音频元数据**
* 支持**歌词显示**，兼容本地 `.lrc` 文件及音频文件中的**内嵌歌词**，支持从网络获取歌词
* 提供**左右声道平衡**与**倍速播放**功能
* 支持读取多种**音频文件信息**
* 可自定义**主题配色**与**字体**
* 支持 **SMTC（系统媒体传输控制）**

## 🌐 关于网络歌词获取

项目内置的歌词 API 是由我个人部署的，**不保证稳定性或可用性**。

如有条件，建议自行部署歌词 API，参考官方部署文档：

👉 [https://docs.lrc.cx/docs/QuickStart](https://docs.lrc.cx/docs/QuickStart)

## 📸 项目截图
![](screenshot/92379F29815DB2236510F9AD0C520ECD.png)
![](screenshot/57116242568D08EF8791737C8D881C06.png)
![](screenshot/D022283844CC6305B4473129E49BBAE2.png) 
![](screenshot/ADDF04814968BACDC75CAD173DA0C4AD.png)

## 🚀 快速开始

### 环境要求

* 安装 **Rust** 环境
* 安装 **Flutter SDK**，版本需 ≥ 3.8.0

### 安装依赖

```bash
flutter pub get
```

### 启动项目

```bash
flutter run
```

## 📦 使用的插件与致谢

* [**audio\_metadata\_reader**](https://pub.dev/packages/audio_metadata_reader)：读取音频元信息
* [**audioplayers**](https://pub.dev/packages/audioplayers)：音频播放支持
* 更多依赖请查看 [pubspec.yaml](pubspec.yaml)

感谢以下项目和开发者的无私分享：

* [**爱情终是残念**](https://aqzscn.cn/archives/flutter-smtc) 与 [**Ferry-200**](https://github.com/Ferry-200/coriander_player)：提供了 Rust + Flutter 的 **SMTC 实现参考**
* [**LrcApi**](https://github.com/HisAtri/LrcApi)：提供了开源的**歌词 API 服务**

🙏 再次致敬所有热爱开源、默默付出的开发者们！

## 📄 许可证

本项目使用 **Apache License 2.0** 开源许可协议。
详细内容请查看根目录下的 [LICENSE](/LICENSE) 文件。

## 🔤 字体版权说明（Font License）

本项目使用小米公司提供的 **MiSans 字体**，该字体已明确允许**免费商用**。

* 字体版权归小米公司所有
* 相关许可协议请查阅：[MiSans 字体知识产权使用许可协议](https://hyperos.mi.com/font-download/MiSans%E5%AD%97%E4%BD%93%E7%9F%A5%E8%AF%86%E4%BA%A7%E6%9D%83%E8%AE%B8%E5%8F%AF%E5%8D%8F%E8%AE%AE.pdf)
* MiSans 官网：[https://hyperos.mi.com/font/](https://hyperos.mi.com/font/)
