In this practical task, I created a small demo website using Sass along with an automated workflow powered by Gulp. The objective of the exercise was to demonstrate core Sass features such as variables, nesting, mixins, and inheritance/extend, while also setting up a workflow that compiles .scss files into CSS automatically.
What I Did
I built a simple webpage that includes a header, a content section, and styled buttons. All the styling is written in Sass and then compiled into CSS using a Gulp task. The project structure follows a modular Sass architecture, with separate partial files for variables, mixins, base styles, and the main stylesheet.
Sass Features Demonstrated
1. Variables
I created global variables for colors, border radius, and font settings.
These variables helped maintain a consistent design and allowed quick updates from one place.
2. Nesting
To keep the code cleaner and more readable, I used nesting within elements such as the header and the main content section.
This made the stylesheet more structured and easier to maintain.
3. Mixins
I created reusable mixins:
A card mixin for card UI styling
A flex-center mixin for easy flexbox alignment
Mixins helped avoid repeating styling patterns.
4. Extend/Inheritance
I used the @extend feature to create button variants.
A base .btn class defines shared button styling, while .btn-primary and .btn-outline extend from it and apply their own modifications.
Automated Workflow (Gulp)
To automate Sass compilation, I set up:
A sass task for compiling .scss into .css
A watch task that listens for any changes in the scss folder and recompiles automatically
This workflow simplifies development and ensures the CSS output is always updated.
Challenges and What I Learned
One challenge was configuring Gulp with the latest Sass compiler, as the syntax has changed from older tutorials. I learned how to properly use gulp-sass with the modern Sass module.
Additionally, organizing Sass files into partials helped me understand the benefits of modular styling.
Conclusion
Overall, this practical exercise improved my understanding of Sass and modern front-end workflows. By completing this task, I gained hands-on experience with SCSS syntax, reusable patterns, and build tools. This foundation will be useful for larger projects where maintainable and scalable CSS is important.
