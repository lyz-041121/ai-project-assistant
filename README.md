# AI 项目助理工作台 (ai-project-assistant)

> 面向总经理室 AI 项目助理岗位的标准化工作流 Skill，覆盖 AI 工具调研、项目跟进、数据分析、跨部门沟通、营销辅助五大核心工作流。

## 功能特性

- **5 大工作流**：每个工作流包含触发场景、交付物定义、操作步骤、模板参考、关键要点、自检清单
- **5 套专业模板**：调研报告、项目周报、数据分析报告、沟通模板库、营销辅助指南
- **即插即用**：安装后直接用自然语言调用，AI 自动匹配对应工作流和模板
- **跨平台兼容**：支持豆包 AI 助手、DeepSeek（TUI/Harness）、Claude Code 等支持 Skill 标准的 Agent 平台

## 覆盖的工作流

| 工作流 | 适用场景 | 产出物 |
|--------|---------|--------|
| 1. AI 工具调研与对比 | 调研/选型/评估 AI 工具 | 完整调研报告（含实测、SWOT、落地路径、ROI） |
| 2. 项目进度跟踪与简报 | 周报/专题简报/进展同步 | 项目周报、里程碑跟踪、风险预警 |
| 3. 数据分析报告 | 使用数据分析/效果评估 | 多维分析报告、洞察提炼、行动建议 |
| 4. 跨部门沟通协调 | 邮件/消息/会议纪要/问题升级 | 5 类邮件模板 + 5 类即时消息话术 |
| 5. 营销业务辅助 | 文案/竞品/客户/活动 | 4 类文案模板 + 竞品分析 + 客户跟进 + 活动方案 |

## 安装方法

### DeepSeek-TUI

```bash
/skill install github:你的用户名/ai-project-assistant
```

安装后重启 DeepSeek-TUI 即可生效。

### DeepSeek Harness (dsh)

```bash
# 全局安装
git clone https://github.com/你的用户名/ai-project-assistant.git ~/.dsh/skills/ai-project-assistant

# 或按项目安装
git clone https://github.com/你的用户名/ai-project-assistant.git .dsh/skills/ai-project-assistant
```

### 豆包 AI 助手

将本仓库的 `ai-project-assistant` 文件夹复制到：

```
C:\Users\你的用户名\AppData\Local\Doubao\User Data\Default\.doubao\agent_mode\workspace\.user_skills\
```

重启豆包客户端即可。

### Claude Code / 其他支持 Skill 的 Agent

将仓库放入对应平台的 skills 目录即可，标准 `SKILL.md` 格式通用。

## 使用方法

安装后直接用自然语言描述需求，AI 会自动匹配工作流：

```
"帮我调研一下 AI 视频生成工具，对比 DORA、可灵、即梦"
"写一份本周 AI 项目周报"
"帮我写一封邮件，让 IT 部配合接口对接"
"根据这些使用数据做一份分析报告"
"帮我写一篇小红书种草文案"
```

## 目录结构

```
ai-project-assistant/
├── SKILL.md                          # 主文档：5 大工作流的操作步骤与自检清单
├── README.md                         # 本文件
└── references/
    ├── ai-tool-research-template.md  # 模板一：AI 工具调研对比报告
    ├── project-briefing-template.md  # 模板二：项目周报 + 专题简报
    ├── data-report-template.md       # 模板三：数据分析报告
    ├── communication-templates.md    # 模板四：跨部门沟通模板库
    └── marketing-assist-guide.md     # 模板五：营销业务辅助指南
```

## 实际产出示例

使用本 Skill 的"工作流一：AI 工具调研与对比"，可产出约 9000 字的完整调研报告，包含 15 维度对比矩阵、3 场景实机测试、SWOT 分析、落地路径、成本估算与 ROI 测算。

## 许可证

MIT License

## 作者

Created with ❤️ for AI Project Assistant role.
