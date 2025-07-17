# Personal Portfolio Website - Jasmine Afrem

This repository contains the source code for my personal portfolio website, showcasing my skills, projects, competitions, and educational background as a Computer Science student. The website is designed to be modern, responsive, and visually appealing with a purple-themed aesthetic.

##  Features

*   **Modern Design:** Clean and contemporary layout with a consistent purple color scheme.
*   **Responsive Layout:** Adapts seamlessly to various screen sizes (desktops, tablets, and mobile devices).
*   **Smooth Scrolling:** Implemented for navigation links.
*   **Dynamic Content:**
    *   Current year in the footer automatically updates via JavaScript.
*   **Sections:**
    *   **Home/Hero:** Introduction with name, subtitle, contact information, and social media links. Features a top banner image.
    *   **About Me:** A brief personal introduction and professional interests.
    *   **Skills:** A list of technical skills.
    *   **Projects:** A grid display of key projects with descriptions and links to their GitHub repositories.
    *   **Competitions:** A list of participation and achievements in various competitions.
    *   **Education:** Details of academic background.
    *   **Languages:** Proficiency in spoken/written languages.
*   **SVG Icons:** Used for enhanced visual appeal and scalability.
*   **Google Fonts:** Utilizes 'Montserrat' for headings and 'Lato' for body text.

##  Technologies Used

*   **HTML5:** For the structure of the website.
*   **CSS3:** For styling, layout, responsiveness, and theming.
    *   CSS Variables for easy theme management.
    *   Flexbox and CSS Grid for layout.
    *   Media Queries for responsive design.
*   **JavaScript (Vanilla):** For dynamic elements like the current year in the footer.
*   **Google Fonts:** For custom typography.
*   **SVG:** For icons and graphical elements.

##  Getting Started

To view or work on this website locally:

1.  **Clone the repository:**
    ```bash
    > git clone https://github.com/Jasmine-Afrem/your-repo-name.git
    ```
    (Replace `your-repo-name` with the actual name of your repository if it's different from this example)
2.  **Navigate to the project directory:**
    ```bash
    > cd your-repo-name
    ```
3.  **Open `index.html` in your web browser:**
    *   You can usually just double-click the `index.html` file, or right-click and choose "Open with" your preferred browser.

No special build steps or dependencies are required for this simple static website.

##  File Structure
```bash
├── index.html # Main HTML file
├── style.css # Main CSS file
└── README.md # This README file
```

##  Customization

### Theme Colors and Fonts:
The primary theme colors, fonts, and other global styles are defined as CSS variables at the top of `style.css` within the `:root` selector. You can easily modify these to change the overall look and feel.

```css
:root {
    --primary-purple: #7F00FF;
    --primary-purple-dark: #6A0DAD;
    /* ... other color variables ... */

    --font-primary: 'Montserrat', sans-serif;
    --font-secondary: 'Lato', sans-serif;

    --nav-height: 70px;
    --banner-height: 150px; /* Adjust height of the top banner image here */
    /* ... other layout variables ... */
}
