# 实现文本切换功能

## 项目简介

基于新建默认工程“Hello World”简单修改的“Hello HarmonyOS”案例，让零基础开发者能独立完成第一个HarmonyOS应用。

## 效果预览

| 手机                                                | 平板                                                 | PC/2in1                                        |
|---------------------------------------------------|----------------------------------------------------|------------------------------------------------|
| <img src='./screenshots/phone.png' width='320px'> | <img src='./screenshots/tablet.png' width='800px'> | <img src='./screenshots/pc.png' width='800px'> |


## 使用说明

点击“Click Me”按钮，使文本在“Hello World”和“Hello HarmonyOS”之间切换。

## 工程目录
```
├──AppScope
│  ├──app.json5
│  └──resources
├──build-profile.json5
├──entry
│  ├──build-profile.json5
│  ├──oh-package.json5
│  └──src
│     └──main
│        ├──ets
│        │  ├──entryability
│        │  │  └──EntryAbility.ets  // 程序入口类
│        │  ├──entrybackupability
│        │  │  └──EntryBackupAbility.ets 
│        │  └──pages
│        │     └──Index.ets         // 应用首页
│        ├──module.json5
│        └──resources               // 应用静态资源目录  
├──LICENSE
├──oh-package.json5
├──README.md
└──screenshots                                    
```

## 具体实现

1. 点击按钮后，利用if判断语句实现“Hello World”与“Hello HarmonyOS”文本的切换显示。
2. 使用@Preview装饰器，实现单个组件的实时预览效果。

## 相关权限

不涉及。

## 约束与限制

1. 本示例仅支持标准系统上运行，支持设备：手机、平板、PC/2in1。
2. HarmonyOS系统：HarmonyOS 6.0.2 Release及以上。
3. DevEco Studio版本：DevEco Studio 6.0.2 Release及以上。
4. HarmonyOS SDK版本：HarmonyOS 6.0.2 Release SDK及以上。