# bytedesk helpdesk system

- [萝卜丝-智能客服-中文文档](https://git.oschina.net/270580156/bytedesk-flutter)
- [Push](https://pub.dev/packages/bytedesk_push)

bytedesk flutter helpdesk sdk

- [Website](https://www.bytedesk.com)
- [Download Gitee Demo](https://git.oschina.net/270580156/bytedesk-flutter)
- [Download Github Demo](https://github.com/Bytedesk/bytedesk-flutter)
<!-- - [Download ApkDemo](https://bytedesk.oss-cn-shenzhen.aliyuncs.com/apk/bytedesk-android-sdk-demo.apk) -->

## Features

- support andorid/ios/web
- chat with agent
- shopping chat, send commodity info
- send post script message
- check online status
- get history thread
- message voice && vibrate setting
- chat with robot
- send and play video message
- chat notification
  <!-- - support faq list -->
  <!-- - support feedback -->

## Getting Started

### Zero Step: Copy Assets dir from bytedesk_demo

```dart
assets:
    - assets/audio/
    - assets/images/chat/
    - assets/images/feedback/
```

### First Step: Register Account

- [Register](https://www.bytedesk.com/admin)
- [Docs](https://github.com/pengjinning/bytedesk-android)

### Second Step：Login

```dart
// appkey和subDomain请替换为真实值
// 获取appkey，登录后台->渠道管理->Flutter->添加应用->获取appkey
String _appKey = '81f427ea-4467-4c7c-b0cd-5c0e4b51456f';
// 获取subDomain，也即企业号：登录后台->客服管理->客服账号->企业号
String _subDomain = "vip";
BytedeskKefu.init(_appKey, _subDomain);
```

### Third Step：Contact

```dart
BytedeskKefu.startWorkGroupChat(context, workGroupWid, "title");
```

### Completed

|                                                image1                                                 |                                                 image2                                                  |                                                  image3                                                  |
| :---------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
|  <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/home.jpeg?raw=true" width="250">  |  <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/robot.jpeg?raw=true" width="250">   |  <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/notice.jpeg?raw=true" width="250">   |
|  <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/chat.png?raw=true" width="250">   |   <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/shop.png?raw=true" width="250">    | <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/postscript.png?raw=true" width="250"> |
| <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/status.jpeg?raw=true" width="250"> | <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/userinfo.jpeg?raw=true" width="250"> |                                                                                                          |

### Change UI

- create new folder: vendors
- [Download](https://pub.dev/packages/bytedesk_kefu/versions) latest source code, put into vendors folder
- integrate source in pubspect.yaml

```dart
bytedesk_kefu:
    path: ./vendors/bytedesk_kefu
```

### Support

- [官网](https://www.bytedesk.com/)
- QQ 3Group: 825257535
- Follow Us：
- <img src="https://github.com/Bytedesk/bytedesk-flutter/blob/master/luobosi_mp.png?raw=true" width="250">

### Other

- [Flutter Push SDK](https://pub.dev/packages/bytedesk_push)
- [Flutter SDK](https://github.com/bytedesk/bytedesk-flutter)
- [UniApp SDK](https://github.com/bytedesk/bytedesk-uniapp)
- [iOS SDK](https://github.com/bytedesk/bytedesk-ios)
- [Android SDK](https://github.com/bytedesk/bytedesk-android)
- [Web](https://github.com/bytedesk/bytedesk-web)
- [微信公众号/小程序接口](https://github.com/bytedesk/bytedesk-wechat)
- [服务器端接口](https://github.com/bytedesk/bytedesk-server)
- [机器人](https://github.com/bytedesk/bytedesk-chatbot)
