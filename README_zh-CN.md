[English](./README.md) | 简体中文

# flutter_icons

[![pub package](https://img.shields.io/pub/v/flutter_icons.svg)](https://pub.dartlang.org/packages/flutter_icons)

在Flutter中使用可定制的图标，该插件包是受到 [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)启发而开发

## 可用的图标

[浏览所有](https://oblador.github.io/react-native-vector-icons/).

* [`AntDesign`](https://ant.design/) by AntFinance (**297** icons)
* [`Entypo`](http://entypo.com) by Daniel Bruce (**411** icons) 
* [`EvilIcons`](http://evil-icons.io) by Alexander Madyankin & Roman Shamin (v1.10.1, **70** icons) 
* [`Feather`](http://feathericons.com) by Cole Bemis & Contributors (v4.7.0, **266** icons) 
* [`FontAwesome`](http://fortawesome.github.io/Font-Awesome/icons/) by Dave Gandy (v4.7.0, **675** icons)
* [`Foundation`](http://zurb.com/playground/foundation-icon-fonts-3) by ZURB, Inc. (v3.0, **283** icons)
* [`Ionicons`](https://ionicons.com/) by Ben Sperry (v4.2.4, **696** icons)
* [`MaterialIcons`](https://www.google.com/design/icons/) by Google, Inc. (v3.0.1, **932** icons)
* [`MaterialCommunityIcons`](https://materialdesignicons.com/) by MaterialDesignIcons.com (v2.8.94, **2894** icons)
* [`Octicons`](http://octicons.github.com) by Github, Inc. (v8.0.0, **177** icons)
* [`Zocial`](http://zocial.smcllns.com/) by Sam Collins (v1.0, **100** icons)
* [`SimpleLineIcons`](https://simplelineicons.github.io/) by Sabbir & Contributors (v2.4.1, **189** icons)

## 使用
要使用此插件包,请将flutter_icons作为依赖项添加到您的`pubspec.yaml`文件中,详见[dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

## 示例

``` dart
// 引入包
import 'package:flutter_icons/flutter_icons.dart';
import 'package:flutter/material.dart';

Icon(Ionicons.getIcon("ios-search"));
Icon(AntDesign.getIcon("stepforward"));
Icon(FontAwesome.getIcon("glass"));
Icon(MaterialIcons.getIcon("ac-unit"));
```
### 特别感谢react-native-vector-icons插件包及其开发者们
