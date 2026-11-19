# 🚕 The Driving Crooner: Icons and a Mobile Menu

## 🎯 Overview

The Driving Crooner is a noir audio drama set in Cincinnati in 1947. Its website is already built: the HTML and the
base styles are done. Your job is to finish it. Add icons throughout the page, then make the **Menu** button open
and close the navigation on phones. You'll practice using an icon library, writing accessible labels for icon-only
links, and toggling a page element with JavaScript.

## 📋 Requirements

### Icons

- [ ] Load [Font Awesome](https://fontawesome.com/) in the `<head>` of `index.html`.
- [ ] Add an icon to every spot shown in the example screenshots below:
  - [ ] A car next to the site name in the header
  - [ ] A menu (hamburger) icon in the **Menu** button
  - [ ] A clock next to each length and a calendar next to each date, in the latest chapter and on all six chapter cards
  - [ ] Headphones in the **Listen now** button
  - [ ] Spotify, Apple, YouTube and RSS icons for the **Also on** links
  - [ ] An icon that fits each cast member's role (for example, a microphone for the crooner)
  - [ ] Instagram, TikTok and email icons in the footer
- [ ] Mark each decorative icon with `aria-hidden="true"`, so screen readers skip it.
- [ ] Links that show only an icon (**Also on** and the footer) keep their text for screen readers inside a
  `<span class="visually-hidden">`. `base.css` already defines the `.visually-hidden` class.

### Mobile menu

- [ ] On screens narrower than `48rem`, show the **Menu** button and hide the navigation links.
- [ ] Clicking **Menu** shows the links; clicking it again hides them.
- [ ] Each click switches the button's `aria-expanded` attribute between `"false"` and `"true"`.
- [ ] At `48rem` and wider, hide the **Menu** button and always show the links in a row across the header.

### Files

- [ ] Do **not** edit `css/base.css`. Put your styles in `css/style.css` and link it **after** `base.css`.
- [ ] Put your JavaScript in `js/script.js` and load it from `index.html`.
- [ ] Don't change the page's text or rearrange its sections. `base.css` styles some elements by their position in
  the page, so moving them can break the layout.

## 🖼️ Example Output

**Desktop:**

![The finished page at desktop width, with icons in the header, latest chapter, chapter cards, cast and footer](../images/final.png)

**Phone, with the menu open:**

<img src="../images/final-phone-menu.png" alt="The finished page at phone width, with the Menu button pressed and the navigation links stacked below the header" width="390">

When the menu is closed, the header shows only the site name and the **Menu** button.

## 📂 Starter Files

| File / Folder   | Purpose                                                     |
|-----------------|-------------------------------------------------------------|
| `index.html`    | The finished page markup. Add your icons, styles and script here. |
| `css/base.css`  | Provided styles. **Don't edit.**                            |
| `css/style.css` | **You create.** Your mobile menu styles.                    |
| `js/script.js`  | **You create.** The code that opens and closes the menu.    |
| `images/`       | Example screenshots of the finished page.                   |

## 🧮 Grading

| Criteria                                                                                   | Points |
|--------------------------------------------------------------------------------------------|--------|
| Font Awesome loads, and every icon from the screenshots is present                         | 4      |
| Decorative icons are hidden from screen readers; icon-only links keep visually hidden text | 3      |
| Menu opens and closes on phones and updates `aria-expanded`                                | 4      |
| Desktop header shows the links in a row and hides the button                               | 2      |
| `base.css` unchanged; styles in `css/style.css`, script in `js/script.js`                  | 2      |
| **Total**                                                                                  | **15** |

The due date is in Canvas.

## 📚 Resources

- [Font Awesome: Add icons with HTML](https://docs.fontawesome.com/web/add-icons/how-to)
- [Font Awesome: Accessibility](https://docs.fontawesome.com/web/dig-deeper/accessibility)
- [MDN: `aria-expanded`](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes/aria-expanded)
- [MDN: `addEventListener()`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)
- [MDN: `setAttribute()`](https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute)

## 🆘 Getting Help

<!-- Office hours, discussion board, tutoring center, etc. -->

---

The AI policy and submission instructions are in the [README](../README.md).
