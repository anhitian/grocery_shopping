

> A tool for grocery shopping

### 实现方案

~~使用${ANDROID_HOME}/tools/bin/uiautomatorviewer.bat分析获取应用页面控件的resourceId~~

使用appium-inspector分析获取应用页面控件的resourceId

基于appium模拟控件点击事件，实现自动购买

目前这种方式需要很复杂的环境安装，比较麻烦，如有更好的方案，还请告知

发现更好的方案，建议参考此方案实现，整体性能比现在的方案要好很多
https://github.com/Skykai521/DingDongHelper

### 安装步骤

1.安装jdk1.8

2.安装Android SDK

3.安装appium appium-inspector

4.安装python环境

### 使用说明

1.连接手机设备，设备已安装叮咚买菜，开启开发者选项USB调试，登录并将添加物品到购物车，收货地址已填好

2.启动appium server

3.运行脚本

### 目标适配

- [x] 叮咚买菜

- [ ] 美团买菜

- [ ] 盒马生鲜

  