# TOEFL Spelling Trainer

GitHub Pages 版个人错题训练网页。

## 发布
1. 新建 GitHub 仓库，例如 `toefl-trainer`
2. 上传 `index.html`
3. Settings → Pages
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`，目录选择 `/(root)`
6. 保存后使用 GitHub Pages 提供的固定网址

## 学习记录
- 每次“批改”会自动写入浏览器 localStorage
- 存储键固定为 `toefl-spelling-trainer-v5`
- 顶部“保存记录”会同时：
  1. 保存到当前浏览器
  2. 下载 JSON 备份
- 更新题库时覆盖同一个 `index.html`，不要更改网站域名/仓库路径
- 换设备时请用“导入备份”恢复
