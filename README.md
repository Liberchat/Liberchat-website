

# Liberchat Website

<p align="left">
  <img src="assets/icon.png" alt="Liberchat Logo" width="128" />
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![Open Source](https://img.shields.io/badge/Open%20Source-❤️-red)](https://opensource.org/)
[![GitHub Stars](https://img.shields.io/github/stars/Liberchat/liberchat-site?style=social)](https://github.com/Liberchat/liberchat-site)

Official Liberchat website - Free and secure messaging application.

## Overview

This repository contains the source code for the official Liberchat website, a decentralized messaging application with end-to-end encryption.

**Website URL:** [https://liberchat.unionlibertaireanarchiste.org](https://liberchat.unionlibertaireanarchiste.org)

## Website Features

- **Home Page** - Introduction to Liberchat and downloads
- **Roadmap** - Project evolution and future versions
- **FAQ** - Frequently asked questions with an accordion system
- **Legal Mentions** - Privacy policy and GDPR compliance
- **Download Pages** - For each platform (Windows, Linux, macOS, Android)
- **Self-hosting** - Guide to hosting your own server (YunoHost)
- **Docker** - Local testing and rapid development
- **Responsive Design** - Mobile and desktop compatible

## Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styles with CSS variables
- **JavaScript** - Interactions and animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter)

## Project Structure

```
liberchat/
├── index.html              # Home page
├── roadmap.html            # Roadmap
├── faq.html                # Frequently asked questions
├── privacy.html            # Legal mentions
├── releases.html           # Android downloads
├── releases-linux.html     # Linux downloads
├── releases-windows.html   # Windows downloads
├── releases-macos.html     # macOS downloads
├── installation-apk.html   # Mobile installation guide
├── autohebergement.html    # YunoHost self-hosting guide
├── docker.html             # Docker guide for development
├── qr.html                 # QR codes for mobile
├── styles.css              # Main styles
├── script.js               # JavaScript scripts
├── modern-interactions.js  # Advanced animations
├── assets/                 # Images and resources
│   └── icon.png           # Liberchat logo
├── Dockerfile             # Docker configuration
├── docker-compose.yml     # Docker compose setup
├── .dockerignore          # Docker ignore file
├── README.md              # This file
└── LICENSE                # Project license
```

## Local Installation

### Method 1: Using Docker (Recommended)

1. **Download the project** (or clone the repository)
2. **Start with Docker Compose**
   ```bash
   docker-compose up -d
   ```
3. **Open in the browser**
   ```
   http://localhost:8345
   ```

### Method 2: Manual Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Liberchat/liberchat-site.git
   cd liberchat-site
   ```

2. **Local server**
   ```bash
   # With Python
   python -m http.server 8000
   
   # With Node.js
   npx serve .
   
   # With PHP
   php -S localhost:8000
   ```

3. **Open in the browser**
   ```
   http://localhost:8000
   ```

## Customization

### CSS Variables
The site uses CSS variables to facilitate customization:

```css
:root {
  --primary-color: #007bff;
  --accent-color: #28a745;
  --background-color: #1a1a1a;
  --text-color: #ffffff;
  --card-background: #2d2d2d;
}
```

### Themes
- **Dark Theme** - Default
- **Responsive Mode** - Automatic mobile/desktop adaptation
- **Animations** - Smooth transitions and hover effects

## Compatibility

- **Modern Browsers** - Chrome, Firefox, Safari, Edge
- **Responsive Design** - Mobile, tablet, desktop
- **Performance** - Optimized for fast loading
- **Accessibility** - WCAG standards respected

## Contribution

Contributions are welcome! To contribute:

1. **Fork** the project
2. **Create** a branch for your feature
3. **Commit** your changes
4. **Push** to the branch
5. **Open** a Pull Request

### Guidelines
- Respect semantic HTML structure
- Use existing CSS variables
- Test on mobile and desktop
- Optimize images and resources

## License

This project is under the MIT license. See the [LICENSE](LICENSE) file for more details.

## Useful Links

- **Liberchat Application** - [GitHub](https://github.com/Liberchat/Liberchat)
- **YunoHost Self-hosting** - [GitHub](https://github.com/Liberchat/liberchatserver_ynh)
- **Docker** - [GitHub](https://github.com/Liberchat/Liberchat-docker)
- **Militant** - <img src="https://militant.revlibertaire.com/assets/favicon.svg" alt="Militant Logo" width="16" height="16" style="vertical-align: middle;"> [Join Militant](https://militant.revlibertaire.com/group_detail.php?id=6)
- **Facebook** - [Facebook Group](https://www.facebook.com/groups/1056100956078058)
- **Downloads** - [Releases](https://github.com/Liberchat)

## Contact

- **GitHub Issues** - For bugs and suggestions
- **Email** - anarchymedialibertaire@gmail.com

---

**Liberchat** - Free and secure communication for everyone 🔒

