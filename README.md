# 格里菲斯发育评估量表（GDS-C）快速计算工具

初生至八岁 · 基于《GRIFFITHS 发育评估量表-中文版》常模册子。

输入：生理年龄（月龄）+ A–E 五个领域的裸值。
输出：百分位数 + 与发育相当的月龄。

## 部署到 GitHub Pages（手机随时可用）

1. 登录/注册 GitHub（github.com）。
2. 右上角 **+** → **New repository**，仓库名如 `gdsc-calc`，选 **Public**，创建。
3. 在空仓库页点 **uploading an existing file**，把本文件夹里的 5 个文件全部拖进去，点 **Commit changes**。
4. 进入仓库 **Settings** → 左侧 **Pages**：
   - Source 选 **Deploy from a branch**；
   - Branch 选 **main**、文件夹选 **/ (root)**，点 **Save**。
5. 等 1–2 分钟，页面会给出网址：`https://你的用户名.github.io/gdsc-calc/`。
6. 手机浏览器打开该网址 → 菜单 → **添加到主屏幕**，即可像 App 一样使用（离线也可用）。

## 文件说明

- `index.html`：工具本体（数据已内置，单文件离线可用）
- `manifest.webmanifest`：PWA 清单（可安装到主屏幕）
- `sw.js`：离线缓存
- `icon-192.png` / `icon-512.png`：App 图标

> 数据由常模册子扫描版经 OCR 提取并做单调性平滑，仅供快速参考；正式评估请以纸质常模表为准。
