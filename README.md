# 拼音识字乐园

儿童拼音识字网页：部编版小学一年级上册识字表 300 字。

- 🌐 在线打开（手机/电脑均可）：https://dongjekyll.github.io/pinyin-shizi-web/
- 📖 学习模式：按课浏览、点击朗读、标记「我认识 / 还不熟」
- 🎲 乱序闯关：看字选拼音 / 看拼音选字 / 听音选字，答错自动重考
- 📊 进度记录：掌握率、每课进度、答题正确率，数据保存在本机浏览器

## 更新方法

重新构建后把 `dist/` 内容推送到本仓库 main 分支，Pages 会自动更新：

```bash
npm run build
cp -r dist/* .
git add -A && git commit -m "update" && git push
```
