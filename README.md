# ♟️ V0 Web Chess Game

A modern, interactive chess game built with Next.js 15, TypeScript, and Tailwind CSS. Experience chess like never before with a beautiful, responsive interface and smooth gameplay.

## 🌟 **Live Demo**

🚀 **[Play Now](https://v0-test-sigma-plum.vercel.app)**

## 📋 **Features**

- ♟️ **Full Chess Implementation** - Complete chess rules and piece movements
- 🎯 **Interactive Board** - Drag & drop or click-to-move gameplay
- 🎨 **Modern UI/UX** - Beautiful design with Radix UI components
- 📱 **Responsive Design** - Perfect experience on desktop and mobile
- ⚡ **Real-time Gameplay** - Smooth animations and state management
- 🌙 **Dark/Light Mode** - Theme switching support
- 🔧 **TypeScript** - Full type safety and better developer experience

## 🛠️ **Tech Stack**

### **Core Technologies**
- **Next.js 15** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **React 19** - Latest React features
- **Tailwind CSS** - Utility-first CSS framework

### **UI Components & Libraries**
- **Radix UI** - Unstyled, accessible UI components
- **Lucide React** - Beautiful icon library
- **Class Variance Authority** - Component styling management
- **Tailwind Merge** - Intelligent Tailwind class merging

### **Form & Validation**
- **React Hook Form** - Performant forms with easy validation
- **Zod** - TypeScript-first schema validation
- **Hookform Resolvers** - Form validation integration

### **Additional Tools**
- **Date-fns** - Modern JavaScript date utility library
- **Sonner** - Toast notifications
- **Next Themes** - Theme management
- **CMDK** - Command menu component

## 🚀 **Getting Started**

### **Prerequisites**

- Node.js 18+ 
- PNPM (recommended) or npm/yarn

### **Installation**

```bash
# Clone the repository
git clone https://github.com/mrrfly/v0-web-chess-game.git

# Navigate to project directory
cd v0-web-chess-game

# Install dependencies
pnpm install

# Start development server
pnpm dev
```

### **Available Scripts**

```bash
# Development
pnpm dev          # Start development server

# Production
pnpm build        # Build for production
pnpm start        # Start production server

# Code Quality
pnpm lint         # Run ESLint
```

## 🏗️ **Project Structure**

```
v0-web-chess-game/
├── 📁 app/                    # Next.js App Router pages
├── 📁 components/             # Reusable React components
│   ├── ui/                   # Base UI components (Radix UI)
│   └── chess/                # Chess-specific components
├── 📁 hooks/                  # Custom React hooks
│   ├── useChessGame.ts       # Main game logic
│   ├── useChessBoard.ts      # Board state management
│   └── useGameHistory.ts     # Move history tracking
├── 📁 lib/                    # Utility functions
│   ├── chess-engine.ts       # Chess rules & validation
│   ├── utils.ts              # General utilities
│   └── constants.ts          # Game constants
├── 📁 public/                 # Static assets
├── 📁 styles/                 # Global styles
└── 📁 types/                  # TypeScript type definitions
```

## 🎮 **How to Play**

1. **Start Game** - The board loads with pieces in starting positions
2. **Make Moves** - Click a piece, then click destination square
3. **Valid Moves** - Only legal chess moves are allowed
4. **Turn System** - Alternates between white and black players
5. **Game States** - Detects check, checkmate, and stalemate

## 🎯 **Game Features**

### **Implemented Chess Rules**
- ✅ All piece movements (Pawn, Rook, Knight, Bishop, Queen, King)
- ✅ Castling (Kingside & Queenside)
- ✅ En passant capture
- ✅ Pawn promotion
- ✅ Check detection
- ✅ Checkmate & Stalemate detection

### **UI/UX Features**
- ✅ Piece highlighting
- ✅ Valid move indicators
- ✅ Smooth animations
- ✅ Responsive design
- ✅ Accessible controls
- ✅ Theme switching

## 🔧 **Configuration**

### **Tailwind Config**
The project uses a customized Tailwind configuration with:
- Custom color palette
- Animation utilities
- Component-specific styling
- Dark mode support

### **TypeScript Config**
Strict TypeScript configuration for:
- Path mapping
- Type checking
- Import optimization
- Build optimization

## 🚀 **Deployment**

The application is deployed on **Vercel** with automatic deployments from the main branch.

### **Deploy Your Own**

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/mrrfly/v0-web-chess-game)

## 🤝 **Contributing**

Contributions are welcome! Please feel free to submit a Pull Request.

### **Development Guidelines**
1. Follow the existing code style
2. Add TypeScript types for new features
3. Write meaningful commit messages
4. Test your changes thoroughly

## 📝 **License**

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 **Author**

**mrrfly** - [GitHub Profile](https://github.com/mrrfly)

## 🔗 **Links**

- **Live Demo**: https://v0-test-sigma-plum.vercel.app
- **Repository**: https://github.com/mrrfly/v0-web-chess-game
- **Issues**: https://github.com/mrrfly/v0-web-chess-game/issues

## 🎉 **Acknowledgments**

- Built with [V0](https://v0.dev) - AI-powered UI generation
- UI components from [Radix UI](https://radix-ui.com)
- Icons from [Lucide](https://lucide.dev)
- Deployed on [Vercel](https://vercel.com)

---

<div align="center">

**⭐ Star this repository if you found it helpful! ⭐**

Made with ❤️ and ☕ by [mrrfly](https://github.com/mrrfly)

</div>
