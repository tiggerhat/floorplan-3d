# 项目协作与发布

- 与用户交流时使用中文。
- 本项目的发布仓库是 `https://github.com/tiggerhat/floorplan-3d`（`origin`）；`wy51ai/floorplan-3d` 仅作上游参考，不向其推送或提交 PR，除非用户另行要求。
- 每次修改完成并验证后，提交并推送到 `origin/master`，等待 GitHub Pages 构建完成，再检查 `https://tiggerhat.github.io/floorplan-3d/` 是否包含本次变更。
- 如果本项目使用 Cloudflare Workers、KV 等服务，且本次修改涉及其代码、配置或数据，同步部署或更新相应资源并验证。当前项目没有 Cloudflare 配置；不要为此创建无关资源。
