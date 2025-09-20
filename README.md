# Traceloop AI Website

This repository contains the official website for Traceloop AI, hosted on GitHub Pages.

## 🌐 Live Website

- **Main Site**: [traceloop-ai.dev](https://traceloop-ai.dev)
- **Developer Resources**: [traceloop-ai.io](https://traceloop-ai.io)
- **AI Community**: [traceloop-ai.ai](https://traceloop-ai.ai)

## 🚀 About Traceloop AI

Traceloop is a local-first observability platform for AI agents. Monitor, debug, and improve your LLM applications with confidence while keeping your data completely private and local.

### Key Features

- 🔍 **Complete Trace Visibility** - See every LLM call, tool use, and decision
- 🔒 **Local-First Privacy** - Your data never leaves your machine
- ⚡ **Zero Latency** - No network calls for tracing
- 🔧 **Framework Agnostic** - Works with LangChain, CrewAI, OpenAI, and more
- 📊 **Real-time Dashboard** - Beautiful web interface for trace visualization
- 🚀 **Production Ready** - From local development to cloud deployment

## 📁 Repository Structure

```
traceloop-website/
├── index.html          # Main landing page
├── styles.css          # CSS styling and responsive design
├── 404.html           # Custom 404 error page
├── CNAME              # GitHub Pages custom domain configuration
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## 🛠️ Local Development

### Prerequisites

- A modern web browser
- A local web server (optional, for testing)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/traceloop-ai/traceloop-website.git
   cd traceloop-website
   ```

2. **Open in browser**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Using Python's built-in server
   python -m http.server 8000
   # Then visit http://localhost:8000
   
   # Option 3: Using Node.js serve
   npx serve .
   ```

3. **Make changes**
   - Edit `index.html` for content changes
   - Edit `styles.css` for styling changes
   - Test locally before pushing

## 🚀 Deployment

This website is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### Manual Deployment

1. **Commit your changes**
   ```bash
   git add .
   git commit -m "Update website content"
   git push origin main
   ```

2. **GitHub Pages will automatically build and deploy**
   - Visit your repository settings
   - Go to Pages section
   - Ensure source is set to "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder

### Custom Domain Setup

The website is configured to use the custom domain `traceloop-ai.dev`:

1. **CNAME file** - Contains the custom domain
2. **DNS Configuration** - Point your domain to GitHub Pages
3. **SSL Certificate** - Automatically provided by GitHub Pages

## 🎨 Design System

### Colors

- **Primary Blue**: `#2563eb`
- **Purple Gradient**: `#7c3aed`
- **Text Dark**: `#1a1a1a`
- **Text Gray**: `#666`
- **Background**: `#ffffff`
- **Light Background**: `#f8fafc`

### Typography

- **Font Family**: Inter (Google Fonts)
- **Headings**: 600 weight
- **Body Text**: 400 weight
- **Code**: Monaco, Menlo, Ubuntu Mono

### Components

- **Buttons**: Primary (blue) and Secondary (outline)
- **Cards**: Rounded corners with subtle shadows
- **Code Blocks**: Dark theme with syntax highlighting
- **Navigation**: Fixed header with backdrop blur

## 📱 Responsive Design

The website is fully responsive and optimized for:

- **Desktop**: 1200px+ (full layout)
- **Tablet**: 768px - 1199px (adjusted grid)
- **Mobile**: < 768px (stacked layout)

## 🔧 Customization

### Adding New Sections

1. Add HTML structure to `index.html`
2. Add corresponding CSS to `styles.css`
3. Update navigation links if needed

### Updating Content

1. Edit the relevant sections in `index.html`
2. Update any hardcoded values
3. Test locally before deploying

### Styling Changes

1. Modify `styles.css`
2. Use the existing design system
3. Ensure responsive behavior
4. Test across different screen sizes

## 📊 Analytics & Monitoring

The website includes:

- **Performance monitoring** via GitHub Pages
- **Custom 404 page** for better user experience
- **SEO optimization** with proper meta tags
- **Accessibility features** for screen readers

## 🤝 Contributing

We welcome contributions to improve the website!

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-improvement
   ```
3. **Make your changes**
4. **Test locally**
5. **Commit your changes**
   ```bash
   git commit -m "Add amazing improvement"
   ```
6. **Push to your fork**
   ```bash
   git push origin feature/amazing-improvement
   ```
7. **Open a Pull Request**

### Contribution Guidelines

- Follow the existing design system
- Ensure responsive design
- Test across different browsers
- Keep the code clean and well-commented
- Update documentation as needed

## 📞 Support

- **Website Issues**: [GitHub Issues](https://github.com/traceloop-ai/traceloop-website/issues)
- **Traceloop Project**: [Main Repository](https://github.com/traceloop-ai/traceloop)
- **Documentation**: [traceloop-ai.dev](https://traceloop-ai.dev)

## 📄 License

This website is part of the Traceloop AI project and is licensed under the Apache License 2.0. See the [main repository](https://github.com/traceloop-ai/traceloop) for details.

---

Built with ❤️ for the AI community
