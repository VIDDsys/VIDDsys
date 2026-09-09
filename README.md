# VIDDsys

独立开发者。围绕「自托管 + AI 工程化」构建了一条完整的产品线：从底层基础设施，到模型接入层，再到面向用户的教程内容——三者共享同一套架构与设计理念。

<div align="center">

**[主站](https://viddsys.com)** · **[AI 网关](https://api.viddsys.xyz)** · **[AI 学习](https://viddsys.xyz/learn/)**

</div>

---

## 产品线

三个产品不是孤立的工具，而是一条自上而下的链路：

### AI 网关 → [api.viddsys.xyz](https://api.viddsys.xyz)

多模型 API 网关，提供 OpenAI 兼容接口。统一鉴权、额度与计费，上层应用无需关心底层模型差异。

### AI 学习 → [viddsys.xyz/learn](https://viddsys.xyz/learn/)

一套完整的 AI Agent 教程，从核心概念讲到浏览器自动化与批量任务实战。教程中的示例直接基于自建的网关，学与用是同一套东西。

### 个人主站 → [viddsys.com](https://viddsys.com)

承载以上所有服务的平台：工具集、社区、资讯聚合与内容分发。云端与本地双节点部署，静态内容经 CDN 分发。

## 工程实践

- **架构**：单机高密度部署，Nginx 统一调度多站点，节点间可互为镜像
- **AI 工程**：模型路由、限流与用量治理；Agent 工作流与工具协议（MCP）落地
- **交付**：所有站点原子化发布，自动回滚，构建即验证

---

<div align="center">

如果这些内容对你有用，欢迎 Star 与交流。

</div>
