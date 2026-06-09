# ChingTech Case Hub

擎添工業 ChingTech 的 GitHub Pages 案例整合頁。

這個 repo 用來集中展示組織內外與擎添工業相關的實際系統、模擬器與常用工具，讓訪客可以從單一入口找到 demo、GitHub repo、案例分類與目前 Pages 狀態。

## Pages

預計發布網址：

```text
https://ching-tech.github.io/chingtech-case-hub/
```

## 首批收錄

- AGV Simulation
- ChingTech Meter HMI
- CTOS Lite
- Production Line Visualization Simulator
- RGV Simulation

## 更新案例

目前案例資料放在 `index.html` 內的 `projects` 陣列。新增案例時補上：

- `name`
- `repo`
- `demo`
- `expectedDemo`
- `domain`
- `category`
- `status`
- `statusText`
- `summary`
- `tags`

若 GitHub Pages 尚未啟用，`demo` 保持空字串，並把預計網址放在 `expectedDemo`。
