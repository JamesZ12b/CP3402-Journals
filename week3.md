**Week 3: WordPress: installation, settings, content, navigation, using themes and plugins**

**Date:** 05/October/2025

**Learning Activities & Resources:**

This week was dedicated to building the second required website for my "Archivio" startup project, this time using WordPress. The process involved several key learning activities.

Initially, I encountered a significant roadblock with my hosting provider, SiteGround. My "StartUp" plan was limited to a single website, which was already occupied by my Joomla installation. After exploring alternatives, I made the decision to upgrade my hosting plan to "GrowBig," which supports unlimited websites. This was a practical lesson in understanding hosting limitations and resource planning.

With the hosting issue resolved, I used the SiteGround installer to set up a fresh WordPress instance on a temporary domain. I then began the process of migrating content from my previous site. I learned that in WordPress, static content like a homepage or an 'About Us' page is created using "Pages," whereas "Posts" are typically used for blog entries. This is a key conceptual difference from Joomla's more unified "Article" system.

To add my custom HTML structure, I had to learn the basics of the modern WordPress block editor (Gutenberg). I discovered the "Custom HTML" block, which allowed me to paste the code for my hero section and project cards directly onto the page. This was a different workflow compared to Joomla's editor, which required toggling a "code view" mode.

After creating all the necessary pages (Home, Projects, Our Team), I navigated to the "Appearance" > "Menus" section to build the site's main navigation. I learned how to create a menu, add my newly created pages to it, and assign it to the "Primary Menu" location to make it appear in the theme's header. I also configured the homepage to be a static page via the "Settings" > "Reading" panel, pointing it to my "Home" page.

Finally, I explored the WordPress theme repository and selected the "Twenty Twenty-Five" theme. The most challenging part was applying my custom CSS. Unlike Joomla's `user.css` file, WordPress's modern block themes hide this feature. After some investigation, I learned that the "Additional CSS" section can be accessed through a hidden menu in the Site Editor's "Styles" panel, or more reliably by using a direct link to the classic Customizer (`/wp-admin/customize.php`). Pasting my CSS code there successfully applied my custom design to the new WordPress site.

**Resources/Links:**

* My New WordPress Website: https://kaixinz3.sg-host.com/
* My Joomla Website (for content reference): `https://kaixinz2.sg-host.com/`
* WordPress Documentation on the Site Editor

**Estimated Hours:**

10 hours. This includes time spent resolving the hosting plan issue, installing and configuring WordPress, migrating all content, troubleshooting the CSS customization, and writing this journal entry.

**Content Insights:**

* **Hosting Plans Matter**: I learned a valuable, practical lesson that entry-level hosting plans often have significant limitations (like the number of websites allowed), which must be considered when planning projects that require multiple sites.
* **WordPress vs. Joomla Terminology**: The core concepts are similar, but the names are different. Joomla's "Articles" are roughly equivalent to WordPress's "Pages" for my use case. Joomla's "Templates" are WordPress's "Themes." Understanding these distinctions is key to navigating each CMS.
* **The Block Editor Paradigm**: WordPress's Gutenberg editor is fundamentally different from the classic WYSIWYG editors. It's built around the concept of "blocks," and for custom code, the `Custom HTML` block is the designated tool. This modular approach is powerful but requires a different mindset.
* **CSS Customization Methods**: While both CMSs allow custom CSS, the methods differ. Joomla's `user.css` is a file-based approach, while the WordPress Customizer's "Additional CSS" is a database-driven approach. I now understand that for modern WordPress themes, this feature is becoming less prominent in the UI, requiring direct access or knowledge of hidden menus.

**Career/Employability/Learning Insights:**

This week's experience has significantly broadened my practical CMS skills. Being proficient in only one CMS is good, but knowing the two most popular platforms in the world—Joomla and WordPress—makes me a much more versatile and employable developer. I can now confidently say I have hands-on experience installing, configuring, and customizing both.

The troubleshooting process, from the hosting limit to the hidden CSS editor, was initially frustrating but ultimately very rewarding. It forced me to move beyond simply following a tutorial and engage in genuine problem-solving: identifying a problem, researching solutions, and applying them methodically. This is exactly what a professional developer does daily. This experience has built my confidence in tackling unfamiliar technical challenges. Furthermore, it highlights the importance of adaptability in the tech field; user interfaces change, and the ability to find solutions when the buttons aren't where you expect them to be is a critical soft skill.
