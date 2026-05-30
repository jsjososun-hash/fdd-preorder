# 肥嘟嘟预订单

这是一个可直接部署到 GitHub Pages 的单页预订单工具。

## 功能

- 录入订单
- pushplus 微信推送
- 订单统计图表
- 订单筛选
- 产品编辑
- CSV 导出

## 部署

把本目录中的 `index.html` 放到 GitHub 仓库根目录，然后在仓库设置中开启 GitHub Pages。

注意：当前版本为了方便使用，pushplus token 写在前端代码中。公开部署后，懂技术的人可以从源码中看到 token。更安全的做法是后续加一个后端代理，由服务器保存 token。
