# 📋 shadcn/ui Cheatsheet

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GitHub Stars](https://img.shields.io/github/stars/shadcnstore/shadcn-cheatsheet?style=social)](https://github.com/shadcnstore/shadcn-cheatsheet)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Next.js](https://img.shields.io/badge/Next.js-15.5.2-000000?logo=next.js&logoColor=white)](https://nextjs.org/)```
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-Latest-000000)](https://ui.shadcn.com/)

> **Interactive Cheatsheet for shadcn/ui components with live previews, copy-paste ready code examples, and comprehensive documentation for 53 components.**

🚀 **Free & Open Source** by [**ShadcnStore**](https://shadcnstore.com) - Your gateway to premium UI components, dashboards, and templates.

<div align="center">

🎯 <a href="https://shadcnstore.com/docs/cheatsheet" target="_blank">**View Live Cheatsheet**</a> | 🧩 <a href="https://shadcnstore.com/blocks" target="_blank">**Explore Premium Blocks**</a> | 🖥️ <a href="https://shadcnstore.com/templates/dashboard/shadcn-dashboard-landing-template/dashboard" target="_blank">**Get Dashboard Template**</a>

</div>

---

## 📍 The hosted cheatsheet has moved

> **`cheatsheet.shadcnstore.com` now redirects to [shadcnstore.com/docs](https://shadcnstore.com/docs/cheatsheet)** (July 2026).
>
> The cheatsheet has been rebuilt inside the ShadcnStore documentation and rewritten for the current shadcn, which ships **Base UI** alongside Radix — this app's content is Radix-era. The replacement covers **61 components** with live demos, prop tables and accessibility notes, maintained alongside the rest of the docs.
>
> | Looking for | Go to |
> |---|---|
> | The one-page cheatsheet | **[shadcnstore.com/docs/cheatsheet](https://shadcnstore.com/docs/cheatsheet)** — every component with its install command |
> | A specific component | **[shadcnstore.com/docs/components](https://shadcnstore.com/docs/components/)** — e.g. [button](https://shadcnstore.com/docs/components/button), [calendar](https://shadcnstore.com/docs/components/calendar), [data-table](https://shadcnstore.com/docs/components/data-table) |
> | Base UI vs Radix | **[the comparison guide](https://shadcnstore.com/docs/components/base-ui-vs-radix)** |
>
> **This repository stays open source and MIT-licensed** — clone and run it locally exactly as before; only the hosted deployment redirects. Old URLs map 1:1: `/component/<name>`, and any variant beneath it, lands on that component's docs page.

---

## ✨ What's This?

The **shadcn/ui Cheatsheet** is the most comprehensive, interactive reference guide for shadcn/ui components available. Built by developers, for developers, it provides instant access to live component previews, copy-paste ready code snippets, and complete documentation for every shadcn/ui component.

Whether you're just getting started with shadcn/ui or you're a seasoned developer looking for quick reference, this Cheatsheet accelerates your development workflow and helps you build beautiful, accessible interfaces faster.

---

## 🔗 Live Cheatsheet

- **[Interactive cheatsheet](https://shadcnstore.com/docs/cheatsheet)** — every component with its install command, on one page
- **[Component reference](https://shadcnstore.com/docs/components/)** — live previews, variants, props and accessibility notes per component

> **Note**: this repo is the archived Radix-era build. The links above are the maintained version, and running this project locally still works.

---

## ✨ Key Features

### 🔥 **Complete Component Library**
- **53 Components** - Every shadcn/ui component this build covers
- **Live Previews** - Interactive component demonstrations
- **Multiple Variants** - All component variations and examples
- **Real-time Updates** - Always up-to-date with latest shadcn/ui releases

### 📋 **Developer-Focused Tools**
- **Copy-Paste Ready** - One-click code copying for components and examples
- **Installation Commands** - Package manager specific install commands (npm, pnpm, yarn, bun)
- **Import Statements** - Ready-to-use import statements
- **Usage Examples** - Practical implementation examples

### 🎨 **Advanced Features**
- **Theme Customizer** - Real-time theme switching and preview
- **Smart Search** - Find components instantly with fuzzy search
- **Category Filtering** - Browse by component categories
- **Keyboard Navigation** - Full keyboard accessibility
- **URL Bookmarking** - Direct links to specific components

### ⚡ **Performance & UX**
- **Lightning Fast** - Built with Next.js 15 & Turbopack
- **Responsive Design** - Mobile-first approach
- **Dark/Light Mode** - Beautiful theme switching
- **Smooth Animations** - Polished user experience
- **Scroll Position Memory** - Maintains scroll position during navigation

---

## � Quick Start

### Prerequisites

- **Node.js** 18+
- **pnpm** (recommended), npm, yarn, or bun

### 1. Clone & Install

```bash
# Clone the repository
git clone https://github.com/shadcnstore/shadcn-cheatsheet.git
cd shadcn-cheatsheet

# Install dependencies
pnpm install

# Start development server
pnpm dev
```

### 2. Access the Application

Open [http://localhost:3000](http://localhost:3000) in your browser. The maintained hosted version lives at [shadcnstore.com/docs/cheatsheet](https://shadcnstore.com/docs/cheatsheet).

### 3. Build for Production

```bash
# Build for production
pnpm build

# Start production server
pnpm start
```

---

## 📦 Available Components

### **Key Components Included**

- ✅ **Button** - Buttons with multiple variants and sizes
- ✅ **Input** - Text inputs with validation states
- ✅ **Select** - Dropdown select components
- ✅ **Dialog** - Modal dialogs
- ✅ **Sheet** - Side panels and drawers
- ✅ **Table** - Advanced data tables
- ✅ **Card** - Content cards with headers and footers
- ✅ **Navigation Menu** - Complex navigation with dropdowns
- ✅ **Calendar** - Date picker calendars
- ✅ **Accordion** - Collapsible content sections
- ✅ **Sonner Toast** - Notification toasts

*And 42+ more components covering all shadcn/ui functionality!*

---

## 🛠️ Development Commands

```bash
# Start development server with hot reload
pnpm dev

# Build for production
pnpm build

# Start production server
pnpm start

# Run linting
pnpm lint

# Run linting with auto-fix
pnpm lint --fix

# Type checking
pnpm type-check
```

---

## 📁 Project Structure

```text
📁 shadcn-cheatsheet/
├── 📁 app/                      # Next.js App Router
│   ├── 📄 layout.tsx           # Root layout
│   ├── 📄 page.tsx             # Homepage
│   ├── 📄 globals.css          # Global styles
│   └── 📁 api/                 # API routes
│       └── 📁 registry/        # Component registry API
├── 📁 components/              # React components
│   ├── 📁 ui/                  # shadcn/ui components
│   ├── 📁 layout/              # Layout components
│   ├── 📁 cards/               # Component preview cards
│   ├── 📁 search/              # Search functionality
│   └── 📁 theme-customizer/    # Theme customization
├── 📁 lib/                     # Utility libraries
│   ├── 📄 search.ts            # Fuzzy search logic
│   ├── 📄 registry.ts          # Component registry
│   └── 📄 utils.ts             # Utility functions
├── 📁 data/                    # Static data
│   └── 📄 components-simple.ts # Component definitions
├── 📁 registry/                # Component examples
│   └── 📁 default/
│       └── 📁 examples/        # Component example files
├── 📁 hooks/                   # Custom React hooks
├── 📁 types/                   # TypeScript definitions
└── 📁 public/                  # Static assets
```

---

## 🛠️ Tech Stack

### **Core Framework**

- **[Next.js 15](https://nextjs.org/)** - React framework with App Router
- **[React 19](https://reactjs.org/)** - Latest React with concurrent features
- **[TypeScript](https://www.typescriptlang.org/)** - Full type safety

### **UI & Styling**

- **[shadcn/ui](https://ui.shadcn.com/)** - Component library
- **[Radix UI](https://www.radix-ui.com/)** - Accessible primitives
- **[Tailwind CSS v4](https://tailwindcss.com/)** - Utility-first styling
- **[Lucide React](https://lucide.dev/)** - Beautiful icons

---

## � Usage & Navigation

### **Component Cards**
Each component card displays:
- Component name and description  
- Installation command for selected package manager
- Code variants with individual copy buttons
- Dependencies and documentation links
- Expand/collapse for detailed view

### **Package Manager Integration**
Switch between package managers using the tab interface:

```bash
# npm, # yarn, # pnpm, # bun
```

### **Search & Navigation**
- **Global Search** - Press `Ctrl+K` or `CMD+k` to open command palette
- **Category Filters** - Click category badges to filter components
- **Component Preview** - Click any component for live preview
- **Keyboard Navigation** - Use arrow keys in preview mode
- **Theme Customizer** - Real-time theme switching and customization

---

## 🌟 Why Use This Cheatsheet?

### **🚀 Speed Up Development**
- **Instant Reference** - No more digging through documentation
- **Copy-Paste Ready** - Get code snippets immediately
- **Live Previews** - See exactly how components look and behave
- **Complete Examples** - Real-world usage patterns

### **📚 Comprehensive Coverage**
- **Every Component** - Complete shadcn/ui library coverage
- **All Variants** - Every possible component variation
- **Up-to-Date** - Always current with latest releases
- **Best Practices** - Proper usage examples and patterns

### **🎯 Developer-Focused**
- **Keyboard Navigation** - Full accessibility support
- **Search Everything** - Find any component instantly
- **Mobile Ready** - Works perfectly on all devices
- **Performance Optimized** - Fast loading and smooth interactions

---

## 🚀 Take It Further with ShadcnStore

This free Cheatsheet is part of the **ShadcnStore** ecosystem! Discover more resources to accelerate your development:

### **🎁 Available Now**

#### **🖥️ [Opensource Dashboard Template](https://shadcnstore.com/templates/dashboard/shadcn-dashboard-landing-template/dashboard)**
Complete admin dashboard with 30+ pages, built with shadcn/ui:
- **2 Dashboard Variants** - Overview & Analytics dashboards
- **App Demos** - Mail, Tasks, Chat, Calendar applications
- **Authentication Pages** - Login, signup, password recovery
- **Settings Pages** - Account, billing, appearance management
- **Live Theme Customizer** - Real-time theme editing with tweakcn
- **Available in Vite & Next.js** - Choose your preferred framework

#### **🧩 [Premium UI Blocks](https://shadcnstore.com/blocks)**
150+ production-ready UI blocks for rapid development:
- **Application Blocks** - Dashboard components and layouts
- **Marketing Blocks** - Landing page sections and CTAs
- **E-commerce Blocks** - Shopping cart, product cards, checkout flows
- **Free Blocks** - No-cost starter components
- **Copy-Paste Ready** - Drop into any shadcn/ui project

### **🔜 Coming Soon**
- **Landing Page Collection** - Business-ready marketing templates  
- **E-commerce Templates** - Complete online store solutions
- **SaaS Starter Kits** - Full-stack application templates

### **💡 Perfect For**
- **SaaS Applications** - Complete dashboard and admin solutions
- **Marketing Websites** - Beautiful, conversion-optimized landing pages  
- **E-commerce Sites** - Professional online store interfaces
- **Internal Tools** - Admin panels and business applications

> **🎯 [Explore ShadcnStore](https://shadcnstore.com)** - Premium blocks, dashboards and templates for modern web applications.

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help make this Cheatsheet even better:

### **Ways to Contribute**

- 🐛 **Report Bugs** - Found an issue? [Create an issue](https://github.com/shadcnstore/shadcn-cheatsheet/issues)
- 💡 **Suggest Features** - Have ideas for improvements? We'd love to hear them!
- 🔧 **Submit Pull Requests** - Fix bugs, add features, or improve documentation
- ⭐ **Star the Repository** - Show your support and help others discover this project!

### **Getting Started**

1. **Fork the repository** - Click the fork button at the top of this page
2. **Clone your fork** - `git clone https://github.com/yourusername/shadcn-cheatsheet.git`
3. **Create a feature branch** - `git checkout -b feature/amazing-feature`
4. **Make your changes** - Add your improvements
5. **Test thoroughly** - Ensure everything works correctly
6. **Commit your changes** - `git commit -m 'Add amazing feature'`
7. **Push to your branch** - `git push origin feature/amazing-feature`
8. **Open a Pull Request** - Submit your changes for review

### **Development Guidelines**

- Use **TypeScript** for all new code
- Follow the existing **code style** and formatting
- Add **type definitions** for new components or props
- Test your changes across **different screen sizes**
- Write **clear, descriptive commit messages**
- Update **documentation** for new features

### **Component Guidelines**

When adding new components:
- Follow the existing **component structure** in `data/components-simple.ts`
- Create **example files** in `registry/default/examples/`
- Include **multiple variants** where applicable
- Add proper **TypeScript types**
- Test **accessibility** and **keyboard navigation**

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

**You are free to:**
- ✅ Use for personal and commercial projects
- ✅ Modify and distribute the code
- ✅ Include in your own projects
- ✅ Create derivative works

**Attribution to [ShadcnStore](https://shadcnstore.com) is appreciated but not required.**

---

## 🙏 Credits & Acknowledgments

This Cheatsheet is built on the foundation of incredible open-source projects and the amazing work of their maintainers:

- **[shadcn](https://twitter.com/shadcn)** - For creating the amazing shadcn/ui component library
- **[shadcn/ui](https://ui.shadcn.com)** - Beautiful and accessible React components
- **[Radix UI](https://www.radix-ui.com)** - Low-level accessible UI primitives
- **[Tailwind CSS](https://tailwindcss.com)** - Utility-first CSS framework
- **[Next.js](https://nextjs.org)** - The React framework for production
- **[Vercel](https://vercel.com)** - Platform for frontend frameworks and static sites
- **[Lucide](https://lucide.dev)** - Beautiful & consistent icon library

---

## 📞 Support & Community

### **Get Help**

- 🐛 **Bug Reports** - [GitHub Issues](https://github.com/shadcnstore/shadcn-cheatsheet/issues)
- 💬 **Feature Requests** - [GitHub Discussions](https://github.com/shadcnstore/shadcn-cheatsheet/discussions)

### **Stay Connected**

- 🌐 **Website** - [ShadcnStore.com](https://shadcnstore.com)
- 🐦 **Twitter** - [@shadcnstore](https://twitter.com/shadcnstore)

### **Found This Helpful?**

- ⭐ **Star this repository** to show your support
- 🔄 **Share with your team** and fellow developers
- 🐦 **Tweet about it** to help others discover this resource
- ❤️ **Sponsor the project** to help us maintain and improve it

---

## ⭐ Star this repo if it helped you

Every star helps more developers discover this resource

[![Star History Chart](https://api.star-history.com/svg?repos=shadcnstore/shadcn-cheatsheet&type=Date)](https://star-history.com/#shadcnstore/shadcn-cheatsheet&Date)

[![ShadcnStore](https://img.shields.io/badge/Built%20by-ShadcnStore-blue?style=for-the-badge&logo=react&logoColor=white)](https://shadcnstore.com)

*A free & open-source project by **[ShadcnStore](https://shadcnstore.com)** - Premium UI components, dashboards and templates for modern web development.*

Made with ❤️ for the React and shadcn/ui community
