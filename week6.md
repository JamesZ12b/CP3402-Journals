**27 / Oct / 2025**
**6:00PM - 10:30PM**
(Troubleshooting Slack, setting up Trello/GitHub, and integrating tools)

### **Week 6 - Project/client introduction, group project management**

**Learning Activities & Resources:**

This week's objective was to set up the collaborative toolset for the major group project.

1.  **Obstacle 1 (Slack):**
    * According to the guide, I should have already been added to a private Slack channel. After checking, I could not find this channel. I was also unable to establish contact with any of my assigned teammates.
    * **Solution:** I proactively contacted my tutor, providing a screenshot of my situation. I received explicit permission to "create new slack and start the group assignment".
    * Following this, I created a new, private Slack workspace named `CP3402-GroupB`.

2.  **Setting up Trello (Project Planning):**
    * I accessed the Trello template link provided in the guide (`.../web-project-dev-template`).
    * I copied the board, named it `CP3402-GroupB`, and set its visibility to "Public" as required.
    * With teammates unavailable, I **independently** began filling out the "Group Agreement & Contacts" card. I based my entries (especially the "Skills Assessment") on the new, more demanding requirements of the final project (`CP3402-2025-Project.pdf`), not Assignment 1.

3.  **Setting up GitHub (Version Control):**
    * I followed the GitHub Classroom link (`.../6bHRbpaJ`) provided in the project guide.
    * Following the specific naming convention (`[campus]-[teamID]`), I named the repository `jcu-teamB`.
    * I made the **first commit** (creating a `README.md`) to satisfy the week's deliverable.

4.  **Integrating Tools (Core Challenge):**
    * **GitHub Integration:** When I ran the guide's command `/github subscribe ...` in my new Slack channel, it failed with a "/github is not a valid command" error.
    * **Diagnosis & Solution:** I realized the guide's command was for the *official* JCU workspace, which has the app pre-installed. In my **new, blank workspace**, I had to go to the App Directory and **manually install the "GitHub" app**. After authorizing it, the `/github subscribe` command worked perfectly.
    * **Trello Integration:** Similarly, the `/trello link ...` command failed, stating "This Slack workspace is not linked to a Trello workspace."
    * **Diagnosis & Solution:** I read the error message, followed the link it provided (`trello.com/platforms/slack`), and authorized my new Slack workspace from my **Trello account's admin settings**. After Trello approved the connection, I returned to Slack and the `/trello link` command succeeded.

**Resources/Links:**
* [cite_start]CP3402 Weekly Practical Guide (Week 6) [cite: 381-404]
* [cite_start]CP3402 Project Guide (for GitHub naming conventions and new project requirements) [cite: 90-93, 167-330]
* Slack App Directory (for installing GitHub and Trello)
* Trello Workspace Slack Integration Settings page

**Estimated Hours:**
4.5 hours (A significant portion was spent diagnosing and solving the unexpected Slack creation and integration issues).

**Content Insights:**

I now have a deep understanding of the **synergy** between these tools. Trello is not just a to-do list; it establishes the project's "rules" via the "Group Agreement" card. GitHub is where the "work" is executed. [cite_start]The purpose of the Slack integration [cite: 393-394] is to pipe all **notifications** from both "planning" (Trello) and "execution" (GitHub) into a single, real-time feed. This allows a team (or in this case, just me) to see all project-related activity without context-switching between three different apps.

**Career/Employability/Learning Insights:**

The most valuable lesson this week came not from following the guide, but from when the **guide failed**. [cite_start]The instructions (`/github subscribe`) [cite: 401-402] were technically **incorrect** for my (tutor-approved) situation.

Instead of getting stuck, I:
1.  **Communicated Proactively:** When I had the initial channel and teammate problem, I didn't wait. I contacted my tutor and got a new path forward.
2.  **Diagnosed the Root Cause:** Faced with the "/github not valid" error, I correctly diagnosed the root cause as "app not installed" in a blank workspace.
3.  **Solved the Problem:** Faced with the Trello "workspace not linked" error, I read the error message and solved the authorization issue from Trello's side.

This ability to "problem-solve when the manual is wrong" by analyzing error messages and understanding the underlying system is a far more valuable real-world skill than simply "following instructions."
