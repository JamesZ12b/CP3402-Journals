**16 / Nov / 2025**
**4:00PM - 9:00PM**
(Team stand-up, learning starter themes, initial custom theme setup)

### **Week 8 - WordPress: Developing Custom Themes**

**Learning Activities & Resources:**

This week's practical was the first full session dedicated to our group project (Assignment 2).

1.  **Team Stand-up Meeting:**
    * We held our first official stand-up meeting at the start of the prac.
    * As a team, we discussed our progress from Week 7 (reviewing client docs) and confirmed our roles.
    * I reported that I had no blockers and that my task for this week would be to research the starter theme and begin the initial theme setup.

2.  **Learning Starter Themes:**
    * The main requirement for Assignment 2 is to build a custom theme from a starter theme, not a child theme.
    * I spent time studying the recommended LinkedIn Learning course: **"WordPress: Building Themes from Scratch Using Underscores"** .
    * I also reviewed the **"DRY Development"** course to understand reusable code principles.

3.  **Initial Theme Development:**
    * Based on my learning, our team decided to use the **`_s` (Underscores)** starter theme due to its minimal, clean structure.
    * I downloaded a fresh copy of `_s` from `underscores.me` and named our new custom theme.
    * I set up this new theme in my local development environment (WPDistillery) and activated it.
    * I began the initial setup: editing `style.css` to add theme details, modifying `functions.php` to enqueue our own (currently empty) stylesheet, and planning the template files we'll need (`header.php`, `footer.php`, `front-page.php`).

4.  **Workflow & Documentation:**
    * I pushed this initial "skeleton" theme to our team's GitHub repository (`jcua-teamB`).
    * I updated my corresponding tasks on our Trello board, moving "Setup Starter Theme" from 'To Do' to 'Done'.

**Resources/Links:**
* LinkedIn Learning: WordPress: Building Themes from Scratch Using Underscores 
* LinkedIn Learning: DRY Development 
* `_s` (Underscores) Official Site: underscores.me
* Our Team GitHub Repository
* Our Team Trello Board

**Estimated Hours:**
5.0 hours (1.0 hour for team meeting & planning, 2.5 hours learning `_s`, 1.5 hours for local setup and first commit)

**Content Insights:**

The jump from a Child Theme (A1) to a Starter Theme (A2) is enormous. A child theme modifies, but a starter theme like `_s` is a true skeleton. It provides the essential WordPress template files and hooks, but absolutely no styling. This is far more complex but offers complete control over the final markup and design, which is essential for a professional, reusable theme. I learned that `functions.php` in a custom theme is the real "control center," managing everything from theme support (like post-thumbnails) to custom post types, which will be vital for our client's site.

**Career/Employability/Learning Insights:**

This week felt like a real-world development sprint.The stand-up meeting , though brief, was critical for accountability. It forced me to define a clear, achievable goal for the week ("Set up the starter theme and push to Git"). [cite_start]I am also seeing the full value of the local/staging/production workflow [cite: 474, 477-478]. [cite_start]My local environment [cite: 344-345] is my sandbox where I can set up and test the new `_s` theme without any risk. Pushing the first version to GitHub felt like establishing the "source of truth" for the rest of the team. This process (learn, set up locally, commit to version control) is a fundamental and highly employable development loop.
