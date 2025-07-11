<<<<<<< HEAD
# 🌐 Public Directory - Portfolio Showcase

A comprehensive portfolio showcasing multiple web applications including AI-powered tools, data visualization platforms, business intelligence dashboards, and strategic analysis tools. Built with modern web technologies including React, TypeScript, Vite, and responsive design principles.

![Portfolio](https://img.shields.io/badge/Portfolio-2025-blue.svg)
![Technologies](https://img.shields.io/badge/Tech-React%20%7C%20TypeScript%20%7C%20Vite%20%7C%20D3.js-brightgreen.svg) 
![Mobile](https://img.shields.io/badge/Mobile-Optimized-green.svg)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Ready-purple.svg)

## 🚀 Live Demo

**🔗 Main Portfolio**: [View Portfolio](./)

Access all applications through the main portfolio dashboard with beautiful animations, theme switching, and mobile-optimized navigation.

## 📱 Applications Overview

### 🤖 AI-Powered Applications

#### 🎥 [DeepTube](./deeptube/)
**YouTube Video Analysis Platform**
- **AI-Powered Analysis**: Video content understanding using Google Gemini
- **Multiple Analysis Types**: Summary, transcript, questions, and custom prompts
- **Interactive Chat**: Ask follow-up questions about video content
- **Example Gallery**: Pre-loaded video examples

#### 👁️ [OSEE](./osee/)
**Visual Content Analysis Tool**
- **Multi-format Support**: Images, documents, and visual content analysis
- **AI Integration**: Powered by Google Gemini for intelligent insights
- **File Processing**: Drag-and-drop interface with queue management
- **Theme Support**: Dark/light mode with modern UI

#### 🎤 [Meeting Agent](./meeting-agent/)
**Meeting Analysis & Documentation**
- **Audio Processing**: Meeting recording analysis
- **AI Transcription**: Automated meeting summaries
- **Action Items**: Extract key decisions and follow-ups
- **Modern Interface**: React-based with responsive design

#### 📊 [Dictator](./dictator/)
**Content Strategy Assistant**
- **Content Analysis**: Strategic content recommendations
- **AI Insights**: Data-driven decision making
- **Interactive Dashboard**: Real-time analytics
- **Export Features**: Multiple output formats

### 📈 Data Visualization & Analytics

#### 🌍 [Country Data Visualization](./country-data/)
**Interactive Global Dashboard**
- **195+ Countries**: Comprehensive global dataset
- **D3.js Visualizations**: Interactive scatter plots and charts
- **Multi-dimensional Analysis**: GDP, population, economic freedom, political systems
- **React + TypeScript**: Modern architecture with Material-UI
- **Real-time Filtering**: Dynamic search and filter capabilities

#### 🔎 [Event Hunter](./event-hunter/)
**Global Events Discovery Platform**
- **200+ Events**: Comprehensive event database for 2025
- **Multi-Industry Coverage**: Technology, Healthcare, Finance, Energy, Tourism
- **Multi-Language Support**: English, Arabic, Persian/Farsi with RTL support
- **Advanced Search**: Filter by industry, country, date, and status

#### 🏢 [Companies Data](./companies-data/)
**B2B Intelligence Platform**
- **80+ Companies**: Strategic business database for UAE & Oman
- **15+ Sectors**: Finance, energy, telecommunications, and more
- **AI Opportunities**: Mapped potential for each company
- **Interactive Filtering**: Search by sector, location, size, priority

### 📊 Strategic Analysis

#### 🎯 [Israel-Iran Crisis Dashboard](./israel-iran-war/)
**Strategic Analysis Platform**
- **Game Theory Framework**: Strategic decision analysis
- **Interactive Polling**: Community sentiment tracking
- **Multi-Language**: English, Arabic, Persian support
- **Real-time Data**: Dynamic probability calculations

#### 📚 [Gemini JS SDK Documentation](./gemini-js-sdk-doc/)
**Developer Resource Hub**
- **SDK Examples**: Practical implementation guides
- **Interactive Demos**: Live code examples
- **Documentation**: Comprehensive API reference
- **Getting Started**: Quick setup tutorials

### 🔧 Additional Tools

#### 📄 [CV/Resume](./cv/)
**Professional Portfolio**
- **Interactive Resume**: Modern web-based CV
- **Responsive Design**: Mobile-optimized layout
- **Professional Showcase**: Skills and experience highlight

#### 📊 [Business Data](./business-data/)
**Business Analytics Hub**
- **AI Scaling Analysis**: Business growth insights
- **Listings Impact**: Market analysis tools
- **Strategic Planning**: Data-driven business decisions

## 🏗️ Architecture Overview

### Monorepo Structure
This repository uses npm workspaces to manage multiple React/TypeScript applications:

- **Workspace Projects**: deeptube, osee, meeting-agent, dictator, country-data, gemini-js-sdk-doc
- **Static Projects**: event-hunter, companies-data, israel-iran-war, business-data, cv
- **Shared Dependencies**: Common build tools and deployment configuration

### Technology Stack
- **Frontend Framework**: React 18+ with TypeScript
- **Build Tool**: Vite (for all React projects)
- **UI Libraries**: Material-UI (@mui), custom components
- **Data Visualization**: D3.js, Chart.js, Recharts
- **AI Integration**: Google Gemini API
- **Styling**: CSS Modules, responsive design, glass morphism effects
- **State Management**: React hooks, local state
- **Deployment**: GitHub Pages with automated builds

## 🏗️ Project Structure

```
public-directory/
├── 📄 index.html                     # Main portfolio dashboard
├── 📄 README.md                      # This documentation
├── 📄 CLAUDE.md                      # AI assistant guidance
├── 📄 package.json                   # Workspace configuration
│
├── 🤖 AI-Powered Applications/
│   ├── 🎥 deeptube/                  # YouTube analysis (React/TS)
│   ├── 👁️ osee/                      # Visual content analysis (React/TS)
│   ├── 🎤 meeting-agent/             # Meeting analysis (React/TS)
│   ├── 📊 dictator/                  # Content strategy (React/TS)
│   └── 📚 gemini-js-sdk-doc/         # SDK documentation (React/TS)
│
├── 📈 Data Visualization/
│   ├── 🌍 country-data/              # Global data dashboard (React/TS)
│   ├── 🔎 event-hunter/              # Events platform (HTML/JS)
│   ├── 🏢 companies-data/            # Business intelligence (HTML/JS)
│   └── 🎯 israel-iran-war/           # Strategic analysis (HTML/JS)
│
├── 🔧 Additional Tools/
│   ├── 📄 cv/                        # Professional resume (HTML/JS)
│   └── 📊 business-data/             # Business analytics (HTML/JS)
│
└── 🚀 Deployment/
    ├── 📄 404.html                   # GitHub Pages 404 handler
    └── 📄 .github/workflows/         # CI/CD pipeline
```

## 🚀 Development & Deployment

### Quick Start
```bash
# Clone repository
git clone <repository-url>
cd public-directory

# Install all dependencies
npm install

# Build all React projects
npm run build

# Start local development
python -m http.server 8000
# Navigate to: http://localhost:8000
```

### Individual Project Development
**React/TypeScript Projects**:
```bash
cd [project-name]  # deeptube, osee, meeting-agent, dictator, country-data, gemini-js-sdk-doc
npm install
npm run dev      # Development server
npm run build    # Production build
npm run preview  # Preview build
```

**Static HTML Projects**:
- Open `index.html` directly or serve via local server
- No build process required

### Build Commands
```bash
# Build all workspace projects
npm run build

# Build specific projects
npm run build:deeptube
npm run build:osee
npm run build:country-data
npm run build:dictator
npm run build:meeting-agent
npm run build:gemini-js-sdk-doc

# Deploy to GitHub Pages
npm run deploy
```

## 🎯 Key Features

### 🤖 AI Integration
- **Google Gemini API**: Advanced AI capabilities across multiple applications
- **Multi-modal Analysis**: Text, image, video, and audio processing
- **Real-time Processing**: Interactive AI-powered insights
- **Custom Prompts**: Flexible AI interaction patterns

### 📊 Data Visualization
- **D3.js Charts**: Interactive and responsive visualizations
- **Real-time Filtering**: Dynamic data exploration
- **Multi-dimensional Analysis**: Complex data relationships
- **Export Capabilities**: Data download and sharing

### 🌐 Multi-language Support
- **Internationalization**: English, Arabic, Persian/Farsi
- **RTL Layout**: Right-to-left language support
- **Cultural Adaptation**: Localized user experiences
- **Font Optimization**: Language-specific typography

## 🎨 Design System

### Visual Identity
- **Glass Morphism**: Modern translucent design effects
- **Dark Theme**: Professional dark mode interface
- **Color Palette**: Consistent branding across applications
- **Typography**: Inter, Cairo, Vazirmatn fonts for multi-language support

### Responsive Design
- **Mobile-First**: Optimized for all screen sizes
- **Touch Friendly**: Appropriate touch targets and interactions
- **Performance**: Fast loading and smooth animations
- **Accessibility**: WCAG 2.1 compliance with screen reader support

### User Experience
- **Intuitive Navigation**: Clear information architecture
- **Progressive Enhancement**: Works without JavaScript
- **Error Handling**: Graceful error states and recovery
- **Loading States**: Clear feedback during data processing

## 📊 Data Sources & Analytics

### Global Coverage
- **195+ Countries**: Comprehensive international dataset
- **200+ Events**: Global events across multiple industries
- **80+ Companies**: Strategic business intelligence
- **Multiple Industries**: Technology, healthcare, finance, energy, tourism

### AI Capabilities
- **Google Gemini Integration**: Advanced AI processing
- **Multi-modal Analysis**: Text, image, video, audio
- **Real-time Processing**: Dynamic content analysis
- **Custom Insights**: Tailored AI responses

### Interactive Features
- **Real-time Filtering**: Dynamic data exploration
- **Multi-language**: English, Arabic, Persian support
- **Export Functions**: Data download capabilities
- **Responsive Charts**: Mobile-optimized visualizations

## 🔧 Configuration

### Environment Setup
**Google Gemini API**: Required for AI-powered applications
```env
# Add to individual React project .env files
VITE_GEMINI_API_KEY=your_api_key_here
```

### Build Configuration
- **Vite**: Modern build tool for React projects
- **TypeScript**: Type safety and enhanced development
- **GitHub Pages**: Base path configuration for deployment
- **Workspace Management**: npm workspaces for monorepo structure

### Deployment
- **GitHub Pages**: Automated deployment via GitHub Actions
- **Static Hosting**: Compatible with Netlify, Vercel, Surge.sh
- **Custom Servers**: Standard static file serving

## 🛠️ Development Guidelines

### Code Standards
- **TypeScript**: Use TypeScript for all React projects
- **ESLint**: Follow configured linting rules
- **Responsive Design**: Mobile-first approach
- **Accessibility**: WCAG 2.1 compliance
- **Performance**: Optimize for fast loading

### Project Organization
- **Monorepo Structure**: Use npm workspaces
- **Component Architecture**: Reusable, modular components
- **State Management**: React hooks and local state
- **Error Handling**: Comprehensive error boundaries
- **Testing**: Unit and integration tests where applicable

## 📄 License

This project is for educational and portfolio purposes. Individual data sources and company information are publicly available and compiled for demonstration.

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Follow** development guidelines and code standards
4. **Test** across multiple browsers and devices
5. **Submit** a Pull Request with detailed description

## 📧 Contact

For questions, suggestions, or collaboration opportunities, please create an issue in this repository.

---

## 🏆 Project Highlights

- **🤖 AI Integration**: Multiple AI-powered applications with Google Gemini
- **📊 Data Visualization**: Interactive charts and real-time analytics
- **🌍 Global Scope**: International coverage with multi-language support
- **📱 Mobile Excellence**: Responsive design optimized for all devices
- **⚡ Modern Stack**: React, TypeScript, Vite, and latest web technologies
- **♿ Accessibility**: Inclusive design following WCAG guidelines
- **🚀 Performance**: Fast loading with optimized build processes

**Built with modern web technologies and AI integration**

---

**Updated**: January 2025 | **Applications**: 12+ | **Stack**: React + TypeScript + AI
=======
# public
All my public projects in one repo
>>>>>>> b1c8a75854333880f1f1e94c3e2bc73bfa65e36e
