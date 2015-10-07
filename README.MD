# RTCat Chrome extension

把 `manifest.json` 配置文件中的 `externally_connectable` 修改为你使用的域名（https only）, 如下面的 `https://rtcat.io/*`  

**注意：** `*`**不能少！**

```
  "externally_connectable": {
    "matches": [ "https://rtcat.io/*"]
```