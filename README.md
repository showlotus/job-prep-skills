# Job Prep Skills

求职技能集合，助力技术面试与简历优化。

## 📚 Skills 列表

### [Resume Optimizer](./resume-optimizer/) - 技术简历优化器 ✍️

将平淡的技术工作描述改写为符合大厂标准的专业简历要点。

**核心能力：**

- 强动词开头，提升表达力度
- 技术关键词优化，精准展示能力
- STAR 法则应用（情境-任务-行动-结果）
- 三种风格输出：标准专业版、数据驱动版、专家架构师版

**使用示例：**

```
"帮我优化这段项目经历"
"把这个技术描述改成简历语言"
```

**适用对象：** 后端/前端开发工程师、架构师、技术专家

---

### [Fresh Graduate Resume Optimizer](./fresh-graduate-resume-optimizer/) - 应届生简历优化器 🎓

专为校招求职者设计，将校园经历、实习经历、项目经验转化为专业、有竞争力的简历描述。

**核心能力：**

- 强动词开头，提升表达力度
- 量化成果展示（支持占位符提示）
- STAR 法则结构化描述
- 三版本输出：基础版、进阶版、高阶版
- 六大模块覆盖：教育背景、实习经历、项目经验、技能证书、校园活动、竞赛获奖

**使用示例：**

```
"帮我优化这段实习经历"
"把这个课程项目改成简历语言"
"优化我的社团活动描述"
```

**适用对象：** 准备校招的应届毕业生

---

### [Frontend Project Interview](./frontend-project-interview/) - 前端项目面试官 🎤

互联网大厂前端面试官角色，针对简历中的项目/工作经历进行阶梯式技术深挖，支持**辅导模式**提供实时反馈和改进建议。

**核心能力：**

- 简历分析与技术点识别
- 六级阶梯式提问（从项目背景到架构视野）
- 两种面试模式：严格面试模式 / 辅导模式（推荐）
- 动态追问技巧（根据回答质量调整深度）
- 实时反馈与优化建议
- 综合评价与提升路径

**使用示例：**

```
"帮我模拟一下前端面试"
"根据我的简历进行技术深挖"
"我想练习一下项目经历相关的面试题"
```

**适用对象：** 准备前端面试的开发者

---

### [Frontend Knowledge Interview](./frontend-knowledge-interview/) - 前端知识点面试官 📖

互联网大厂前端面试官，提供阶梯式技术提问、实时反馈和改进建议。覆盖 11 个技术分组、40+ 具体方向、三级难度。

**核心能力：**

- 11 大技术分组：基础、浏览器与网络、框架与原理、工程化、性能优化、安全、移动端、架构与设计、算法、Node.js、其他
- 40+ 具体技术方向：Vue、React、TypeScript、Webpack、微前端等
- 三级难度：初级（基础概念）、中级（原理理解）、高级（源码级）
- 专业评价与补充说明
- 持续面试模式

**使用示例：**

```
"我想练习 Vue 的面试题"
"考考我 React 原理相关的问题"
"帮我检验一下 JavaScript 基础"
```

**适用对象：** 想要系统性检验前端技术掌握程度的开发者

---

### [Frontend Scenario Interview](./frontend-scenario-interview/) - 前端场景题面试官 🧩

互联网大厂前端面试官，专注于主观场景题模拟面试，考察系统设计能力、问题解决思路和实战经验。

**核心能力：**

- 7 大场景类别：性能优化、架构设计、工程化、疑难问题排查、团队协作、AI 相关、职业发展
- 2-3 轮阶梯式追问，逐步深入考察
- 基于真实面经的场景题库
- 多维度评分：问题分析、方案设计、技术深度、表达逻辑
- 口语化回答示例与改进建议

**使用示例：**

```
"帮我练习性能优化场景题"
"我想做架构设计的场景面试"
"随机出一道场景题练练"
"根据当前项目经历模拟场景题面试"
```

**适用对象：** 准备前端面试，想提升场景题答题能力的开发者

---

## 💬 在任意 AI 对话工具中使用

每个技能目录下都有一个 `README.md` 文件，其中包含完整的提示词。你可以：

1. 打开对应技能的 `README.md` 文件
2. 复制 `---` 分隔线之后的代码块内容
3. 粘贴到任意 AI 对话工具（如 ChatGPT、Claude 网页版、DeepSeek、千问、智谱清言等）
4. AI 会自动扮演该技能角色，开始提供服务

**示例：**

```
# 在 ChatGPT 中使用简历优化器
1. 打开 resume-optimizer/README.md
2. 复制分隔线后的完整提示词
3. 发送给 ChatGPT
4. 然后输入你的技术描述，即可获得优化后的简历要点
```

**支持的平台：**

- ChatGPT
- Claude 网页版
- DeepSeek
- 千问
- 智谱清言
- 任何支持长文本的 AI 对话工具

---

## 🚀 安装（Claude Code 专用）

### 使用 skills CLI（推荐）

```bash
# 列出所有可用的 skills
npx skills add showlotus/job-prep-skills --list

# 安装特定 skill
npx skills add showlotus/job-prep-skills --skill resume-optimizer
npx skills add showlotus/job-prep-skills --skill fresh-graduate-resume-optimizer
npx skills add showlotus/job-prep-skills --skill frontend-project-interview
npx skills add showlotus/job-prep-skills --skill frontend-knowledge-interview
npx skills add showlotus/job-prep-skills --skill frontend-scenario-interview

# 安装所有 skills
npx skills add showlotus/job-prep-skills --skill '*'

# 指定安装到 Claude Code
npx skills add showlotus/job-prep-skills --skill resume-optimizer -a claude-code

# 全局安装（所有项目可用）
npx skills add showlotus/job-prep-skills --skill resume-optimizer -g
```

### 手动安装

```bash
# 克隆仓库
git clone https://github.com/showlotus/job-prep-skills

# 复制到项目的 .claude/skills 目录
cp -r job-prep-skills/resume-optimizer your-project/.claude/skills/
cp -r job-prep-skills/fresh-graduate-resume-optimizer your-project/.claude/skills/
cp -r job-prep-skills/frontend-project-interview your-project/.claude/skills/
cp -r job-prep-skills/frontend-knowledge-interview your-project/.claude/skills/
cp -r job-prep-skills/frontend-scenario-interview your-project/.claude/skills/
```

---

## 📁 项目结构

```
job-prep-skills/
├── README.md
├── resume-optimizer/                 # 简历优化工具
│   ├── SKILL.md                      # Claude Code 专用指令
│   ├── README.md                     # 通用 AI 对话提示词 ⭐
│   └── references/
│       ├── examples.md               # 优秀案例库
│       └── strong-verbs.md           # 强动词库
├── fresh-graduate-resume-optimizer/  # 应届生简历优化工具
│   ├── SKILL.md                      # Claude Code 专用指令
│   ├── README.md                     # 通用 AI 对话提示词 ⭐
│   └── references/
│       ├── campus-keywords.md        # 校园经历关键词库
│       ├── examples.md               # 优秀案例库
│       └── strong-verbs.md           # 强动词库
├── frontend-knowledge-interview/     # 前端知识点面试官
│   ├── SKILL.md                      # Claude Code 专用指令
│   └── README.md                     # 通用 AI 对话提示词 ⭐
├── frontend-project-interview/       # 前端项目面试官
│   ├── SKILL.md                      # Claude Code 专用指令
│   ├── README.md                     # 通用 AI 对话提示词 ⭐
│   └── references/
│       └── frontend-knowledge.md     # 前端知识点参考
└── frontend-scenario-interview/      # 前端场景题面试官
    ├── SKILL.md                      # Claude Code 专用指令
    └── README.md                     # 通用 AI 对话提示词 ⭐
```

> ⭐ `README.md` 文件包含完整的提示词，可在任意 AI 对话工具中直接使用

---

## 📖 资源

- [Claude Skills 官方文档](https://www.anthropic.com/news/skills)
- [Awesome Claude Skills](https://github.com/ComposioHQ/awesome-claude-skills) - 更多 skills 集合
- [创建自定义 Skills 指南](https://support.claude.com/en/articles/12512198-creating-custom-skills)
