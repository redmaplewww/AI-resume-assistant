# AI简历助手

一个面向技术岗位的 Codex 简历写作教练 Skill。

它不会从零代写简历，而是通过逐段提问、证据整理、可信度检查和局部修改，引导用户完成自己的简历。全部文字经用户确认后，可以继续进行版式整理并生成最终 PDF。

## 核心原则

- 不从空白页面生成完整简历或项目经历。
- 没有用户原文时，只提供高层结构和少量引导问题。
- 每次只处理一个小节或少量相关条目。
- 局部修改只能使用用户原文和已确认事实。
- 不虚构指标、职责、技术栈、业务背景或因果关系。
- 最终内容必须可追溯为用户原写或用户确认过的局部修改。
- 支持岗位定位、项目叙事、可信度审查、JD 映射和最终 PDF 制作。

## 仓库结构

```text
skills/
  write-impactful-tech-resume/
    SKILL.md
    agents/openai.yaml
    references/
```

## 安装

将 `skills/write-impactful-tech-resume` 目录复制到：

```text
$CODEX_HOME/skills/write-impactful-tech-resume
```

未设置 `CODEX_HOME` 时，通常使用：

```text
~/.codex/skills/write-impactful-tech-resume
```

## 使用示例

```text
使用 $write-impactful-tech-resume 引导我逐段完成技术简历。不要从零生成内容，先从最重要的项目开始提问。
```

## 内容

- 技术简历逐段写作流程
- 应用、Agent Infra 与算法岗位定位
- 项目需求与技术选型叙事
- 指标基线与可信度检查
- 历史反面模式审查规则
- 40 分质量评分体系
- 用户确认后的最终 PDF 生成规则
