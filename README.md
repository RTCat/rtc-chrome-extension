# 本项目已被整合进[RTCat/rtc-browser-extension](https://github.com/RTCat/rtc-browser-extension)，请前往该项目获取最近更新

# rtc-chrome-extension

实时猫屏幕分享插件

## 用于个人项目

### 配置

clone项目至本地，修改 `manifest.json` 配置文件中的 `externally_connectable` 为你的域名（必须是https协议，如`https://localhost:3000/*`, 后面的`*`不能少）。

**示例**

```
  "externally_connectable": {
    "matches": [ "https://localhost:3000/*"]
```

### 调试安装

在chrome浏览器中访问`chrome://extensions/`页面，勾选`Devloper mode`, 点击`Load unpacked extension...`，选择本插件安装。
