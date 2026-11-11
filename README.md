# yanfei0725.github.io

GitHub Pages 用户级站点源码。发布到 <https://yanfei0725.github.io/>，作为该域名下的**中立索引页**，列出公开项目与文档入口。

## 文件

| 文件 | 作用 |
| --- | --- |
| `index.html` | 域根索引页（含 Schema.org `WebSite` JSON-LD） |
| `llms.txt` | 域名级站点摘要，给 crawler / agent 的诚实说明 |
| `robots.txt` | 爬虫策略，明确允许 AI / LLM 抓取器 |
| `sitemap.xml` | 本域名公开页面清单 |
| `.nojekyll` | 跳过 Jekyll 构建 |

## 边界

- 纯静态文档，**不提供** HTTP API、OpenAPI、MCP server、`ai-plugin.json` 或在线服务。
- 项目级文档站由 `yanfei0725/dsh-qwen-paint` 仓库的 `docs/` 目录发布到 `/dsh-qwen-paint/`，与本仓库相互独立。
- 插件本体运行在用户本机 DeepSeek Harness 进程内，运行时不访问本域名。

## 主要项目

[dsh-qwen-paint](https://github.com/yanfei0725/dsh-qwen-paint) · [项目文档站](https://yanfei0725.github.io/dsh-qwen-paint/)
