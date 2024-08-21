![Hexo](https://img.shields.io/badge/Hexo-0E83CD?style=for-the-badge&logo=hexo&logoColor=white)
![Node.js](https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Google Analytics](https://img.shields.io/badge/Google%20Analytics-E37400?style=for-the-badge&logo=google%20analytics&logoColor=white)
# MapleRoyals Promotion Site
This is a website built using the [Hexo](https://hexo.io/ "link") framework, intended for non-profit promotion of MapleRoyals to the Chinese-speaking community.

## Directory Structure
```
.
├── _config.yml          # Hexo global configuration file
├── package.json         # Project dependency configuration
├── public/              # Compiled static files (should not be version controlled)
├── source/              # Original content files (Markdown, images, etc.)
├── themes/              # Custom theme folder
└── scaffolds/           # Default templates
```

### Installation and Setup
#### 1. Clone the repository:
```
git clone https://github.com/bolin0330/mapleRoyals-Node.js.git
cd mapleRoyals-Node.js
```

#### 2. Install dependencies:
Use pnpm to install the dependencies:
```
pnpm install
```

#### 3. Configure the site:
Update the *_config.yml* file according to your needs. You can set the site title, description, URL, Google Analytics tracking ID, and more.

#### 4. Preview locally:
Run the following commands to generate and start the Hexo server locally:
```
pnpm hexo generate
pnpm hexo server
```
