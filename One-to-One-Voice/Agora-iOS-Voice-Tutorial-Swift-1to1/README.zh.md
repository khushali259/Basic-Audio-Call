# Agora iOS Voice Tutorial for Swift - 1to1

*Read this in other languages: [English](README.md)*

这个开源示例项目演示了如何快速集成Agora音频SDK，实现1对1音频通话。

在这个示例项目中包含了以下功能：

- 加入通话和离开通话；
- 静音和解除静音；
- 切换扬声器和听筒；

你可以在这里查看进阶版的示例项目：[OpenVoiceCall-iOS](https://github.com/AgoraIO/Basic-Audio-Call/tree/master/Group-Voice-Call/OpenVoiceCall-iOS)

## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。你可以在你的项目页面生成一个临时的Token (生成的Token只能用于加入指定的频道)。将 AppID 和 Token 填写进 AppID.swift

```
let AppID: String = <#Your App ID#>
// assign Token to nil if you have not enabled app certificate
let Token: String? = <#Temp Token#>
```

然后在 [Agora.io SDK](https://www.agora.io/cn/download/) 下载 **语音通话 + 直播 SDK**，解压后将其中的 **libs** 文件夹复制到本项目目录下，和 “Agora iOS Voice Tutorial” 文件夹平级。

最后使用 XCode 打开 Agora iOS Voice Tutorial.xcodeproj，连接 iPhone／iPad 测试设备，设置有效的开发者签名后即可运行。

## 运行环境
* XCode 8.0 +
* 两台 iOS 真机设备
* 不支持模拟器

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的 bug, 欢迎提交 [issue](https://github.com/AgoraIO/Basic-Audio-Call/issues)

## 代码许可

The MIT License (MIT).
