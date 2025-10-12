### **Week 4 - Development and deployment workflows**

**Learning Activities & Resources:**

This week, the focus shifted to a more technical and professional aspect of web development: establishing a local development environment. The goal was to understand the workflow of building and testing a website on my own computer before deploying it to a live server.

[cite_start]Following the practical guide, my main task was to set up a dynamic CMS on my localhost[cite: 157, 161]. [cite_start]After considering the options, I chose to use USB WebServer due to its simplicity and portability, as suggested as an alternative in the guide[cite: 164]. I specifically downloaded the version bundled with PHP 8.1, understanding that using a modern version of PHP is crucial for performance, security, and future compatibility with WordPress and its plugins.

The process involved several key steps. First, I launched USB WebServer and confirmed that both Apache and MySQL services were running correctly. Then, I downloaded the latest version of WordPress and placed its core files into the `root` directory of the server. Using the built-in phpMyAdmin tool, which I accessed at `http://localhost/phpmyadmin`, I created a new, empty database for the site. Finally, by navigating to `http://localhost` in my browser, I initiated the famous WordPress 5-minute installation process, providing the database details I had just created. The installation was smooth, and I now have a fully functional WordPress site running entirely on my own machine.

[cite_start]To supplement this hands-on work, I began reviewing the recommended LinkedIn Learning resources for this week, particularly "Mapping the Modern Web Design Process," to better grasp the theory behind why a local-to-live workflow is the industry standard[cite: 150].

**References:**
* [cite_start]Mapping the Modern Web Design Process (LinkedIn Learning) [cite: 150]
* [cite_start]Version Control for Everyone (LinkedIn Learning) [cite: 152]
* Screenshots of my local WordPress dashboard and phpMyAdmin interface.

**Estimated Hours:**
Approximately 4 hours spent on learning the concepts, setting up the environment, and journaling.

**Content Insights:**

This week's practical provided a crucial insight into the distinction between a live (production) environment, like the SiteGround site I made last week, and a local (development) environment. I now understand that working locally provides a safe sandbox. I can experiment with new themes, test potentially risky plugins, or make significant changes without any fear of breaking the public-facing website. The development process is also much faster, as I am not waiting for files to upload or for server responses over the internet. [cite_start]This practice of "build locally, deploy globally" is clearly a foundational principle for professional and efficient web development[cite: 158].

**Career/Employability/Learning Insights:**

Learning to set up a local server environment feels like a significant step up in my technical skills. This is no longer just about using a CMS's user interface; it's about understanding and managing the stack that powers it. This skill is fundamental for any serious web development role and is essential for working in a team. [cite_start]I can see how each team member could have their own local copy of a site to work on, with changes being merged later[cite: 283]. This practical exercise has demystified what "localhost" means and has given me the confidence to handle basic server and database configurations, which is an invaluable skill for troubleshooting and a key competency for future employment in this field.
