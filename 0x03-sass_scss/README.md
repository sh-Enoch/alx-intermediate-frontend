Overview
This project is a practical introduction to SASS/SCSS, a powerful CSS preprocessor. The goal is to move beyond basic CSS by learning to use features that make stylesheets more maintainable, readable, and efficient. Through a series of incremental tasks, the project covers the foundational concepts of SASS, from installation and setup to using variables, nesting, and mixins.

Learning Objectives
Upon completing this project, a developer will be able to:

Install and configure the SASS compiler in a development environment.
Understand the core philosophy of a CSS preprocessor and its advantages over vanilla CSS.
Write and compile SASS (.scss) files into standard CSS.
Apply core SASS features to solve common styling problems:
Use variables to store and reuse values (like colors, fonts, sizes).
Structure CSS rules using nesting to mirror HTML hierarchy.
Create reusable code blocks with mixins to apply consistent styles.
Key Concepts
SASS/SCSS (Syntactically Awesome Style Sheets): A preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets (CSS). It adds features that do not exist in pure CSS, providing a more developer-friendly way to write styles. SCSS is the newer syntax that is fully compatible with CSS.

Variables ($variable-name): A way to store information that you want to reuse throughout your stylesheet. You can store things like colors, font stacks, or any CSS value you think you’ll want to reuse. This promotes consistency and makes global changes trivial (e.g., changing a theme color in one place).

Nesting: Allows you to write CSS rules inside another rule, which helps to organize code in a way that visually matches the HTML structure. This avoids the need to repetitively write long selector chains.

Mixins (@mixin / @include): A powerful feature that allows you to define reusable blocks of styles. You can even make them take arguments, making them highly flexible. They are perfect for vendor prefixes, defining a set of margins/paddings, or creating complex style patterns used in multiple places.

Tools and Libraries
Node.js (v20.16.0 recommended): A JavaScript runtime used to run the Node Package Manager (npm).
Node Version Manager (nvm): A bash script used to manage multiple active Node.js versions on a single system. Used here for the recommended installation path.
npm (Node Package Manager): The default package manager for Node.js, used to install libraries and tools from its registry.
SASS Compiler (v3.7.4): The core library installed via npm. This is the tool that reads .scss files and compiles them into .css files that browsers can understand.
Real-World Use Case
In a modern web development workflow, writing plain CSS for large, complex applications becomes difficult to manage. Stylesheets become thousands of lines long, making them prone to errors, hard to read, and challenging to maintain.

SASS/SCSS addresses these issues directly. A front-end developer at a company like Netflix, Airbnb, or Shopify would use SASS to:

Create and Enforce a Design System: Define a palette of brand colors ($primary-color, $secondary-color) and a typography scale ($font-size-sm, $font-size-lg) in a central _variables.scss file. Every component across the entire site uses these variables, ensuring visual consistency.
Structure Large Codebases: Use nesting and partials (not covered here but a key feature) to break down a massive styles.css file into smaller, logical files (e.g., _header.scss, _buttons.scss, _forms.scss) that are easier for a team to work on simultaneously.
Increase Development Speed: Use mixins for common tasks like creating a flexbox container (@mixin flex-center { display: flex; justify-content: center; align-items: center; }) or managing responsive breakpoints. This eliminates repetitive code and reduces errors.
Improve Maintainability: To change the site’s primary color, a developer only needs to update the value of one variable instead of searching and replacing dozens of hex codes throughout the codebase.
This project provides the essential building blocks to start leveraging these professional-grade techniques.

📝 Project Assessment (Hybrid)
Your project will be evaluated primarily through manual reviews. To ensure you receive your full score, please:

✅ Complete your project on time
📄 Submit all required files
🔗 Generate your review link
👥 Have your peers review your work

An auto-check will also be in place to verify the presence of core files needed for manual review.

⏰ Important Note
If the deadline passes, you won’t be able to generate your review link—so be sure to submit on time!

We’re here to support your learning journey. Happy coding! ✨
