# Week 5 – Creating a WordPress Child Theme

## Overview
This week’s focus was on learning how to create a **WordPress child theme** and understanding why it’s an essential technique for professional web development.

## What I Did
I created a new child theme based on the parent theme **Twenty Twenty-Four**.  
The child theme includes:
1. A new `style.css` file referencing the parent.
2. A `functions.php` file to enqueue parent and child styles.
3. Six visible customizations:
   - Background color change  
   - Header color change  
   - Link hover color and underline  
   - Post title font and text transformation  
   - Image border radius and shadow  
   - Footer background and text style

After activating the theme, I confirmed all the changes were successfully displayed on my local WordPress site.

## What I Learned
Creating a child theme helps separate **custom design** from the **core code** of the parent theme.  
This ensures that when the parent theme updates, my modifications remain intact — a key principle in scalable development.

I also learned how to manually place the theme into the `wp-content/themes/` folder, which gave me a deeper understanding of WordPress’s file structure.

## Reflection
One key takeaway for me is the importance of **safe customization**.  
In web development, it’s tempting to modify core files, but sustainable coding is about making improvements without breaking the system.

## Next Steps
Next week, I plan to:
- Experiment with adding custom functions to the child theme.
- Explore theme.json and advanced styling options.
- Practice exporting and deploying the site to a hosting environment.

---

**LinkedIn Post:** [View Here](#)  
**Theme ZIP File:** `twentytwentyfour-child.zip`
