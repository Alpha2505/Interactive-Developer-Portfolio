# Interactive Developer Portfolio

An interactive and responsive developer portfolio built with **Angular** and **Bootstrap**, showcasing projects, publications, and technical skills.  
The platform is designed to be modular and production-grade, with dynamic project filtering, reusable components, and cross-device compatibility.

## 🚀 Features

- **Dynamic Project Filtering** – explore projects interactively by category or technology.
- **Reusable Angular Components** – modular structure for scalability and maintainability.
- **Responsive Design** – optimized for desktops, tablets, and mobile devices using Bootstrap.
- **Routing Support** – seamless navigation between About, Skills, Projects, and Contact sections.
- **Deployment Ready** – hosted on GitHub Pages for easy public access.

## 🛠️ Tech Stack

- **Frontend Framework**: Angular
- **Styling**: CSS3, SCSS/Sass
- **Animations**: CSS Animations, Angular Animations
- **Icons**: FontAwesome, Lucide Icons *(customize based on what you used)*
- **Fonts**: Google Fonts
- **Hosting**: GitHub Pages
- **Build Tools**: Angular CLI, TypeScript

## 🎯 Sections

- **🏠 Home**: Welcome section with hero banner and introduction
- **👨‍💻 About**: Professional background, skills, and expertise
- **💼 Portfolio**: Showcase of development projects with descriptions and links
- **📄 Resume**: Professional experience and education background
- **🛠️ Services**: Technical services and expertise offered
- **📞 Contact**: Contact form and professional links

## 📂 Project Structure

Interactive-Developer-Portfolio/
├── src/
│   ├── app/
│   │   ├── Constants/
│   │   │   └── app-constants.ts     # Application constants
│   │   ├── home/
│   │   │   ├── footer/              # Footer component
│   │   │   ├── nav-tabs/            # Navigation components
│   │   │   │   ├── about/           # About section
│   │   │   │   ├── contact/         # Contact section
│   │   │   │   ├── portfolio/       # Portfolio section
│   │   │   │   ├── resume/          # Resume section
│   │   │   │   └── services/        # Services section
│   │   │   ├── portfolio-details/   # Detailed portfolio views
│   │   │   └── home.component.*     # Main home component
│   │   ├── app-routing.module.ts    # Routing configuration
│   │   ├── app.component.*          # Root component
│   │   └── app.module.ts            # Main app module
│   ├── assets/                      # Static assets
│   ├── environments/                # Environment configurations
│   ├── favicon.ico                  # Site favicon
│   ├── index.html                   # Main HTML file
│   ├── main.ts                      # Bootstrap file
│   └── polyfills.ts                 # Browser compatibility
├── angular.json                     # Angular configuration
├── package.json                     # Dependencies and scripts
└── README.md                        # This file

