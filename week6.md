**27 / Oct / 2025**
**6:00PM - 10:30PM**
(Troubleshooting Slack, setting up Trello/GitHub, and integrating tools)

### **Week 6 - Project/client introduction, group project management**

**Learning Activities & Resources:**

本周的目标是为大型团队项目设置协作工具。

1.  **遭遇的第一个障碍 (Slack):**
    * 根据指南，我应该已经被添加到了一个私有的Slack频道。但我检查后发现，我**没有**被添加到任何频道，并且也无法联系到我的任何组员。
    * **解决方案:** 我主动联系了导师，并提供了我的情况截图。我得到了**明确的许可**，可以“create new slack and start the group assignment” (创建新的Slack并开始小组作业)。
    * 因此，我创建了一个全新的Slack工作区，命名为 `CP3402-GroupB`。

2.  **设置 Trello (项目规划):**
    * 我访问了指南中提供的Trello模板链接 (`.../web-project-dev-template`)。
    * 我复制了该看板，将其命名为 `CP3402-GroupB`，并设置为“公开”。
    * 由于组员缺席，我**独自**打开了 “Group Agreement & Contacts” 卡片，并根据项目指南 (`CP3402-2025-Project.pdf`) 的新要求，填写了**我自己的**角色、技能评估（Skills Assessment）和“拟议的”(Proposed)团队沟通协议。

3.  **设置 GitHub (版本控制):**
    * 我访问了课程提供的GitHub Classroom链接 (`.../6bHRbpaJ`)。
    * 根据项目指南的命名规范（`[校区]-[团队ID]`），我将仓库命名为 `jcu-teamB`（而不是Slack的名字）。
    * 我创建了一个 `README.md` 文件并完成了**首次 commit**，以满足本周的提交要求。

4.  **集成工具 (核心挑战):**
    * **GitHub 集成:** 当我尝试在我的新Slack频道中运行指南里的 `/github subscribe ...` 命令时，Slack返回了“/github非有效命令”的错误。
    * **诊断与解决:** 我意识到，指南的命令是为*已经安装了应用的*官方工作区准备的。在我这个**全新的空工作区**里，我必须先**手动安装 "GitHub" 应用**。安装并授权后，`/github subscribe ...` 命令才
