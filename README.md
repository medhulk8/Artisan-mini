# Artisan Mini - AI-Powered Craft Marketing Assistant

<div align="center">

  **🌐 [Live Demo](https://artisan-psi-wheat.vercel.app/)**

  *Empowering artisans with AI-driven marketing strategies*

  [![React](https://img.shields.io/badge/React-18.3-61dafb?logo=react&logoColor=white)](https://reactjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178c6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Vite](https://img.shields.io/badge/Vite-5.4-646cff?logo=vite&logoColor=white)](https://vitejs.dev/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06b6d4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

  *An AI-powered chat application designed to help artisans and craftspeople market their traditional crafts in the digital age.*

</div>

---

## 📋 Overview

Artisan Mini is a beautiful, modern web application that leverages AI to provide personalized digital marketing strategies for artisans and craftspeople. Whether you're a potter, weaver, woodworker, or any other craft professional, Artisan Mini helps you navigate the digital marketing landscape with budget-aware, actionable recommendations.

## ✨ Features

- **🤖 AI-Powered Marketing Strategies** - Get personalized digital marketing strategies powered by Google Gemini API
- **💰 Budget-Aware Recommendations** - Strategies tailored to your specific budget constraints
- **💬 Interactive Chat Interface** - Natural conversation flow with intelligent AI assistant
- **🎯 Strategy Selection** - Choose from multiple marketing approaches based on your needs
- **📱 Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **🎨 Modern UI** - Clean, artisan-inspired design with warm, earthy color palette
- **🌍 Multi-language Support** - Automatic language detection and responses

## 🚀 Quick Start

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager
- Google Gemini API key ([Get one here](https://makersuite.google.com/app/apikey))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/medhulk8/Artisan-mini.git
   cd artisan-mini
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```

   Then edit `.env` and add your Gemini API key:
   ```env
   VITE_GEMINI_API_KEY=your_actual_gemini_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**

   Navigate to `http://localhost:8080`

## 🛠️ Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build optimized production bundle |
| `npm run build:dev` | Build in development mode |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint for code quality checks |

## 🏗️ Tech Stack

### Core Technologies
- **React 18** - Modern UI library with hooks
- **TypeScript** - Type-safe JavaScript
- **Vite** - Next-generation frontend tooling
- **Tailwind CSS** - Utility-first CSS framework

### UI Components & Styling
- **Radix UI** - Accessible component primitives
- **Lucide React** - Beautiful icon library
- **CSS Variables** - Custom theming system

### State & Routing
- **React Hooks** - Built-in state management
- **React Router** - Client-side routing
- **TanStack Query** - Server state management

### AI Integration
- **Google Gemini API** - Advanced AI language model for generating marketing strategies

## 📁 Project Structure

```
artisan-mini/
├── public/                 # Static assets
│   ├── robots.txt         # SEO configuration
│   └── placeholder.svg    # Placeholder image
├── src/
│   ├── components/        # React components
│   │   ├── ui/           # Reusable UI components
│   │   ├── ChatView.tsx  # Main chat interface
│   │   ├── ChatMessage.tsx
│   │   ├── ChatInput.tsx
│   │   ├── ChatHeader.tsx
│   │   ├── DetailsGate.tsx
│   │   ├── StrategySelection.tsx
│   │   └── StrategyDetails.tsx
│   ├── hooks/            # Custom React hooks
│   │   ├── useArtisanChat.ts
│   │   ├── use-mobile.tsx
│   │   └── use-toast.ts
│   ├── lib/              # Utility functions
│   │   └── utils.ts
│   ├── pages/            # Page components
│   │   └── Index.tsx
│   ├── utils/            # Helper utilities
│   │   └── languageDetection.ts
│   ├── App.tsx           # Main app component
│   ├── main.tsx          # Application entry point
│   └── index.css         # Global styles
├── .env.example          # Environment variables template
├── components.json       # shadcn/ui configuration
├── tailwind.config.ts    # Tailwind CSS configuration
├── vite.config.ts        # Vite configuration
└── package.json          # Project dependencies
```

## 🎨 Design System

The application uses a custom design system inspired by traditional artisan crafts:

- **Primary Color**: Terracotta (#e07856) - Warm, earthy tone
- **Typography**: Clean, readable fonts optimized for accessibility
- **Components**: Consistent, reusable UI components from Radix UI
- **Layout**: Mobile-first responsive design
- **Theme**: Artisan-inspired with natural, warm color palette

## 🔧 Configuration

### Environment Variables

The application requires the following environment variables:

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_GEMINI_API_KEY` | Google Gemini API key | Yes |

**Important**: Never commit your `.env` file to version control - it's already included in `.gitignore`

### Getting Your API Key

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in with your Google account
3. Create a new API key
4. Copy the key to your `.env` file

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

This creates a `dist` folder with optimized production files.

### Deploy to Vercel (Recommended)

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

3. **Set environment variable**

   In your Vercel project settings, add:
   - Key: `VITE_GEMINI_API_KEY`
   - Value: Your Google Gemini API key

### Other Platforms

For other platforms (Netlify, Cloudflare Pages, etc.), ensure you set the `VITE_GEMINI_API_KEY` environment variable according to your platform's documentation.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. Push to the branch
   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **[Vite](https://vitejs.dev/)** - Lightning-fast build tool
- **[Radix UI](https://www.radix-ui.com/)** - Accessible component primitives
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Google Gemini](https://ai.google.dev/)** - Advanced AI language model
- **[Lucide Icons](https://lucide.dev/)** - Beautiful open-source icons

## 💡 Features Roadmap

- [ ] User authentication and saved conversations
- [ ] Export marketing strategies as PDF
- [ ] Multi-language interface
- [ ] Integration with social media platforms
- [ ] Analytics dashboard
- [ ] Custom branding options

## 📞 Support

If you encounter any issues or have questions:

- **Issues**: [GitHub Issues](https://github.com/medhulk8/Artisan-mini/issues)
- **Discussions**: [GitHub Discussions](https://github.com/medhulk8/Artisan-mini/discussions)

---

<div align="center">

  **Made with ❤️ for artisans and craftspeople worldwide**

  [Live Demo](https://artisan-psi-wheat.vercel.app/) • [Report Bug](https://github.com/medhulk8/Artisan-mini/issues) • [Request Feature](https://github.com/medhulk8/Artisan-mini/issues)

</div>
