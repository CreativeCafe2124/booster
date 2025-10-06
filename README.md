# Booster

AI-powered website builder and code generation platform. An innovative application for creating React apps instantly using artificial intelligence. Built on the foundation of modern web technologies with sandboxed development environments.

<!-- Demo GIF temporarily disabled -->
<!-- <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExODAwZGJzcDVmZGYxc3MyNDUycTliYnAwem1qbzhtNHh0c2JrNDdmZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LMYzMkNmOecj3yFw81/giphy.gif" alt="Booster Demo" width="100%"/> -->

## Features

✨ **AI-Powered Code Generation** - Generate complete React applications using natural language
🔍 **Web Scraping** - Extract and recreate existing websites with intelligent content analysis
🎨 **Design Styles** - Multiple design aesthetics (Modern, Glassmorphism, Neumorphism, etc.)
🏗️ **Sandboxed Development** - Safe, isolated environments for code execution
⚡ **Real-time Preview** - Instant visual feedback during development
🔧 **Interactive Editing** - AI-assisted code refinement and customization

## Setup

1. **Clone & Install**
```bash
git clone https://github.com/CreativeCafe2124/Booster.git
cd Booster
npm install
```

2. **Environment Configuration**

Create a `.env` file with your API keys:

```env
# =================================================================
# REQUIRED
# =================================================================
FIRECRAWL_API_KEY=your_firecrawl_api_key    # https://firecrawl.dev

# =================================================================
# AI PROVIDER - Choose your LLM (at least one required)
# =================================================================
ANTHROPIC_API_KEY=your_anthropic_api_key  # https://console.anthropic.com
OPENAI_API_KEY=your_openai_api_key        # https://platform.openai.com
GEMINI_API_KEY=your_gemini_api_key        # https://aistudio.google.com/app/apikey
GROQ_API_KEY=your_groq_api_key            # https://console.groq.com

# =================================================================
# SANDBOX PROVIDER - Choose ONE: Vercel or E2B (recommended)
# =================================================================
SANDBOX_PROVIDER=e2b  # or 'vercel'

# For E2B Sandbox (recommended)
E2B_API_KEY=your_e2b_api_key      # https://e2b.dev

# For Vercel Sandbox (alternative)
# VERCEL_TOKEN=your_vercel_token
# VERCEL_TEAM_ID=your_team_id
# VERCEL_PROJECT_ID=your_project_id
```

3. **Run Development Server**
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS, Radix UI, Framer Motion
- **AI Integration**: Vercel AI SDK, Multiple AI Providers
- **Sandboxes**: E2B (Primary), Vercel (Alternative)
- **Web Scraping**: Firecrawl API
- **Development**: Turbopack, ESLint, PostCSS

## Project Structure

```
Booster/
├── app/                 # Next.js App Router pages
├── components/          # Reusable UI components
├── lib/                 # Utility functions and configurations
├── config/              # Application configuration
├── types/               # TypeScript type definitions
├── styles/              # CSS and styling files
├── public/              # Static assets
└── docs/                # Documentation
```

## Development

### Available Scripts
- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Key Features
- **Hot Module Replacement** - Instant updates during development
- **TypeScript** - Full type safety and IntelliSense
- **Responsive Design** - Mobile-first approach
- **Component Architecture** - Modular, reusable components

## Deployment

Ready for deployment to:
- **Vercel** (recommended for Next.js)
- **Netlify**
- **Railway**
- **Self-hosted** servers

## License

MIT

---

**Built with ❤️ using cutting-edge AI and web technologies**
