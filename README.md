Pure CSS Responsive Navbar :---
This project showcases a fully functional, responsive navigation bar created using only HTML and CSS. The main feature is a collapsible mobile menu that operates without a single line of JavaScript, making it lightweight and efficient.

✨ Key Features
Fully Responsive: Adapts seamlessly to various screen sizes, from desktops to mobile devices.

JavaScript-Free: The interactive toggle functionality is achieved using the "checkbox hack" in CSS.

Lightweight & Fast: With no JS dependencies, the navbar is incredibly fast to load.

Easy to Integrate: The code is self-contained and can be easily integrated into any existing website.

Customizable: The styles are straightforward and can be customized with basic CSS knowledge.

🤔 How It Works
The magic behind the collapsible menu is a clever CSS technique often called the "checkbox hack". Here’s the basic principle:

1...An invisible checkbox (<input type="checkbox">) is placed in the HTML.

2...A <label> element, styled to look like a hamburger menu icon, is associated with the checkbox. Clicking this label toggles the checkbox's state (checked/unchecked).

3...The navigation menu  is placed after the checkbox in the HTML structure.

4...CSS pseudo-selectors (:checked) and combinators (~ or +) are used to change the styles of the navigation menu when the checkbox is checked. For example, we can change its visibility, position, or opacity to show or hide it.
