# Staff & Notes · 谱间

**一个通过点击、聆听和练习，帮你学会看五线谱的交互式网页。**

从零开始，把谱面上的位置、琴键上的音和耳朵听到的声音连起来。不用先背完乐理，点一个音符就能开始。

## 可以怎么玩？

- **点着认音**：点击五线谱与琴键，听音高、看音名，切换高低音谱号。
- **轻松记忆**：从中央 C、高音 G、低音 F 三个地标出发，认识线与间。
- **看懂符号与节奏**：翻符号图鉴、拼一小节节奏，跟着《小星星》打拍。
- **练到认得出**：每轮 10 题，不限时；易错音留下来，慢慢复习。

## 开始使用

下载 [pujian-music-lab.html](./pujian-music-lab.html)（打开文件页，点击 **Download raw file**），用浏览器打开即可。

**无需安装、无需登录，下载后可离线使用。** 第一次点击后才会发声，练习记录保存在当前浏览器。

第一次来？先点几个音，再去「记忆地图」找三个地标，最后做一轮认音练习。

## 部署到 Cloudflare Pages

1. 从仓库 **Code → Download ZIP** 下载并解压。
2. 在 [Cloudflare 控制台](https://dash.cloudflare.com/) 打开 **Workers & Pages → Create application**，选择 **Pages 的 Direct Upload（直接上传）**。
3. 上传包含 `index.html` 和 `pujian-music-lab.html` 的文件夹，项目名可填 `staff-and-notes`，点击 **Deploy**。

无需构建。部署成功后，Cloudflare 会提供访问网址；手动上传不会随 GitHub 更新自动同步。[部署说明](https://developers.cloudflare.com/pages/get-started/direct-upload/)

*每天认识一点点，音乐就会慢慢清晰。*
