# 🛠️ WorkBuddy 技能库 — 可直接用的 AI Agent 技能

> 一套围绕 **WorkBuddy / Coze / 虾评** 实战打磨的 AI Agent 技能集合，覆盖自动化、数据接入、浏览器采集、小程序全栈、Canvas 内容工厂、微信生态等场景。所有技能均附 `SKILL.md`，可被 Agent 直接加载执行。

- 公开技能仓：**17** 个（持续增加中）

## 目录

- [自动化 / RPA / 反检测](#自动化--RPA--反检测)

- [数据接入 / 导出 / 字段](#数据接入--导出--字段)

- [浏览器采集闭环](#浏览器采集闭环)

- [微信生态](#微信生态)

- [Canvas / PDF 内容工厂](#Canvas--PDF-内容工厂)

- [AI 协作 / 验收](#AI-协作--验收)

- [智能体互联](#智能体互联)


---

## 自动化 / RPA / 反检测

| 技能 | 说明 | 链接 |
|---|---|---|
| `stealth-browser-collector` | stealth-browser-collector orchestrator skill | [GitHub](https://github.com/shuangying0001-beep/stealth-browser-collector) |
| `browser-fingerprint-pool` | 爬虫/自动化 防封指纹伪装（UA+分辨率池）：随机真实浏览器指纹（88+ UA、87 分辨率）降低风控识别。适合爬虫工程师、RPA 开发者、海外社媒多账号。 | [GitHub](https://github.com/shuangying0001-beep/browser-fingerprint-pool) |
| `human-like-automation` | RPA 拟人化鼠标轨迹/打字（防机器人识别）：贝塞尔轨迹、随机延时、犹豫点击、逐字打字。适合 RPA 测试、批量操作防封。 | [GitHub](https://github.com/shuangying0001-beep/human-like-automation) |
| `playwright-stealth` | Playwright 反检测环境配置（去 webdriver 痕迹）：随机 UA/时区/语言、去自动化标志、模拟 Canvas/WebRTC 绕开反爬。适合爬虫、自动化测试。 | [GitHub](https://github.com/shuangying0001-beep/playwright-stealth) |

## 数据接入 / 导出 / 字段

| 技能 | 说明 | 链接 |
|---|---|---|
| `api-data-pipeline` | api-data-pipeline orchestrator skill | [GitHub](https://github.com/shuangying0001-beep/api-data-pipeline) |
| `parse-api-doc` | 接口文档转字段映射（ERP/OpenAPI 一键结构化）：把 API 文档解析成字段名/类型/必填/端点，直接出映射。适合对接第三方、低代码搭建。 | [GitHub](https://github.com/shuangying0001-beep/parse-api-doc) |
| `tabular-exporter` | 记录数据一键导出 Excel/CSV（带样式）：表头冻结、斑马纹、是/否，中文防乱码。适合运营报表、数据导出、日志归档。 | [GitHub](https://github.com/shuangying0001-beep/tabular-exporter) |
| `field-aligner` | 中英文字段名对齐映射工具：把杂乱字段名（中/英/驼峰/下划线）映射到规范 key，支持别名与模糊匹配。适合对接第三方接口、ERP 字段整理、数据清洗。 | [GitHub](https://github.com/shuangying0001-beep/field-aligner) |
| `config-merge` | 多环境配置合并校验工具（默认/系统/任务三层）：按优先级合并校验、自动修冲突、出 diff、可回滚。适合 dev/test/prod 多环境管理的后端与运维。 | [GitHub](https://github.com/shuangying0001-beep/config-merge) |
| `unit-converter` | 电商/物流规格单位换算（kg·cm·V·W）：把5kg 30cm这类带单位文本解析换算成标准单位。适合电商运营、物流报价、BOM 整理。 | [GitHub](https://github.com/shuangying0001-beep/unit-converter) |

## 浏览器采集闭环

| 技能 | 说明 | 链接 |
|---|---|---|
| `stealth-browser-collector` | stealth-browser-collector orchestrator skill | [GitHub](https://github.com/shuangying0001-beep/stealth-browser-collector) |

## 微信生态

| 技能 | 说明 | 链接 |
|---|---|---|
| `wechat-pay-integration` | 微信支付接入（JSAPI/Native/退款，含安全）：强制回调验签、幂等、密钥隔离。适合任何要收款的微信应用。 | [GitHub](https://github.com/shuangying0001-beep/wechat-pay-integration) |
| `wechat-notify` | 微信消息通知接入（企业微信机器人+公众号模板）：5 分钟接消息推送。适合任何需通知用户的微信应用。 | [GitHub](https://github.com/shuangying0001-beep/wechat-notify) |
| `miniprogram-ai-fullstack` | miniprogram-ai-fullstack orchestrator skill | [GitHub](https://github.com/shuangying0001-beep/miniprogram-ai-fullstack) |
| `miniprogram-canvas-verify` | 微信小程序 Canvas 预览与视觉验证 / 教备神器 Canvas 工具链：截图+区域裁剪+回归对比 | [GitHub](https://github.com/shuangying0001-beep/miniprogram-canvas-verify) |
| `wechat-miniprogram-devrules` | 微信小程序 AI 协作规范生成器（AGENTS.md）：生成安全/稳定/最小改动协作规范，一键出 AGENTS.md。适合带 AI 开发小程序的团队。 | [GitHub](https://github.com/shuangying0001-beep/wechat-miniprogram-devrules) |

## Canvas / PDF 内容工厂

| 技能 | 说明 | 链接 |
|---|---|---|
| `canvas-content-factory` | canvas-content-factory orchestrator skill | [GitHub](https://github.com/shuangying0001-beep/canvas-content-factory) |
| `canvas-grid-engine` | 字帖/作业纸生成器（米字格田字格13种）：一键生成可打印中文字帖与练习纸，支持汉字居中、拼音标注。适合书法练字、小学语文作业、早教字卡。 | [GitHub](https://github.com/shuangying0001-beep/canvas-grid-engine) |
| `canvas-multipage-pdf` | 学习资料/报告 一键导出可打印PDF：多页画布（字帖/作业纸/图表/报告）一键合成 A4 PDF，自动分页+页码。适合老师出卷、家长打印练字、开发者导出可视化报告。 | [GitHub](https://github.com/shuangying0001-beep/canvas-multipage-pdf) |
| `svg-to-canvas-replica` | SVG 图纸零误差转 Canvas（A4 印刷级）：A4 SVG 设计稿/工程图坐标文字样式零误差复刻到 Canvas，误差<0.001px。适合印刷打样、设计稿还原、报表导出。 | [GitHub](https://github.com/shuangying0001-beep/svg-to-canvas-replica) |

## AI 协作 / 验收

| 技能 | 说明 | 链接 |
|---|---|---|
| `ai-work-acceptance` | AI 产出验收清单生成器（四维度查错）：按功能/接口/安全/回归出可勾选验收清单。适合 code review、AI 外包验收。 | [GitHub](https://github.com/shuangying0001-beep/ai-work-acceptance) |
| `ai-project-wizard` | AI项目启动向导 - 从模糊想法到可执行施工策略包 | [GitHub](https://github.com/shuangying0001-beep/ai-project-wizard) |

## 智能体互联

| 技能 | 说明 | 链接 |
|---|---|---|
| `workbuddy-agent-card` | A2A Agent Card endpoint for WorkBuddy Skills Agent (A2A protocol 0.2) | [GitHub](https://github.com/shuangying0001-beep/workbuddy-agent-card) |

---

## 如何使用

1. 复制仓库里的 `SKILL.md` 到你的 Agent skills 目录（如 `~/.workbuddy/skills/`）。
2. 在 Agent 对话中直接描述任务，技能会被自动路由加载。
3. 部分技能依赖 Python/Node 运行时，按 `SKILL.md` 的 env 说明配置即可。

## 许可证

各技能以其仓库内 LICENSE 为准；索引仓内容采用 MIT。
