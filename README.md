# ACM Portfolio Workshop

### Built with
![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff&style=for-the-badge)
![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff&style=for-the-badge)
![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)


### [Live preview](https://mamuzad.github.io/portfolio-workshop/) 🔗
## Workshop Overview

During the workshop, we covered the following topics:

- **HTML Basics:** Semantic HTML elements (header, nav, main, section, etc.), structure of webpages, element tags (opening/closing/void), common elements (h1-h6, p, a, br, img), divs & containers, and nesting concepts.
- **CSS Fundamentals:** Selectors (element, class, id), box model (content, padding, border, margin), layouts including block elements and Flexbox. Didn't get to discuss grid, animations, or CSS variables.
- **Development Tools:** VSCode with extensions like Live Server for real-time previewing of changes.
- **Version Control with Git and GitHub:** Connecting local repositories to remote GitHub repositories via VSCode. Did not go over basics of Git Commands (due to audience's previous experience).
- **Deployment:** Setting up static site deployment using GitHub Pages to make your portfolio accessible online.

## Available Templates
Three different templates were showcased during the workshop:

1. **Basic Version** - A simple portfolio template with separate pages for projects and about sections
2. **Two-Column Version** - A clean two-column layout portfolio template
3. **Bento Version** - A modern bento-grid style portfolio template

Choose the one that best fits your style or use them as inspiration to create your own design!

## Getting Started

### Clone and Create a New Repository

#### Via VSCode:
1. Open command palette
2. Search for `git clone`
3. Clone with the url or the repo's name (`mamuzad/portfolio-workshop`)

#### Via Terminal:
1. Clone this repository to your local machine:

```bash
git clone https://github.com/mamuzad/portfolio-workshop.git
```
2. Create a new repository on GitHub
3. Change the remote URL to point to your new repository:
```bash
git remote set-url origin https://github.com/<your-username>/<your-repo>.git
```
4. Push the code to your new repository:
```bash
git push -u origin main
```

## Working with the Templates
Each template folder contains everything you need to get started:

- `index.html` - The main HTML file for the template
  - Basic includes sub folders which are pages such as `/projects` & `/about`
- `styles.css` - The CSS styling for the template
- Additional assets and folders specific to each template

Simply edit the files to customize with your own information, projects, and styling.

## GitHub Pages Deployment
Deploying your portfolio on GitHub Pages is a straightforward process:

1. Go to your repository on GitHub
2. Click on "Settings" in the top navigation bar
3. Scroll down to the "Pages" section in the left sidebar
4. Under "Build and deployment" > "Source", select "Deploy from a branch"
5. Select the branch you want to deploy (usually "main" or "master")
6. Select the folder (usually "/(root)" if your files are in the main directory)
7. Click "Save"

- GitHub will process your request and deploy your static site. 
- Once complete, you'll see a message with the URL where your site is published (typically https://yourusername.github.io/repositoryname/).
- Any future changes you push to the selected branch will automatically trigger a new deployment, keeping your portfolio up to date.

## [Slides from Workshop](https://docs.google.com/presentation/d/1ywRE4bL6pDGbXeCN9mEZJCVNRUao2lCn3lC6rSUe8T8/edit?usp=sharing)
Click on the link above for the content from the workshop itself :)

## Additional Resources
- [FreeCodeCamp](https://www.freecodecamp.org/) - Free coding tutorials and projects
- [The Odin Project](https://www.theodinproject.com/) - Free full-stack curriculum
- [MDN Web Docs](https://developer.mozilla.org/) - Comprehensive web development documentation
- [CSS-Tricks](https://css-tricks.com/) - Helpful articles and guides for CSS
- [GitHub Pages Documentation](https://docs.github.com/en/pages) - Official documentation for GitHub Pages

## Questions?
If you have any questions about the workshop or the templates, feel free to open an issue in this repository.