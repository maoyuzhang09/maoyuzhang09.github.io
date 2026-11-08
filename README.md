# maoyuzhang09.github.io

Source of [Maoyu Zhang's academic homepage](https://maoyuzhang09.github.io/): a single static page (`index.html` plus `assets/`), with no build step.

## 维护说明

**改文字**：所有内容都在 `index.html` 里。在 GitHub 网页上打开这个文件，点右上角的铅笔图标编辑，提交（Commit changes）后一两分钟网站自动更新。

**加 CV、研究陈述、教学陈述**：把 PDF 按下表的文件名上传到仓库根目录（网页上点 **Add file → Upload files**）。上传后主页上对应的按钮会自动出现，不用改代码。

| 文件名 | 主页上的按钮 |
| --- | --- |
| `cv.pdf` | CV |
| `research-statement.pdf` | Research Statement |
| `teaching-statement.pdf` | Teaching Statement |

**加论文**：在 `index.html` 里复制一段 `<li class="pub">…</li>`，改标题、作者、期刊和链接；获奖信息用 `<p class="award">…</p>`。

**换照片**：替换 `assets/img/maoyu-zhang.jpg`，建议用 4:5 的竖图，宽 640 像素左右。

**求职状态**：找到工作后，删掉 `index.html` 里 `class="market"` 那一行。

**本地预览**：在这个文件夹里运行 `python3 -m http.server 8765`，然后打开 <http://localhost:8765>。
