# Personal Portfolio Website

A personalized student portfolio for Rachit B Angadi, made with **HTML and CSS only**. It has a warm editorial style, responsive sections, in-page navigation for all eight sections, project cards, a subtle animated background, shooting stars, a CSS animated race car on a marked track, hover animations, a LinkedIn button, a contact area, and a CSS-only light/dark theme switch.

## Files

- `index.html` — page structure and portfolio content
- `style.css` — colors, typography, layout, effects, and responsive styles
- `index.txt` and `style.txt` — plain-text copies of the HTML and CSS source
- `images/avatar.webp` — selected portfolio avatar artwork

## Open the website

Keep `index.html` and `style.css` in the same folder. Open `index.html` in a browser. The selected avatar is stored at `images/avatar.webp`. Replace it with an image you prefer and update the image path and alt text in `index.html` if you change the file.

The typography uses Google Fonts when an internet connection is available and falls back to system fonts when it is not. The background glow, shooting stars, race car, and hover effects use CSS only. They automatically stop or simplify when the visitor has requested reduced motion. CSS can animate page elements on hover but cannot track and animate a separate cursor follower; that would require JavaScript.

## Personalize it

The current page includes the details provided by Rachit: education, skills, project leadership, interests, activities, email, GitHub, and LinkedIn. Change them directly in `index.html` if anything needs correction. The profile avatar is user-provided Iron Man artwork; replace `images/avatar.webp` if you prefer another image.

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
