## Hi 👋, I'm Abhinav

I'm a college student who loves bringing wireframes and static designs to life using `React/SolidJS, TypeScript`, and `Tailwind CSS`. 

I enjoy building things for the web, but I honestly spend just as much time (and have just as much fun) debugging. I have a good amount of experience untangling weird JS/CSS issues, and I'm totally comfortable jumping into the terminal to write bash scripts or tinker with Linux systems to get things working right.

### Featured Project

#### [Cosmic Mod Manager](https://github.com/PuzzlesHQ/cosmic-mod-manager)
*A comprehensive, full-stack platform for hosting mods, resource packs, and shaders for the game Cosmic Reach.*

This is the largest and most complex project I have done, architected as a monorepo to handle large-scale data and dynamic user interactions. 
- **Frontend:** Built with `React` for dynamic client-side interactions, server-rendered with `React-Router v7`, styled completely with `Tailwind CSS`, and fully typed with `TypeScript`. The UI is responsive and has localization support.
- **Backend & API:** Written in `TypeScript` using `Hono` running on the `Bun` runtime.
- **Database:** Uses `Postgres` as the primary database managed using `Prisma`, `Redis` for high-speed caching/rate-limiting, and `Meilisearch` to provide fast, typo-tolerant search across thousands of mods.
- **CI/CD:** Leverages webhooks triggered by git events for continuous deployment and `GitHub Actions` for running tests and keeping Game versions list updated.
- **Infrastructure:** Self-hosted on a VPS, proxied through Cloudflare, with Fastly configured for static asset delivery and caching.

---

### Other Projects

- **[TS Locale Editor](https://github.com/Abhinav5383/ts-locale-editor)**
    A visual web editor for JS/TS-based translation files. Built with `SolidJS, TypeScript, and Babel`, it parses AST objects (including nested expressions) and safely assembles them back into code while preserving the original file structure.

- **[SBTE Result Viewer](https://github.com/Abhinav5383/sbte-result-viewer)**
    A tool built with `TypeScript` to automate the bulk downloading and parsing of SBTE diploma results. It extracts text from the PDF files, parses and saves it into a JSON file. The frontend part uses that to compile a standalone HTML page with all the JSON data embedded, gzipped + base64 encoded for small bundle size.

- **[Cisco Automagic](https://github.com/Abhinav5383/cisco-automagic)**
    A browser automation bot built with `TypeScript and Playwright` to automate the repetitive cisco coursework that my college forces to do for marks.


### Skills

- **Languages:** TypeScript, JavaScript, HTML/CSS
- **Frontend Frameworks:** React, SolidJS, Tailwind CSS, Next.js
- **Backend:** Express.js, Node.js, Bun, Hono, Prisma, Redis

- **Tools:** Vite, Git, GitHub Actions, Linux, SSH, Bash scripts, pm2, Caddy
- **Familiar with:** C, SQL (Postgres), Babel
- **Other things:** Self-hosting, Cloudflare, Fastly
