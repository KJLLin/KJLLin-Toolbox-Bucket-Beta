# KJLLin Toolbox — 内测版 bucket

内测 / 灰度清单，仅限受邀测试者安装。

客户端已内置本 bucket：`toolbox-beta` → `https://github.com/KJLLin/KJLLin-Toolbox-Beta`。

## 使用

```powershell
scoop bucket add toolbox-beta https://github.com/KJLLin/KJLLin-Toolbox-Beta
scoop install toolbox-beta/clipflow
```

同一个包可以同时存在稳定版与内测版：稳定版在 `KJLLin-Toolbox`，内测版在本仓库，客户端里会显示为两个来源。

> 当前清单指向的 Release 资产需自行上传，`hash` 也需校验后再发布。
