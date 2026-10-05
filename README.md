# EventPilot v3.0

**多单位全场景事件冲突与归档系统 · 交互原型**

EventPilot 以事件为中心，探索将事件信息、冲突提示、规则配置、关联分析与归档流程汇集到统一工作台。适合用于作品展示、产品方案交流和现场演示。

## 在线体验

启用 GitHub Pages 后，可在仓库的 **Settings → Pages → Visit site** 打开网站并复制分享链接。首页为作品介绍，点击「立即体验作品」进入完整 Demo。

## 场景与模块

支持切换七类预设单位：政务服务、公安、检察院、法院、监狱、医院、学校。

| 页面 | 展示内容 |
| --- | --- |
| 架构总览 | 产品分层与整体设计 |
| 指挥台 | 事件指标、趋势、时间线与待办展示 |
| AI监控预警 | 监控与告警界面设计 |
| 人员轨迹 | 人员、区域与设备相关界面 |
| 事件档案库 | 事件列表、详情、状态、证据与记录展示 |
| 规则配置 | 各单位预设业务规则展示 |
| 数据源接入 | 业务库、工单、消息流等接入方案展示 |
| 关联图谱 | 事件关联关系展示 |
| 归档工作台 | 归档流程界面设计 |

## 建议体验顺序

1. 打开架构总览，了解设计思路。
2. 进入指挥台，查看当前单位的指标和事件。
3. 在事件档案库打开事件详情。
4. 使用右上角单位切换器，对比不同场景。
5. 浏览规则配置、关联图谱和归档工作台。

## Demo 边界

这是 HTML、CSS、原生 JavaScript 构成的静态前端原型，无需安装依赖或启动后端。数据预置在页面中；AI识别、监控、轨迹、法规校对、数据接入、材料预览和归档等不代表已接通真实服务。部分操作仅展示界面或提示，状态不持久保存。示例业务规则用于说明产品设计。

## 本地查看

直接双击 `index.html` 查看介绍，双击 `demo.html` 查看原始演示。原演示引用 Google Fonts；字体服务不可访问时使用系统字体。

## 发布到 GitHub Pages

1. 在 GitHub 创建名为 `eventpilot` 的公开仓库。
2. 将本文件夹内的 `index.html`、`demo.html`、`README.md` 等文件上传至仓库根目录，不要上传 ZIP 本身。
3. 打开 **Settings → Pages**。
4. Source 选择 **Deploy from a branch**，Branch 选择 **main**，目录选择 **/ (root)**，点击 **Save**。
5. 等待部署完成，在 Pages 页面点击 **Visit site**。网站通常为 `https://你的用户名.github.io/eventpilot/`，以 GitHub 实际显示的地址为准。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 文件结构

```text
index.html   作品介绍首页
demo.html    原始交互演示
README.md    GitHub 项目介绍与发布说明
.nojekyll    静态文件发布标记
```

后续方向：接入身份认证、权限控制、持久化存储、真实事件数据与后端服务，逐步将界面原型转化为完整应用。