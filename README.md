# 🌐 GitHub Pages Deployment Demo
### (A Demo System for Publishing Websites with GitHub Pages)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](#)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=github&logoColor=white)](#)

This project is a demo that demonstrates how to publish a website using **GitHub Pages**, covering the configuration and deployment processes involved.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Usage](#installation-and-usage)
- [Project Structure](#project-structure)
- [Development Process](#development-process)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
This work was created to experience hosting static web content on GitHub's infrastructure for free and quickly. It serves as a basic example of CI/CD (Continuous Integration/Continuous Deployment) processes.

- **Developer:** Haluk Can SARIÖZ
- **Type:** Web Deployment Demo
- **Live Demo:** [halukcansarioz.github.io/gh-pages-demo](https://halukcansarioz.github.io/gh-pages-demo)

---

## Features
- **Automatic Publishing:** Commits pushed to the main branch are automatically published.
- **Responsive Design:** Fully compatible with mobile, tablet, and desktop devices.
- **Fast Loading:** High performance through static file optimization.
- **Custom Domain Support:** Example of custom domain configuration on GitHub Pages.

---

## Technologies Used
- **HTML5:** Page structure and semantic content.
- **CSS3:** Visual design and animations.
- **GitHub Actions:** Automated deployment workflows.
- **Git:** Version control.

---

## Installation and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/halukcansarioz/gh-pages-demo.git
```

### 2. Navigate to the Project Directory
```bash
cd gh-pages-demo
```

### 3. Install Dependencies
*(Note: Since this is a static project, package installation is usually not required. However, if there are npm packages, install them.)*
```bash
npm install
```

### 4. Launch the Application
To view it on a local server:
```bash
# If you are using a live server
# (e.g., VS Code Live Server or a simple http-server)
npx http-server .
```

---

## Project Structure
```text
gh-pages-demo/
├── .github/
│   └── workflows/      # GitHub Actions deployment settings
├── assets/             # Images, icons, and fonts
├── css/                # Style files
├── js/                 # Script files
├── index.html          # Main page
└── README.md           # Project documentation
```

---

## Development Process

### 1. Fork
You can copy the project to your own account and experiment with your own GitHub Pages settings.

### 2. Create a New Branch
```bash
git checkout -b feature/new-design
```

### 3. Push the Code
```bash
git push origin feature/new-design
```

---

## Contributing
1. **Fork** this repository.
2. Create a **Branch** (`git checkout -b feature/NewFeature`).
3. Make your changes and **Commit** (`git commit -m 'Add: New feature'`).
4. **Push** your code (`git push origin feature/NewFeature`).
5. Open a **Pull Request**.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

**Project Link:** [https://github.com/halukcansarioz/gh-pages-demo](https://github.com/halukcansarioz/gh-pages-demo)

---

## License
This project is licensed under the [MIT License](LICENSE).
