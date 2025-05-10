# 🧠 NERV — Networked Expressive Resource Vault

NERV is a centralized headless CMS built with Strapi, designed to power a constellation of websites, apps, services, and digital rituals. It serves as the sovereign backend for the Strong Hands, Soft Heart ecosystem — delivering structured content across domains in Markdown, HTML, and JSON via secure, flexible APIs.

This is more than just a CMS.

NERV is the central nervous system of a mythic creator's network. LOL

## 🔧 Features (WIP/TO-DO!!!)

- Content Types for Posts, Categories, Users, Pages, and Social Links
- Multi-site support with siteId scoping for filtering pages/content
- API-ready delivery (REST and GraphQL out of the box)
- Markdown + Media Support for modern publishing workflows
- User-based roles and relations for collaborative publishing
- Headless delivery to Astro, React, static sites, or mobile apps

## 🗺️ Use Cases

- Feed content to [StrongVault], your Obsidian-inspired public digital archive
- Power rich media pages and glossaries for your branded projects
- Host universal social profiles, page content, and rituals across domains
- Deliver structured data to frontends hosted on Vercel, Netlify, or GitHub Pages
- Create internal or public APIs for collaborators, mentees, or automation tools

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18.0.0 and <= 22.x.x
- npm >= 6.0.0

### Installation

```bash
npm install
```

### Development

Start your Strapi application with autoReload enabled:

```bash
npm run develop
# or
yarn develop
```

### Production

Start your Strapi application with autoReload disabled:

```bash
npm run start
# or
yarn start
```

### Build

Build your admin panel:

```bash
npm run build
# or
yarn build
```

### Database Seeding

To seed the database with example data:

```bash
npm run seed:example
# or
yarn seed:example
```

## ⚙️ Project Structure

```
src/
├── api/          # API endpoints and controllers
├── components/   # Reusable components
├── extensions/   # Strapi extensions
└── admin/        # Admin panel customizations
```

## 📦 Dependencies

- Strapi v5.13.0
- React v18
- TypeScript
- SQLite (better-sqlite3)

## 📝 License

This project is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE).

## 📚 Learn more

- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials
- [Strapi blog](https://strapi.io/blog) - Official Strapi blog

## ✨ Community

- [Discord](https://discord.strapi.io) - Strapi community
- [Forum](https://forum.strapi.io/) - Strapi forum
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - Curated list of Strapi resources

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
