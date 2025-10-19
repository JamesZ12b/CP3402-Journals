
**19 / Oct / 2025**
**4:00PM - 9:30PM**
(Learning, creating a child theme, extensive debugging, and journaling)

### **Week 5 - WordPress: Developing Child Themes**

**Learning Activities & Resources:**

[cite_start]This week's objective was to create a WordPress Child Theme to apply custom styles to my startup website, a core skill for safe and maintainable customizations[cite: 177, 179]. The first step was to replicate my live SiteGround site on my local USB WebServer environment. I attempted this with a migration plugin but ran into a server error during the process. Instead of spending more time troubleshooting the migration, I decided to manually recreate the necessary pages (Home, Our Team, Projects) on my fresh local WordPress installation, which also gave me good practice in setting up site structure.

Once the local site was ready, I created the child theme. I created a new folder named `twentytwentyfive-child` inside the `wp-content/themes/` directory. [cite_start]Inside this folder, I created the two essential files: `style.css`, where I added the required header to link it to the `twentytwentyfive` parent theme [cite: 183][cite_start], and `functions.php` to enqueue the parent theme's stylesheet[cite: 183].

The main task was to add at least six visible customizations via CSS. I wrote styles to change the global background and link colors, add borders to titles, and create custom-styled "cards" for projects and a distinct bio section for the team page. However, after activating the child theme, none of my styles appeared. This began an extensive and highly educational debugging session.

My troubleshooting process was as follows:
1.  First, I tried a hard refresh of the browser (`Ctrl + F5`) to clear any caching issues. This did not solve the problem.
2.  Next, I used the browser's Developer Tools ("Inspect") to check the page's source code. I discovered that my child theme's `style.css` file was not being loaded at all.
3.  This pointed to an issue with the `functions.php` file. After carefully re-checking the code and finding no visible errors, I replaced the initial code with a more robust and modern version to ensure proper script enqueuing.
4.  Even after fixing the `functions.php`, the styles were still missing. Re-examining the loaded `style.css` in the developer tools (it was now loading but empty) led me to meticulously check the CSS code itself, where I found a single extra curly brace `}` at the very end of the file. This syntax error was causing the entire stylesheet to be ignored by the browser.

After correcting this final syntax error and performing another hard refresh, all the custom styles appeared perfectly. [cite_start]The final step was to compress the `twentytwentyfive-child` folder into a `.zip` file for submission[cite: 180].

**References:**
* [cite_start]WordPress: Building Child Themes (LinkedIn Learning) [cite: 173]
* [cite_start]Design Responsive WordPress Themes in the Browser (LinkedIn Learning) [cite: 175]
* The final `twentytwentyfive-child.zip` file containing my work.

**Estimated Hours:**
A total of 5.5 hours. A significant portion was dedicated to the systematic debugging process, which proved to be an invaluable learning experience.

**Content Insights:**

This week provided a deep, practical understanding of why child themes are the professional standard for WordPress customization. It's not just a theoretical best practice; I now see firsthand how it creates a safe separation between the core theme and my modifications. The experience clarified the critical roles of `style.css` (for both identification via its header and for custom styles) and `functions.php` (for controlling how stylesheets are loaded). The most significant insight was realizing how a single, tiny syntax error, like an extra bracket, can invalidate an entire file, emphasizing the precision required in coding.

**Career/Employability/Learning Insights:**

This was by far the most valuable week for developing real-world developer skills. The process of debugging was far more educational than if everything had worked on the first try. I learned the critical importance of using browser developer tools as a primary diagnostic weapon. Being able to inspect the source, check for loaded files, and identify errors is a fundamental skill that separates a user from a developer. This experience taught me resilience and a methodical approach to problem-solving: form a hypothesis (is it the cache? is the file loading? is the code valid?), test it, and then move to the next logical step. This systematic debugging process is a skill directly applicable to any programming or IT role and is crucial for becoming an efficient and self-sufficient developer.
