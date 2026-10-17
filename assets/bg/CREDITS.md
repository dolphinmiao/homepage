# 背景图来源与许可

`bg-1..6-{1280,1920}.webp` 是首页随机背景用的 6 张图，每张两档（最长边 1280 / 1920，WebP）。

- **来源**：[Picsum Photos](https://picsum.photos/)（图片全部取自 [Unsplash](https://unsplash.com/)）
- **许可**：[Unsplash License](https://unsplash.com/license)——可免费用于商业/非商业用途、可修改、可再分发，无需授权（署名非强制，这里仍列出作者以示尊重）
- 下载地址形如 `https://picsum.photos/id/<id>/2560/1440`，之后本地转 WebP 并去掉元数据

| 文件 | Picsum id | 作者 | 原图 |
|---|---|---|---|
| `bg-1-*.webp` | 10 | Alejandro Escamilla | https://unsplash.com/photos/6J--NXulQCs |
| `bg-2-*.webp` | 37 | Austin Neill | https://unsplash.com/photos/erTjj730fMk |
| `bg-3-*.webp` | 46 | Jeffrey Kam | https://unsplash.com/photos/Nzw3HHsNHYU |
| `bg-4-*.webp` | 51 | Ireneuilia | https://unsplash.com/photos/knYQ6arClBE |
| `bg-5-*.webp` | 56 | Sebastian Muller | https://unsplash.com/photos/VLdaxYyXJvw |
| `bg-6-*.webp` | 38 | Allyson Souza | https://unsplash.com/photos/JabLtzJl8bc |

## 想换图 / 加图

把 WebP 丢进这个目录，命名成 `bg-<序号>-1280.webp` 和 `bg-<序号>-1920.webp`（序号从 1 连到 N），然后把 `index.html` 里那段内联脚本的 `COUNT` 改成 N 即可，CSS 不用动。

单张建议 1280 档 ≤120 KB、1920 档 ≤200 KB（q76 左右、`-strip`、`webp:method=6` 就差不多）；6 张两档合计约 1.34 MB。
