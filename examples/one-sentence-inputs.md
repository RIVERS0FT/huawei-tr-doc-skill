# 一句话输入示例

本文件展示如何用一句话触发不同 TR 阶段的设计文档生成。

## TR1：产品概念与可行性设计

```text
生成 TR1 设计文档：开发一个多 Agent 网络通信仿真平台，用于模拟 agent 间消息流转、日志追踪和拓扑回放。
```

适合场景：项目想法、立项、概念方案、可行性分析。

## TR2：需求分解与规格设计

```text
生成 TR2 设计文档：为 AgentNetworkSimulation 设计需求规格，支持 session_id、trace_id、channel_id 和 agent 间消息记录。
```

适合场景：需求拆解、规格定义、验收标准、需求追踪矩阵。

## TR3：总体方案与概要设计

```text
生成 TR3 设计文档：AgentNetworkSimulation 采用 message bus 连接多个 agent，支持 HTTP 消息转发、统一日志和拓扑回放。
```

适合场景：系统架构、模块划分、概要设计、技术路线。

## TR4：详细设计与模块设计

```text
生成 TR4 设计文档：为 AgentNetworkSimulation 设计统一日志事件模型，字段包括 timestamp、event_id、session_id、trace_id、component、event、level、agent_from、agent_to。
```

适合场景：接口设计、数据结构、异常处理、日志字段、模块详细设计。

## TR5：集成验证与测试设计

```text
生成 TR5 设计文档：为 AgentNetworkSimulation 设计集成验证方案，覆盖正常消息流、超时、重试、异常返回和日志追踪完整性。
```

适合场景：测试方案、验证场景、质量门禁、缺陷闭环。

## TR6：发布交付与运维设计

```text
生成 TR6 设计文档：将 AgentNetworkSimulation 以 Docker Compose 方式交付，支持日志查看、配置管理、版本回滚和基础运维监控。
```

适合场景：发布方案、交付方案、运维方案、回滚方案。

## 推荐格式

```text
生成 <TR阶段> 设计文档：<项目名称>，用于<目标>，支持<核心能力>，要求<关键约束>。
```
