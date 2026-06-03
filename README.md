# 新疆钧仪衡环境技术有限公司 3D 环视页面

这是用于 GitHub Pages 发布的静态页面版本。

## 文件说明

- `index.html`：网页入口文件，GitHub Pages 会默认访问这个文件。
- `.nojekyll`：禁用 Jekyll 处理，避免静态资源路径被误处理。

## 发布前必须修改

请在 `index.html` 中将下面两处 `您申请的key值` 替换为你的高德 Web JS API Key：

```html
<script src="https://webapi.amap.com/maps?v=2.0&key=您申请的key值"></script>
<script src="https://webapi.amap.com/loca?v=2.0.0&key=您申请的key值"></script>
```

## GitHub Pages 发布方式

1. 新建一个 GitHub 仓库，例如：`junyiheng-3d-view`。
2. 上传本文件夹内全部文件到仓库根目录。
3. 打开仓库 `Settings` → `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ root`。
6. 保存后等待 GitHub Pages 发布完成。

发布后的访问地址通常为：

```text
https://你的GitHub用户名.github.io/junyiheng-3d-view/
```
