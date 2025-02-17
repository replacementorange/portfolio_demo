# Portfolio Website

Welcome to the repository for my personal portfolio website. This site
showcases my skills and projects.

## Project Overview

This portfolio is a basic static website that highlights my work. It uses HTML for structure, CSS for styling, and SASS for efficient stylesheet management.

### Features

- **Responsive Mobile Design:** The portfolio adapts to different screen sizes, providing a seamless experience on mobile devices.

- **Sass Compilation:** Utilizes SASS for preprocessing, allowing for organized and maintainable CSS code.

- **Clean Layout:** A clean and modern layout that emphasizes readability and aesthetics.

### Getting Started

1. **Clone the Repository:**

   ```
   git clone https://github.com/replacementorange/portfolio_demo
   ```

2. **Install Dependencies:**

   If you have Node.js installed, you can install SASS:

   ```
   npm i sass
   ```

3. **Compile SASS Files:**
   Run the following command to compile SASS files into CSS

   ```
   npm run sass
   ```

   Running `npm run sass` will automatically watch for
   changes in the `scss/main.scss` file and compile them to
   `dist/css/main.css`

4. **Open in Browser:**
   Open `index.html` in your preferred web browser to view the portfolio.

## Project Structure

```
portfolio-demo/
├── .gitignore
├── README.md
├── dist/
│   ├── index.html
│   └── css/
│       ├── main.css
│       └── main.css.map
├── scss/
    ├── _config.scss
    ├── _mobile.scss
    └── main.scss
```

- **`.gitignore`:** Specifies files and directories to be ignored by Git.
- **`index.html`:** The main HTML file that includes all the content.
- **`scss/`:** Contains the source SASS files for styling.
  - **`_config.scss`:** Stores reusable variables and mixins.
  - **`_mobile.scss`:** Stores media queries for different resolutions.
  - **`main.scss`:** Main entry point for SASS.
- **`css/`:** Contains the compiled CSS files.
