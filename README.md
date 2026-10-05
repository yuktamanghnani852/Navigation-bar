🧭 Navigation Bar – HTML & CSS

A simple HTML and CSS navigation bar project that demonstrates how to create a modern website menu using Flexbox, CSS hover effects, rounded corners, and gradient backgrounds.

The navigation menu contains links to different sections/pages of a website such as Home, About Us, Gallery, Achievements, and Contact Us.

📸 Project Overview

The webpage contains a centered horizontal navigation bar with five menu items:

- 🏠 Home
- ℹ️ About Us
- 🖼️ Gallery
- 🏆 Achievements
- 📞 Contact Us

The navigation bar is placed inside a large box with a blue-to-pink gradient background.

Layout

┌──────────────────────────────────────────────────────────┐
│                                                          │
│       ┌──────────────────────────────────────────┐       │
│       │ Home │ About Us │ Gallery │ Achievements │       │
│       │             │ Contact Us │               │       │
│       └──────────────────────────────────────────┘       │
│                                                          │
│              Blue → Pink Gradient Background             │
│                                                          │
└──────────────────────────────────────────────────────────┘

🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Linear Gradient
- CSS Hover & Transform Effects

No external libraries or frameworks are required.

📂 Project Structure

navigation-bar/
│
├── index.html
├── About.html
├── Gallery.html
├── Achivements.html
├── Contact Us.html
└── README.md

«The filenames are based on the links used in the provided HTML code.»

🎨 CSS Features

Navigation List

The "<ul>" element is styled as a horizontal navigation bar:

ul {
    width: 80%;
    list-style-type: none;
    display: flex;
    justify-content: space-evenly;
    height: 100px;
    align-items: center;
    background-color: brown;
    color: white;
    border-radius: 40px;
}

This creates:

- A horizontal menu
- Even spacing between menu items
- Rounded corners
- Brown background
- White text

Background Gradient

The main ".box" uses a linear gradient:

.box {
    height: 600px;
    justify-content: center;
    align-items: center;
    display: flex;
    background: linear-gradient(blue, pink);
}

This creates a smooth gradient from blue to pink.

Navigation Links

The links are styled with:

a {
    color: aliceblue;
    text-decoration: none;
}

This removes the default underline and gives the links a light-colored appearance.

Hover Animation

When the user moves the mouse over a menu item:

li:hover {
    transform: scale(1.5);
}

The menu item becomes larger using the CSS "scale()" transformation.

🔗 Navigation Links

The navigation menu connects to different HTML pages:

<a href="index.html"><li>Home</li></a>
<a href="About.html"><li>About Us</li></a>
<a href="Gallery.html"><li>Gallery</li></a>
<a href="Achivements.html"><li>Achivements</li></a>
<a href="Contact Us.html"><li>Contact Us</li></a>

Clicking each menu item opens its corresponding HTML page.

▶️ How to Run

1. Create a project folder.
2. Save the provided code as "index.html".
3. Create the linked HTML pages in the same folder.
4. Make sure the filenames match the "href" values.
5. Open "index.html" in any modern web browser.
6. Hover over the menu items to see the scaling animation.
7. Click a menu item to navigate to the corresponding page.

🎯 Learning Objectives

This project helps beginners understand:

- HTML navigation links
- "<ul>" and "<li>" elements
- Anchor ("<a>") tags
- CSS Flexbox
- "justify-content"
- "align-items"
- CSS gradients
- Border radius
- Hover effects
- CSS transforms
- Basic website navigation

💡 Possible Improvements

The project can be improved by:

- Adding a responsive mobile navigation menu
- Adding icons to the navigation items
- Adding smooth transitions to the hover effect
- Creating an active-page indicator
- Adding a dropdown menu
- Using semantic "<nav>" HTML
- Improving accessibility with appropriate link structure
- Correcting "Achivements" to "Achievements"

Example Smooth Hover Effect

The hover animation can be made smoother by adding:

li {
    transition: transform 0.3s ease;
}

This creates a smooth scaling animation instead of an immediate change.

👨‍💻 Author

Created as a beginner-friendly HTML & CSS navigation bar project for practicing Flexbox, gradients, links, and hover animations.# Navigation-bar
