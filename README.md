# QYSDK CocoaPods Specs

网易七鱼 iOS SDK 的公开 CocoaPods Specs 仓库。

## 使用方式

在 `Podfile` 顶部声明七鱼 Specs 源和 CocoaPods 官方源：

```ruby
source 'https://github.com/qiyukf/QYSDK_specs.git'
source 'https://cdn.cocoapods.org/'
```

然后按需集成：

```ruby
pod 'QY_iOS_SDK', '~> 11.13.0'
pod 'QY_iOS_SDK/Abroad', '~> 11.13.0'
pod 'QY_iOS_SDK/Video', '~> 11.13.0'
```

## 维护说明

本仓库仅保存版本化 Podspec，不保存 SDK 二进制。SDK 内容和版本 tag 位于
[`qiyukf/QY_iOS_SDK`](https://github.com/qiyukf/QY_iOS_SDK)。
