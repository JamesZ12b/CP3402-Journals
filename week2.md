**Week 2: Overview of CMSs**

**Date:** 28/September/2025

**Learning Activities & Resources:**

* This week, I focused on setting up my first dynamic website using the Joomla CMS, hosted on SiteGround.
* Learned the process of creating "Articles" in Joomla and migrating the content from my static HTML files (`index.html`, `projects.html`) into the CMS structure.
* Studied how to create and manage "Menu Items" to make the articles visible on the website's front-end.
* Explored the Cassiopeia template's settings, attempting to customize the site's appearance.
* Spent significant time troubleshooting CSS application issues, which involved learning to use the browser's "Inspect Element" developer tool to find the correct CSS selectors for the site title.
* Learned the correct method for adding custom styles to the Cassiopeia template by creating and editing a `user.css` file.

**Resources/Links:**

* My Joomla Website: `https://kaixinz2.sg-host.com/`
* Joomla Documentation on Templates
* Browser Developer Tools (MDN Docs)

**Estimated Hours:**

Approximately 7 hours spent on setting up Joomla, migrating content, troubleshooting, and journaling.

**Content Insights:**

* I learned that a CMS like Joomla fundamentally separates content (Articles), structure (Menu Items), and presentation (Templates). You don't just upload HTML files; you input content into a database, and the template displays it.
* Pasting HTML directly into the default WYSIWYG editor can cause issues. The editor often cleans the code, displaying it as plain text. The solution is to switch to the "code" or "toggle editor" mode before pasting HTML.
* Joomla's caching system is aggressive. Changes made in the backend (like hiding a page title) might not appear on the live site until the cache is manually cleared (`System` > `Clear Cache`). This is a critical troubleshooting step.
* The Cassiopeia template uses a specific file, `user.css`, for custom styles. This is a best practice as it prevents custom code from being overwritten during template updates. This file needs to be manually created in the template's `css` directory.

**Career/Employability/Learning Insights:**

This week was less about straightforward learning and more about practical problem-solving, which I feel is a crucial skill for any IT career. When the CSS didn't apply, I couldn't just follow a tutorial; I had to adopt a methodical troubleshooting process. Learning to use the "Inspect Element" tool felt like gaining a superpower – I can now see the exact structure of any website and understand why my styles aren't working. This is a skill I will use constantly in any future web development role. This experience taught me that in development, things rarely work on the a first try, and the real skill lies in patiently diagnosing and solving the problem.
