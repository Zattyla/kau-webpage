# KAU - Safety Guidelines & Restricted List

Official repository of the safety guidelines and restricted list page for the **K-pop AI Universe (KAU)**.

This page was created to ensure that our Discord server remains a safe, comfortable space focused on the mental well-being of all members. Here, we list the rules of conduct regarding controversial figures in the industry and the official list of individuals banned from our universe.

## Features

* **Multilingual:** Native support for 4 languages (English, Portuguese, Spanish, and French), with instant switching. English is the default language.

* **Real-Time Search:** Functional search bar that filters cards by idol name, group, or keywords related to the reason (in any selected language).

* **Responsive Design:** The page adapts perfectly to computer, tablet, and mobile phone screens.

* **Easy Maintenance:** Simple code structure (HTML/CSS/JS in a single file) to facilitate adding new names to the list.

## Technologies Used

* HTML5
* CSS3 (Flexbox, Grid, CSS Variables)
* JavaScript (Vanilla - for search logic and language switching)
* Hosting: [GitHub Pages](https://pages.github.com/)

## How to Update the Restricted List

If it becomes necessary to add a new name to the banned list in the future, the process is quick and done directly through GitHub:

1. Access the `index.html` file in this repository.

2. Click the pencil icon (Edit) in the upper right corner.

3. Scroll down to the `<div class="grid-lista" id="listaGrid">` section.

4. Copy the code block below and paste it at the end of the list (before the closing `</div>` of the grid).

5. Replace the text in brackets with the actual data.

```html
<div class="card">
<div>
<h3>[Idol Name]</h3>
<h4>[Group or Solo Name]</h4>
<p class="texto-en">[Reason in English]</p>
<p class="texto-pt">[Reason in Portuguese]</p>
<p class="texto-es">[Reason in Spanish]</p>
<p class="texto-fr">[Reason in French]</p>

</div>
<span class="status-badge texto-en">Fully Banned</span>
<span class="status-badge texto-pt">Totally Banned</span>
<span class="status-badge texto-es">Totally Prohibited</span>
<span class="status-badge texto-fr">Totally Banned</span>
</div>
