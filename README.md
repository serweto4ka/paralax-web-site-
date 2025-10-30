# Parallax Effect Website

This is a simple, static one-page website built with HTML and CSS to demonstrate a classic parallax scrolling effect. The background images remain fixed in position while the content sections scroll over them, creating an illusion of depth.

## 🚀 Features

* **Parallax Scrolling:** Uses `background-attachment: fixed` to create the parallax effect on desktop browsers.
* **Multiple Sections:** Demonstrates the effect with three different background images (`.pimg1`, `.pimg2`, `.pimg3`).
* **Content Blocks:** Includes light (`.section-light`) and dark (`.section-dark`) themed content sections to break up the visual flow.
* **Responsive Fallback:** Includes a media query that disables the fixed attachment on screens smaller than 568px (common for mobile devices) by changing `background-attachment` to `scroll`. This is done because `background-attachment: fixed` can cause performance issues on mobile.

## 🛠️ Technologies Used

* **HTML5**
* **CSS3** (Flexbox, background properties, media queries)

## 📂 File Structure

The project relies on a specific file structure as defined in the `index.html` and `styles.css` files.
