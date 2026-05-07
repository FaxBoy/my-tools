# 乐刻门店等级查询（H5）

纯静态页面：`index.html` + `leoao-stores-public.json`，无需后端。

源码位置：本仓库 **`my-tools/leoao-store-query/`**，与根目录 **`my-tools/index.html`** 中的小工具入口一并维护。

数据：来自闲鱼店铺「健身房男孩女孩」整理的「乐刻门店」公开 **H5 查询数据（JSON）**。将 `leoao-stores-public.json` 置于本目录即可覆盖默认数据；使用时与 `index.html` 放在同一目录。

不建议使用 `file://` 直接本地双击打开；若通过 **HTTPS** 部署且受跨域限制无法自动加载同目录 JSON，请使用页面上的「选择门店数据文件」手动载入。
