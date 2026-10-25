# Xperia Play 游戏库

一个静态网页，用来浏览 Sony Ericsson Xperia PLAY 游戏合集里的 1051 个游戏（安卓、PS1、PlayStation Mobile）：中文简介、截图、类型和语言筛选、推荐与适合通勤的标签，以及每个版本在合集里的文件夹位置。

- `index.html`：页面本身，不需要构建，直接作为静态网站部署即可。
- `games.json`：游戏列表和中文简介。
- `icons.json`、`covers-*.json`、`shots-*.json`：图标、封面和截图（以 data URI 形式内嵌）。
- `manifest.json`：每个游戏的截图在哪个数据文件里。

简介根据 Steam、维基百科和 APKPure 的资料整理；截图来自 APKPure、Steam、维基百科和 LaunchBox Games Database，版权归各游戏的权利人所有。
