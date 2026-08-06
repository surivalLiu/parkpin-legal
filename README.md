# PlacePark Legal Pages

English **Privacy Policy** and **Support** pages for App Store Connect.

## Public repo vs public file？

**必须把整个仓库设为 Public，不能只把某个文件设为公开。**

| 方式 | 是否可行 |
|------|----------|
| 仓库设为 **Public**，再开 GitHub Pages | ✅ 推荐（免费账号即可） |
| 仓库 **Private**，只公开某一个 HTML | ❌ GitHub 不支持「单个文件公开」 |
| 仓库 Private + GitHub Pages | ❌ 免费账号一般不可用；需付费计划 |

App Store 审核员打开的是 HTTPS 网页链接，不需要登录 GitHub。因此法律页所在仓库应保持 **Public**。

App 源码可以放在另一个 **Private** 仓库；法律页单独用本仓库（或本目录发布）即可。

---

## 本目录文件

| 文件 | App Store Connect |
|------|-------------------|
| `privacy.html` | **Privacy Policy URL** |
| `support.html` | **Support URL** |
| `index.html` | 可选首页 |
| `styles.css` | 样式（页面会引用，需一并上传） |
| `privacy.md` / `support.md` | Markdown 源稿（可选上传） |

**上传时请带上整个 `legal/` 目录里的 HTML + CSS**，不要只传一个 md。

---

## 推荐：单独公开仓库 `parkpin-legal`

适合：App 工程仓库想保持私有，法律页单独公开。

1. GitHub → **New repository**
   - Name: `parkpin-legal`
   - Visibility: **Public**（整仓公开）
   - 不要勾选「只加 README」也行，有空仓即可
2. 把本目录文件放到仓库**根目录**并 push，例如：
   - `privacy.html`
   - `support.html`
   - `index.html`
   - `styles.css`
3. 仓库 **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main`（或 `master`）
   - Folder: **/ (root)**
   - Save
4. 等待 1–2 分钟，浏览器打开：
   - `https://YOUR_GITHUB_USERNAME.github.io/parkpin-legal/privacy.html`
   - `https://YOUR_GITHUB_USERNAME.github.io/parkpin-legal/support.html`
5. 填入 App Store Connect：
   - Privacy Policy URL → 上面的 `privacy.html`
   - Support URL → 上面的 `support.html`

---

## 备选：跟 App 源码同一仓库一起上传

若你把 **整个** `park-pin-ios` 设为 Public，也可以：

1. 保留路径：`docs/legal/privacy.html` 等  
2. **Settings → Pages** → Branch `main` → Folder **/docs**  
3. URL 形如：
   - `https://YOUR_GITHUB_USERNAME.github.io/REPO_NAME/legal/privacy.html`
   - `https://YOUR_GITHUB_USERNAME.github.io/REPO_NAME/legal/support.html`

注意：这样会 **公开整个源码仓**，不只是法律页。若不想公开代码，请用上面的独立 `parkpin-legal` 方案。

---

## 自检

- [ ] 仓库 Visibility = **Public**
- [ ] Pages 已启用，链接用无痕窗口能打开（无需登录）
- [ ] `privacy.html` / `support.html` 样式正常（`styles.css` 已上传）
- [ ] 联系邮箱正确：`surival987@gmail.com`

Contact used on these pages: **surival987@gmail.com**
