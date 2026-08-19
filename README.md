# Yuxin's Life Lab

私人生活管理系统，支持任务、四个房间、日记、经验值、周日历与周复盘。

## 发布前配置

打开 `config.js`，只填写 Supabase 的 Project URL 与 Publishable key。不要填写 Secret key、Service role key 或数据库密码。

## GitHub Pages

把本目录中的全部文件上传到仓库根目录，再在仓库 Settings → Pages 中选择从 `main` 分支根目录发布。

## 免费 AI 流程

日记页面的“复制给 AI 整理”不会调用付费接口，只会把整理好的提示词复制到剪贴板，由用户自行粘贴到免费的 ChatGPT 或 DeepSeek。
