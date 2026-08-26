# Multi-Agent-APP

Multi-Agent-APP 是一个由多个专业 Agent 协作，将 Idea 推进为可运行、可测试、可发布产品的项目框架。

## V0.1 架构

- `agents/`：专业 Agent 定义
- `shared/`：共享知识、技能、工具和规范
- `runtime/`：任务规划、执行、上下文、记忆和状态管理
- `workflows/`：跨 Agent 协作流程
- `evals/`：Agent、Artifact、Workflow 和系统评估
- `projects/`：实际开发项目
- `.cursor/`：Cursor 执行适配层
- `.github/`：GitHub 协作配置

V0.1 中，Orchestrator 作为 Runtime 层的协同调度能力存在，不单独定义为业务 Agent。

## 当前状态

当前版本仅搭建项目骨架，并完成 Product Agent 的初始定义。

