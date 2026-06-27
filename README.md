# Triton Tails - Howloween Website

The official website for Howloween, an annual Halloween-themed mini convention at UCSD. Howloween is hosted by Triton Tails, the furry student organization at UC San Diego.

## 🛠️ Technology Stack

- **[11ty (Eleventy)](https://www.11ty.dev/)** - Static Site Generator
- **[Vite](https://vitejs.dev/)** - Build Tool & Development Server
- **[Bootstrap 5](https://getbootstrap.com/)** - Frontend Framework
- **[Sass](https://sass-lang.com/)** - CSS Preprocessor
- **[GSAP (GreenSock)](https://greensock.com/gsap/)** - Animation Library
- **[ESLint](https://eslint.org/)** - JavaScript Linter
- **[Prettier](https://prettier.io/)** - Code Formatter
- **[Jest](https://jestjs.io/)** - Testing Framework
- **[Nunjucks](https://mozilla.github.io/nunjucks/)** - Templating Language

## 📁 Project Structure

```
src/
├── content/              # Content and data
│   ├── components/      # Reusable content components
│   ├── data/           # Site-wide data files
│   └── pages/          # Main site pages (.njk templates)
├── layouts/             # Page templates
│   └── base.njk        # Base layout template
└── assets/            # Static assets
    ├── js/           # JavaScript modules
    ├── scss/         # SASS stylesheets
    ├── images/       # Site images
    └── favicon/      # Favicon files
```

The project uses Nunjucks (`.njk`) as the templating language for pages and layouts. Content is organized as follows:

- **content/**: Contains all content-related files
  - **components/**: Reusable content components
  - **data/**: Site-wide data files and configurations
  - **pages/**: Main site pages written in Nunjucks
- **layouts/**: Page templates and layouts
  - **base.njk**: Base layout template that other pages extend from
- **utils/**: Utility functions and helpers
  - Contains date formatting and other helper functions
- **assets/**: Organized static assets including:
  - JavaScript modules for interactivity
  - SCSS stylesheets for custom styling
  - Images and favicon resources

## 🚀 Development

### Prerequisites

- Node.js (LTS version recommended)
- npm or yarn

### Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/furriesatucsd/howloween-website.git
   cd howloween-website
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```
   This will:
   - Clean the dist directory
   - Start Vite in watch mode
   - Run 11ty with hot-reloading
   - Open your default browser to the local development server

## 🔧 Available Scripts

- `npm run clean` - Clean the dist directory
- `npm run dev` - Start development server with hot reloading (cleans dist, runs Vite in watch mode, and starts 11ty server)
- `npm run build` - Build the site for production (cleans dist, builds with Vite, and runs 11ty)
- `npm run serve` - Build and preview the production site locally
- `npm run lint` - Run ESLint to check code quality in JavaScript/TypeScript files
- `npm run lint:fix` - Fix ESLint issues automatically
- `npm run format` - Format code using Prettier (JS, TS, JSON, MD, CSS, SCSS, NJK)
- `npm run format:check` - Check if files are properly formatted without making changes
- `npm run test` - Run Jest tests
- `npm run test:watch` - Run tests in watch mode
- `npm run validate` - Validate HTML output in the dist directory

## 🏗️ Building for Production

To build the site for production:

```bash
npm run build
```

The compiled site will be generated in the `dist` folder, ready for deployment.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- [Howloween Website](https://github.com/furriesatucsd/howloween-website) (coming soon!)
- [GitHub Repository](https://github.com/furriesatucsd/howloween-website) (you are here)
