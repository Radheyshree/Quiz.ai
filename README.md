# Quiz.ai
# 🧠 Quiz.AI - AI-Powered Dynamic Quiz Platform

<div align="center">

![Quiz.AI Logo](https://img.shields.io/badge/Quiz.AI-AI%20Powered%20Quiz%20Platform-blue?style=for-the-badge&logo=react)
![React](https://img.shields.io/badge/React-18.0.0-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-3178C6?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.0.0-06B6D4?style=for-the-badge&logo=tailwindcss)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini%20API-AI%20Powered-4285F4?style=for-the-badge&logo=google)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Project-green?style=for-the-badge&logo=vercel)](https://quiz-ai-demo.vercel.app)
[![GitHub Stars](https://img.shields.io/github/stars/yourusername/quiz-ai?style=for-the-badge)](https://github.com/yourusername/quiz-ai)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

*An intelligent, adaptive quiz platform that generates personalized questions using AI*

</div>

---

## 🚀 Overview

Quiz.AI is a cutting-edge Single Page Application (SPA) that revolutionizes the traditional quiz experience by leveraging artificial intelligence to create dynamic, user-specific content. Built with modern web technologies, this platform offers an engaging and personalized learning experience with real-time competition through an interactive leaderboard.

### ✨ Key Features

- 🤖 **AI-Powered Question Generation** - Dynamic content creation using Google Gemini API
- 🎯 **Personalized Experience** - User-specific quiz content based on preferences and performance
- 🏆 **Real-time Leaderboard** - Live competition tracking and rankings
- ⚡ **Responsive Design** - Seamless experience across all devices
- 🎨 **Modern UI/UX** - Beautiful interface built with Tailwind CSS
- 🔄 **Dynamic Content** - No two quizzes are ever the same
- 📊 **Performance Analytics** - Detailed insights into user progress
- 🚀 **Instant Feedback** - Real-time scoring and explanations

---

## 🛠️ Technology Stack

### Frontend
- **React 18** - Modern UI library for building interactive interfaces
- **TypeScript** - Type-safe JavaScript for better development experience
- **Tailwind CSS** - Utility-first CSS framework for rapid UI development
- **Vite** - Fast build tool and development server

### AI & Backend
- **Google Gemini API** - Advanced AI model for intelligent question generation
- **RESTful APIs** - Clean and efficient data communication

### Development Tools
- **ESLint** - Code quality and consistency
- **Prettier** - Code formatting
- **Git** - Version control

---

## 🎯 Features in Detail

### 🤖 AI-Driven Content Generation
- Leverages Google Gemini API for intelligent question creation
- Adapts difficulty based on user performance
- Generates diverse question types and topics
- Provides contextual explanations for answers

### 🏆 Real-time Leaderboard
- Live updates of player rankings
- Global and category-specific leaderboards
- Achievement badges and milestones
- Social sharing capabilities

### 📱 Responsive Design
- Mobile-first approach
- Optimized for all screen sizes
- Touch-friendly interface
- Progressive Web App features

### ⚡ Performance Optimized
- Fast loading times
- Efficient state management
- Optimized bundle size
- Caching strategies

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager
- Google Gemini API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/quiz-ai.git
   cd quiz-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   ```bash
   cp .env.example .env.local
   ```
   
   Add your Google Gemini API key to `.env.local`:
   ```env
   VITE_GEMINI_API_KEY=your_api_key_here
   ```

4. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
# or
yarn build
```

---

## 📁 Project Structure

```
quiz-ai/
├── public/
├── src/
│   ├── components/          # Reusable UI components
│   ├── pages/              # Page components
│   ├── hooks/              # Custom React hooks
│   ├── services/           # API and external services
│   ├── types/              # TypeScript type definitions
│   ├── utils/              # Utility functions
│   ├── styles/             # Global styles and Tailwind config
│   ├── App.tsx             # Main application component
│   └── main.tsx            # Application entry point
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── README.md
```

---

## 🎮 How to Use

1. **Start a Quiz**
   - Choose your preferred category or difficulty
   - Let AI generate personalized questions for you

2. **Answer Questions**
   - Read carefully and select your answer
   - Get instant feedback and explanations

3. **Track Progress**
   - View your score in real-time
   - Check your position on the leaderboard

4. **Compete**
   - Challenge friends and family
   - Aim for the top spot on global rankings

---

## 🔧 Configuration

### Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `VITE_GEMINI_API_KEY` | Google Gemini API key | Yes |
| `VITE_API_BASE_URL` | Backend API base URL | No |
| `VITE_APP_NAME` | Application name | No |

### Customization

The application can be easily customized by modifying:
- `tailwind.config.js` - Styling and theme
- `src/types/` - TypeScript interfaces
- `src/components/` - UI components
- `src/services/` - API integration

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Follow TypeScript best practices
- Use meaningful commit messages
- Add tests for new features
- Update documentation as needed
- Follow the existing code style

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Google Gemini API** - For providing powerful AI capabilities
- **React Team** - For the amazing framework
- **Tailwind CSS** - For the utility-first CSS framework
- **Vite** - For the fast build tool
- **Open Source Community** - For inspiration and support

---

## 📞 Contact & Support

- **Project Link**: [https://github.com/yourusername/quiz-ai](https://github.com/yourusername/quiz-ai)
- **Live Demo**: [https://quiz-ai-demo.vercel.app](https://quiz-ai-demo.vercel.app)
- **Issues**: [GitHub Issues](https://github.com/yourusername/quiz-ai/issues)

---

<div align="center">

**Made with ❤️ and ☕ by [Your Name]**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourusername)

</div>
