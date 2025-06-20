
<div align="center">
  <img src="src/assets/logos/RISClogo-whiteoutline.svg" style="height:80%;" alt="RISc Logo" align="center" />
</div>

---

This is the RISc Lab website, built using Atro with the Atrogon template.

## Features

### Folder Structure
Most of everything you will need to update is in the src/content and src/assets folders.

.
├── LICENSE
├── README.md
├── astro.config.mjs
├── astrogon-docs
├── package-lock.json
├── package.json
├── postcss.config.js
├── public
│   ├── CNAME
│   ├── favicon
│   ├── fonts
│   ├── robots.txt
│   └── site.webmanifest
├── src
│   ├── assets
│   │   ├── carousel
│   │   ├── convert_imgs_webp.sh
│   │   ├── logos
│   │   │   ├── I-risc.webp
│   │   │   ├── R-risc.webp
│   │   │   ├── RISClogo-whiteoutline.svg
│   │   │   ├── Sc-risc.webp
│   │   │   ├── collaborators
│   │   │   └── funding
│   │   ├── news
│   │   ├── people
│   │   └── publications
│   │       └── teasers
│   ├── components
│   │   ├── awards
│   │   ├── base
│   │   ├── common
│   │   ├── home
│   │   ├── news
│   │   ├── not-found
│   │   ├── people
│   │   ├── publications
│   │   └── search
│   ├── content
│   │   ├── about
│   │   ├── awards
│   │   ├── config.ts
│   │   ├── home
│   │   ├── news
│   │   ├── people
│   │   │   ├── -index.md
│   │   │   ├── masters
│   │   │   ├── phd
│   │   │   ├── professors
│   │   │   └── undergraduates
│   │   └── publications
│   ├── env.d.ts
│   ├── lib
│   ├── pages
│   ├── scripts
│   ├── styles
│   └── types
├── tailwind.config.js
└── tsconfig.json



- Blog
  - Implements **Categories** and **Tags**, for easy filtering and searching
- Documentation
  - **Multi-level** document structure
  - Toggleable **Doc Browser** sidebar
  - Toggleable **Table of Contents** sidebar
- Recipes
  - Demonstrates a highly **templated structure**
- Authors - A collection that can **link entries across collections** by the Author field
- Poetry - A trim interface for a lightweight collection, demonstrating pagination over the content pages
- Index Cards - A variation on the "Poetry" layout, where all content is kept in a single file, and displayed in a single page
- And more:
  - Homepage
  - About/Bio
  - Portfolio
  - Terms and Conditions
  - 404 page

#### Content Components & Features

- **Accordion**/collapsible section
- **Tabs** section
- **Code Block** with syntax highlighting
- **Quote Block**
- **Notice Blocks** - note, tip, info, & warning
- **Embedded YouTube Video**
- Integrated **LaTeX** support for inline and block mathematical expressions
- All the standard **MD/MDX** features, including footnotes, tables, and more

### Additional Features

- Comprehensive **Light Mode** and **Dark Mode** support, with automatic detection of system preference
- **Searchablility** over all content you choose to include
- **Adaptive Layout** for all screen sizes, from phone a to a desktop monitor
- **Tool Tips** that can be added seamlessly to any interactable element
- **Breadcrumbs** for rapid navigation
- Auto-populating **Related Content** section available for any content collection
- Auto-calculating **Reading Time** available for any content collection
- Togglable **Frosted Glass** effect on all components
- Easily customizable color scheme and typography
- Animated component **Transitions** for an elegant flourish
- **Pagination** for any content collection
- Component for **Social Media** sharing
- Built-in patterns for **Search Engine Optimization**

Every one of these features was designed with modularity and customizability in mind, for the smoothest development experience possible. For more details, see [docs/customization.md](docs/customization.md).

## Recommended Technologies

- [Git](https://git-scm.com)
- [Node Version Manager](https://github.com/nvm-sh/nvm)
- [Visual Studio Code](https://code.visualstudio.com/)

See [docs/tech-stack.md](docs/tech-stack.md) for more details.

## Development Instructions

1. Fork this repository to your own GitHub account, then clone it to your local machine
2. Use Node 22: `nvm install 22` or `nvm use 22`
3. From the project directory, install Node dependencies: `npm install`
4. From the project directory, build: `npm run dev`
5. See your changes live at `http://localhost:4321`

## License

Astrogon is licensed under the [MIT License](LICENSE).

## Acknowledgments

This template was originally inspired by the structures of [zeon-studio](https://github.com/zeon-studio)'s [astroplate](https://github.com/zeon-studio/astroplate), [jordienr](https://github.com/jordienr)'s [astro-design-system](https://github.com/jordienr/astro-design-system) and [TheOtterlord](https://github.com/TheOtterlord)'s [manual](https://github.com/TheOtterlord/manual).

## Sponsorship

[reednel](https://github.com/reednel) has dedicated hundreds of hours to building this template, and continues to maintain and improve on it. This software is fully Free and Open Source, but if you find value in it, a small donation [[here](https://github.com/sponsors/reednel)] would be warmly appreciated.
