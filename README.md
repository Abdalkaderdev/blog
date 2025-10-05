# Abdalkader's Blog

A modern, performant personal blog built with Hexo.js and the Icarus theme, featuring technical tutorials, project showcases, and industry insights.

## 🚀 Features

- **Modern Design**: Clean, professional layout matching abdalkader.dev
- **Performance Optimized**: Fast loading times with optimized assets
- **SEO Ready**: Proper meta tags, sitemap, and structured data
- **Responsive**: Mobile-first design that works on all devices
- **Dark/Light Theme**: Automatic theme switching support
- **Code Highlighting**: Syntax highlighting for multiple languages
- **Search**: Built-in search functionality
- **RSS Feed**: Automatic RSS/Atom feed generation
- **Comments**: Disqus integration for reader engagement

## 🛠️ Tech Stack

- **Framework**: Hexo.js v8.0.0
- **Theme**: Icarus (customized)
- **Deployment**: Vercel/Netlify/GitHub Pages
- **Content**: Markdown with frontmatter
- **Styling**: Custom CSS with CSS variables
- **Icons**: Font Awesome
- **Analytics**: Google Analytics ready

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd abdalkader-blog
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install Hexo CLI globally** (if not already installed)
   ```bash
   npm install -g hexo-cli
   ```

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server with drafts
- `npm run server` - Start development server
- `npm run build` - Generate static files
- `npm run clean` - Clean generated files
- `npm run start` - Clean, build, and serve
- `npm run new` - Create new post

### Creating New Posts

```bash
# Create a new post
hexo new "Your Post Title"

# Create a new page
hexo new page "page-name"

# Create a draft
hexo new draft "Draft Title"
```

### Post Frontmatter Template

```yaml
---
title: "Your Post Title"
date: 2024-12-20 10:00:00
categories: [Web Development]
tags: [React, JavaScript, Tutorial]
excerpt: "Brief description of your post"
cover: /images/post-cover.jpg
toc: true
draft: false
---
```

## 🎨 Customization

### Theme Configuration

The main theme configuration is in `_config.icarus.yml`. Key sections:

- **Site Information**: Title, description, author details
- **Navigation**: Menu items and external links
- **Sidebar Widgets**: Profile, categories, tags, recent posts
- **Social Links**: GitHub, LinkedIn, email
- **Comments**: Disqus configuration
- **Analytics**: Google Analytics setup

### Custom Styling

Custom CSS is located in `source/css/custom.css` and includes:

- CSS custom properties for theming
- Typography improvements
- Component styling
- Responsive design
- Dark mode support

### Color Scheme

The blog uses a professional color palette:

- **Primary**: #2563eb (Blue)
- **Secondary**: #00acc1 (Cyan)
- **Text**: #1f2937 (Dark Gray)
- **Background**: #ffffff (White)

## 🚀 Deployment

### Vercel (Recommended)

1. **Connect your repository to Vercel**
2. **Set build command**: `npm run vercel-build`
3. **Set output directory**: `public`
4. **Deploy automatically on push to main**

### Netlify

1. **Connect your repository to Netlify**
2. **Set build command**: `npm run build`
3. **Set publish directory**: `public`
4. **Deploy automatically on push to main**

### GitHub Pages

1. **Install hexo-deployer-git**:
   ```bash
   npm install hexo-deployer-git --save
   ```

2. **Configure deployment in `_config.yml`**:
   ```yaml
   deploy:
     type: git
     repo: https://github.com/username/username.github.io.git
     branch: main
   ```

3. **Deploy**:
   ```bash
   npm run deploy
   ```

## 📝 Content Guidelines

### Writing Standards

- **Length**: 800-2000 words for tutorials, 400-800 for insights
- **Structure**: Use clear headings and subheadings
- **Code Examples**: Include working, tested code with comments
- **Images**: Optimize for web (<500KB per image)
- **SEO**: Target 1-2 primary keywords naturally

### Content Categories

1. **Technical Tutorials** - Step-by-step guides
2. **Project Showcases** - Portfolio pieces and case studies
3. **Industry Insights** - Trends, opinions, and analysis
4. **Learning Experiences** - Personal growth and lessons learned
5. **Tools & Resources** - Reviews and recommendations

## 🔍 SEO Features

- **Sitemap**: Auto-generated XML sitemap
- **RSS Feed**: Atom feed for subscribers
- **Meta Tags**: Proper Open Graph and Twitter Card tags
- **Structured Data**: JSON-LD for articles
- **Performance**: Optimized loading and Core Web Vitals

## 📊 Analytics

The blog is configured for Google Analytics. To enable:

1. **Get your GA tracking ID**
2. **Add to `_config.icarus.yml`**:
   ```yaml
   plugins:
     google_analytics:
       tracking_id: 'GA_TRACKING_ID'
   ```

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch**
3. **Make your changes**
4. **Test locally**
5. **Submit a pull request**

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙋‍♂️ Support

For questions or support:

- **Email**: hello@abdalkader.dev
- **GitHub**: [github.com/abdalkaderdev](https://github.com/abdalkaderdev)
- **LinkedIn**: [linkedin.com/in/abdalkaderdev](https://linkedin.com/in/abdalkaderdev)
- **Instagram**: [instagram.com/abdalkader.dev](https://www.instagram.com/abdalkader.dev)

---

Built with ❤️ using [Hexo.js](https://hexo.io) and [Icarus Theme](https://github.com/ppoffice/hexo-theme-icarus)

<!-- Deployment trigger -->