# 🛡️ Universal Skill Auditor 

[中文文档向下滚动 | Scroll down for Chinese version](#-中文文档)

**The ultimate automated gatekeeper for your AI Agent ecosystem.** As LLMs and AI agents become deeply integrated into our daily workflows, executing third-party, prompt-based "skills" poses a silent but critical security risk. `skill-auditor` is a universal, platform-agnostic security tool designed to prevent malicious skills from overriding your system instructions, exfiltrating local data, or executing dangerous commands.

## ✨ Core Feature: Zero-Click Automatic Auditing

Top-tier security should be invisible. `skill-auditor` features a **fully automated interception mechanism**. 
Whenever a new skill or prompt-based program is installed or loaded into your workspace, `skill-auditor` instantly wakes up in the background. It scans the incoming logic and blocks threats before they can execute—**requiring absolutely no manual triggers or prompts from the user.**

## 🔍 The 6-Dimensional Security Check
Our auditor meticulously dissects any incoming skill across six critical vectors:
1. **Prompt Injection:** Detects attempts to overwrite core system instructions, jailbreak the AI, or alter foundational rules.
2. **File System Threats:** Flags unauthorized attempts to delete files or write to sensitive system paths.
3. **Network Exfiltration:** Blocks commands designed to secretly send your local data or environmental variables to external servers.
4. **Privilege Escalation:** Alerts you if a skill attempts to request `sudo` or administrator-level access.
5. **Social Engineering:** Identifies misalignments between what a skill *claims* to do and its *actual* hidden behavior.
6. **Stealth Behaviors:** Uncovers hidden instructions, encoded payloads (e.g., Base64), or malicious commands masked by excessive blank lines.

## 🚀 Usage

* **Automatic Mode (Recommended):** Do nothing! Just install or load your skills as usual. `skill-auditor` acts as a silent sentinel in the background.
* **Manual Mode:** You can explicitly trigger an audit by commanding your AI: *"Audit this skill"* or *"Run a security check on the newly downloaded tool"*.

---

# 🇨🇳 中文文档

**为你所有的 AI Agent 和大模型技能库打造的通用“门卫”。**

当我们把 AI 深度接入各类开发和业务工作流时，运行来源不明的第三方 Skill（提示词程序）会带来极大的安全隐患。`skill-auditor` 是一款打破平台壁垒的通用安全审计工具，专为拦截恶意指令、防止越权访问和保护本地数据而生。

## ✨ 核心亮点：全自动、无感知的安全审查

最好的安全工具是让用户感受不到它的存在。`skill-auditor` 拥有**全自动的静默拦截机制**。
无论是哪个平台的 Agent 框架，只要检测到有新的 skill 被安装或写入，审查程序就会在后台瞬间启动。它会在恶意代码生效前完成扫描并阻断威胁，**全程无需你开口下达任何指令**。

## 🔍 6 大核心审查维度
像“X光”一样透视每一个外来 Skill：
1. **提示词注入 (Prompt Injection)：** 严查是否试图覆盖核心系统指令、越狱 (Jailbreak) 或篡改底层规则。
2. **文件系统高危操作：** 拦截越权删除文件或向敏感系统路径写入的动作。
3. **网络数据外泄：** 防止本地代码、数据或环境变量被暗中打包发送到外部服务器。
4. **权限提升：** 警惕任何试图要求 `sudo` 或管理员权限的隐藏指令。
5. **社会工程学欺骗：** 核对 Skill 的“自我描述”与其“实际执行逻辑”是否一致，防止挂羊头卖狗肉。
6. **隐蔽恶意行为：** 揪出藏在大量空行后、或者经过 Base64 等编码伪装的恶意 Payload。

## 🚀 如何使用

* **全自动模式（推荐）：** 保持默认即可。当你导入或安装新 Skill 时，它会自动站岗放哨。
* **手动模式：** 随时向你的 AI 助手下达指令：*“审查这个 skill”* 或 *“帮我安全扫描一下刚下载的技能”*。
