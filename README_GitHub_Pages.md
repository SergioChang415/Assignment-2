# 把报告网站发布到 GitHub Pages(约 10 分钟)

1. 登录 github.com,点右上角 **+ → New repository**。
   - 名字填 `whats-left-on-the-plate`,选 **Public**,点 **Create repository**。
2. 在新仓库页面点 **uploading an existing file**。
   - 把这个文件夹里的 **index.html** 和整个 **assets** 文件夹一起拖进去,然后点 **Commit changes**。
3. 打开仓库的 **Settings → Pages**。
   - Source 选 **Deploy from a branch**,Branch 选 **main**,文件夹选 **/(root)**,点 **Save**。
4. 等 1–2 分钟,刷新 Pages 页面,上方会显示网址:
   `https://你的用户名.github.io/whats-left-on-the-plate/`
   这个网址就是交到 Canvas 的链接。

## 交之前要改的地方
- 用文本编辑器(比如 VS Code)打开 `index.html`,搜索 `class="ph"`,把所有方括号占位换成你们的内容:
  - 名字、课程代码
  - 组员海报的描述
  - 三篇文献的反思段落
  - Draft 反馈
  - 音乐来源
- **海报:** 已经放好了(assets/poster_1.jpg、poster_2.jpg)。海报如果更新,用同样的文件名覆盖即可。
- **视频:** 如果你在 AE 里导出了最终版,覆盖 `assets/video_social_cut.mp4` 即可,保持同样的文件名。
- 改完再上传一次覆盖旧文件,网站会自动更新。
