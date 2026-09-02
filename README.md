# video-music-replace

营销视频音乐使用与替换产品 Demo。

## 目录

- `index.html`：总入口
- `product/`：完整产品页面
  - `home.html`：首页
  - `video-tasks.html`：视频任务列表
  - `new-video-task.html`：新建视频任务
  - `task-detail.html`：视频任务详情 / 授权校验
  - `music-library.html`：商用音乐库
  - `approvals.html`：待办确认
  - `usage-records.html`：音乐使用记录
- `demo/marketing-video-music-replace-demo.html`：最小可演示 Demo

## 最小 Demo 流程

上传营销视频 → 识别视频中的音乐 → 选择可商用替换音乐 → 一键重新合成 → 页面展示新视频。

当前最小 Demo 为前端交互演示，音乐识别和视频合成过程使用模拟逻辑；接入真实能力时可分别对接音乐识别 API、音乐文件服务和 FFmpeg 合成服务。
