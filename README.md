# Personal Portfolio Website

A student portfolio made with **HTML and CSS only**. It has a warm editorial style, responsive sections, in-page navigation for all eight sections, project cards, a contact area, and a CSS-only light/dark theme switch.

## Files

- `index.html` — page structure and portfolio content
- `style.css` — colors, typography, layout, effects, and responsive styles
- `index.txt` and `style.txt` — plain-text copies of the HTML and CSS source
- `images/` — optional folder for your profile picture and project screenshot

## Open the website

Keep `index.html` and `style.css` in the same folder. Open `index.html` in a browser. The page includes designed image placeholders; if you add your own images, save them as `images/profile.jpg` and `images/project.jpg` (or change the paths in the HTML).

The typography uses Google Fonts when an internet connection is available and falls back to system fonts when it is not.

## Personalize it

In `index.html`, replace `Your Name`, the education details, project, hobbies, achievement, email address, and social profile links. Adjust the image alt text to describe your actual images. The skills progress values are examples; change the percentages in the inline `style` attributes to match your own estimates.

In `style.css`, change the color variables at the top to customize the palette. The media queries near the bottom adapt the page for tablets and phones. Keep the files `index.html` and `style.css` together so the stylesheet loads correctly.

## JavaScript-free behavior

This project contains no JavaScript. Section navigation uses HTML anchor links, smooth scrolling, responsive layouts, and the light/dark theme switch use CSS. The theme control is a checkbox styled as a button. The form uses built-in HTML required-field and email-format checks. Submitting the contact form opens the visitor's email app to prepare a message; it does not send it automatically. The current section is not dynamically highlighted in the navigation.

## Upload to GitHub

Create your own repository, open a terminal in this project folder, then run the following commands. Replace the URL with your repository URL:

```bash
git init
git add .
git commit -m "Create personal portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
