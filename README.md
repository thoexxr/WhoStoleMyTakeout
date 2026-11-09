# appstore-site · 上传到 GitHub Pages

这个目录里是三个静态页面，直接传到 GitHub 仓库根目录即可：

| 文件 | 用途 | 填到 App Store Connect 的位置 |
|---|---|---|
| `index.html` | 落地页（可选，避免根地址 404） | 不用填 |
| `support.html` | 技术支持页 | App 信息 → 一般信息 → **支持网址** |
| `privacy.html` | 隐私政策页 | 版本页 → App 隐私 → **隐私政策网址** |

## 上传步骤

1. GitHub 新建一个 **public** 仓库，例如 `who-stole-my-takeout-site`。
2. 把本目录下的 `index.html`、`support.html`、`privacy.html` 三个文件传到仓库根目录（Add file → Upload files，拖进去即可）。
3. 仓库 **Settings → Pages**：Source 选 `Deploy from a branch`，Branch 选 `main`、目录 `/ (root)`，Save。
4. 等 1–2 分钟，地址形如：

```
https://<你的GitHub用户名>.github.io/who-stole-my-takeout-site/support.html
https://<你的GitHub用户名>.github.io/who-stole-my-takeout-site/privacy.html
```

5. 用浏览器打开两个链接，确认能正常显示、语言切换（简/繁/EN/日/한）都能点，再填进 ASC。

## 注意

- 仓库必须是 public，否则 Pages 不能公开访问、ASC 校验会失败。
- 隐私政策和支持网址一旦提交，审核期间不要删除或改路径。
- 页面里的联系邮箱已经是 `xingran0720@gmail.com`（原样写进了 5 种语言）。
