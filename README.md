# awilonk.github.io

Personal academic homepage — single static page, no build step.

## 结构
- `index.html` — 全部内容 + 内嵌 CSS 都在这一个文件里，改文字直接改它
- `assets/img/` — 图片
  - `profile.jpg` ← **待放**：你的头像
  - `plane.jpg / sitl.png / los.png / flight.png / pov.gif / wind.png` — 图墙（目前是仿真图，可换实拍）

## 本地预览
```bash
cd awilonk.github.io
python -m http.server 8899
# 浏览器打开 http://localhost:8899
```

## 部署到 GitHub Pages
已确认使用账号 `awilonk`（该账号已有 70 个公开仓库，name 已填 Yaokun Lu）。
仓库名必须是 `awilonk.github.io`，站点地址 https://awilonk.github.io 。

```bash
cd awilonk.github.io
git init
git add .
git commit -m "New homepage"
git branch -M main
git remote add origin https://github.com/awilonk/awilonk.github.io.git
git push -u origin main
```
仓库名必须正好是 `awilonk.github.io`。推上去后 GitHub 自动开 Pages，
几分钟后访问 https://awilonk.github.io 。
（如需手动开：仓库 Settings → Pages → Source 选 `main` 分支根目录。）

## 让 Google 能搜到你（SEO）
页面内 SEO 已做好：`<title>`/description/canonical/Open Graph + JSON-LD 结构化数据（Person）+ `sitemap.xml` + `robots.txt`。
**排名真正靠的是外链权重**，下面几步你上线后做：

1. **Google Search Console**（最关键）：https://search.google.com/search-console
   加 `https://awilonk.github.io/` → 用 HTML 标签法验证（把它给的 `<meta name="google-site-verification">` 贴进 index.html 的 `<head>`）→ 提交 `sitemap.xml` → 点 "请求编入索引"。这是主动让 Google 来收录，最快。
2. **各平台挂主页链接**（给 Google 可信的爬取路径，也是金豆排第一的真正原因）：
   - Google Scholar 个人资料 → Homepage 填 `awilonk.github.io`
   - GitHub 个人 bio → 填主页
   - ORCID / DBLP / ResearchGate 资料页 → 填主页
   - 实验室主页、合作者页面 → 请他们链一下你
3. **补齐 JSON-LD 里的 `sameAs`**：把 Scholar / ORCID / DBLP 链接加进 index.html 的 `<script type="application/ld+json">` 的 `sameAs` 数组，Google 会据此把这些身份和网页绑成同一个人（有机会出知识面板）。
4. **名字一致**：所有平台统一用 `Yaokun Lu` / `卢耀坤`。搜 `luyaokun` 好排（够独特）；搜 `Yaokun Lu` 慢些（会重名），靠上面外链累积权重。
5. **耐心**：新站收录到能搜到通常几天～几周。

## 待补充清单
- [ ] `assets/img/profile.jpg` 头像
- [ ] Google Scholar / CV 链接（index.html 顶部 `.links` 里的 `href="#"`）
- [ ] 在投论文标题（可公开的逐条填进 Publications）
- [ ] SIYI ZT6 吊舱、真机实飞照片替换图墙
- [ ] 核对硕士期间"烟条检测"专利是否署名（存疑，暂标问号）
