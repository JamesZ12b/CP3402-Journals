**29 / Nov / 2025**
**7:00PM - 11:00PM**
(Sass practical exercise, continued group project development)

### **Week 9 - CSS pre-processing with Sass**

**Learning Activities & Resources:**

This week's focus was on learning and applying CSS pre-processing techniques using Sass (SCSS), while continuing the momentum on the major group project.

1.  **Sass Practical (Individual Task):**
    * I explored the capabilities of Sass (Syntactically Awesome Style Sheets) to write more efficient and maintainable CSS.
    * **Environment Setup:** Instead of using a command-line tool, I installed the "Live Sass Compiler" extension in VS Code to automatically compile my `.scss` files into `.css` in real-time.
    * **Implementation:** I created a standalone static webpage (`index.html`) and styled it using a `style.scss` file. I successfully demonstrated the four required features:
        * **Variables:** Defined `$primary-color` and `$text-color` to manage the color scheme globally.
        * **Mixins:** Created a `@mixin flex-center` to handle repetitive Flexbox centering code.
        * **Nesting:** Used nested selectors (e.g., `.main-header nav ul`) to mirror the HTML structure, making the stylesheet more readable.
        * **Extend/Inheritance:** Created a `.btn-base` class and used `@extend` to create specific primary and secondary buttons that share common properties.

2.  **Group Project Work (Assignment 2):**
    * Continued working on the "Baizonn Learning Centre" custom theme.
    * I applied the principles of DRY (Don't Repeat Yourself) learned from the Sass exercise to our WordPress theme development, ensuring our CSS is modular and reusable.
    * Verified the consistency of the "Visit Us" page content across our Staging environment.

**Resources/Links:**
* LinkedIn Learning: Sass Essential Training
* VS Code Extension: Live Sass Compiler (by Glenn Marks)
* Submitted Files: `index.html`, `style.scss`
* Official Sass Documentation: sass-lang.com

**Estimated Hours:**
4.0 hours (1.5 hours learning and coding Sass, 2.5 hours on Group Project theme refinement)

**Content Insights:**

Using Sass highlighted the limitations of vanilla CSS, particularly regarding code repetition and maintenance. The **Variables** feature is a game-changer for theming; changing a single hex code at the top of the file updates the entire site, which is crucial for maintaining brand consistency (like the specific blue we use for the Baizonn project). **Nesting** makes the CSS logic much easier to follow visually, as it mimics the DOM structure. However, I also learned that "Inheritance" (`@extend`) should be used carefully to avoid creating bloated CSS selectors in the compiled output.

**Career/Employability/Learning Insights:**

This week reinforced the importance of "Tooling" in modern web development. Just as we use Git for version control and Vagrant for local environments in our group project, using a Pre-processor like Sass is an industry-standard practice for front-end efficiency. It shifts the focus from "writing code" to "architecting styles." Mastering these tools makes a developer significantly more productive and attractive to employers, as it shows an ability to work with complex, scalable codebases rather than just hacking together simple stylesheets.
