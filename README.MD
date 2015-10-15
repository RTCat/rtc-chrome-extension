# RTCat Chrome Extension


## 修改`manifest.json`配置文件

clone项目至本地，修改 `manifest.json` 配置文件中的 `externally_connectable` 为你使用的域名（必须是https协议，如`https://rtcat.io/*`）。

**示例**

```
  "externally_connectable": {
    "matches": [ "https://rtcat.io/*"]
```

**注意：** `*`**不能少！**

## 调试安装

在chrome浏览器中访问`chrome://extensions/`页面，勾选`Devloper mode`, 点击`Load unpacked extension...`，选择本插件安装。