# 🤖 AI-Powered Social Media Generator MVP

[![MVP Status](https://img.shields.io/badge/Status-MVP-green)](https://github.com/yourusername/ai-social-media-generator)
[![Version](https://img.shields.io/badge/Version-1.0.0-blue)](https://github.com/yourusername/ai-social-media-generator/releases)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

> **Minimum Viable Product (MVP)** - A comprehensive AI-powered tool that monitors GitHub repositories and automatically generates platform-optimized social media content using multiple AI models.

## 🎯 **What This MVP Does**

Transform your GitHub repository updates into engaging social media content across multiple platforms using the power of AI. This MVP provides a complete workflow from repository monitoring to publication-ready content.

## ✨ **Key MVP Features**

### 🔍 **GitHub Repository Monitoring**
- Real-time monitoring of repository changes
- Automatic commit detection and analysis
- README content extraction and processing
- Configurable check intervals

### 🧠 **Multi-AI Model Support**
- **Google Gemini** - Creative and engaging content
- **OpenAI GPT** (3.5/4/4-Turbo) - Professional and versatile
- **Anthropic Claude** (Sonnet/Opus) - Technical and analytical
- Smart fallback system when models fail

### 📱 **Platform-Specific Content Generation**
- **Twitter/X** (280 chars) - Concise, hashtag-optimized
- **LinkedIn** (3000 chars) - Professional, detailed
- **Instagram** (2200 chars) - Visual storytelling
- **Facebook** - Engagement-focused
- **TikTok** - Trendy and energetic
- **Blog Posts** - Comprehensive articles

### 🎨 **Content Creation Modes**
1. **AI Generate from Repository** - Analyzes repo data and creates content
2. **AI Rephrase** - Optimizes your existing text for platforms
3. **Manual Writing** - Full control with AI assistance

### 🛠 **Advanced Content Tools**
- Real-time character counting with platform limits
- Live platform-specific previews
- Hashtag suggestions engine
- Emoji picker and insertion
- AI content refinement
- Template management system

## 🚀 **Getting Started**

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- GitHub Personal Access Token
- At least one AI API key (Gemini/OpenAI/Claude)

### Quick Setup

1. **Clone or Download**
   ```bash
   git clone https://github.com/yourusername/ai-social-media-generator.git
   cd ai-social-media-generator
   ```

2. **Open the Application**
   - Simply open `index.html` in your web browser
   - No installation or server setup required!

3. **Configure AI Models**
   - Go to the "AI Models" tab
   - Add your API keys for preferred AI services
   - Test connections to ensure they work

4. **Set Up Repository Monitoring**
   - Navigate to the "Monitor" tab
   - Add your GitHub Personal Access Token
   - Enter your repository URL
   - Configure monitoring settings

5. **Start Creating Content**
   - Use the "Create" tab for immediate content generation
   - Or enable auto-generation in monitoring mode

## 🔑 **API Keys Setup**

### GitHub Personal Access Token
1. Go to GitHub Settings → Developer Settings → Personal Access Tokens
2. Generate new token with `repo` permissions
3. Copy and paste into the application

### AI Service API Keys

#### Google Gemini
- Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
- Create new API key
- Free tier available

#### OpenAI
- Go to [OpenAI API](https://platform.openai.com/api-keys)
- Create new secret key
- Pay-per-use pricing

#### Anthropic Claude
- Visit [Anthropic Console](https://console.anthropic.com/)
- Generate API key
- Pay-per-use pricing

## 💡 **Usage Examples**

### Automatic Repository Monitoring
```
1. Configure GitHub repo: https://github.com/username/awesome-project
2. Set check interval: 5 minutes
3. Enable auto-generation for Twitter and LinkedIn
4. Start monitoring
→ When new commits are detected, posts are automatically generated!
```

### Manual Content Creation
```
1. Select "AI Rephrase" mode
2. Enter: "Just fixed a major bug in our authentication system"
3. Choose platform: Twitter
4. Set tone: Professional
→ Output: "🔧 Just resolved a critical authentication issue! Enhanced security and improved user experience. Thanks to our amazing community for reporting this. #cybersecurity #bugfix #development"
```

### Template Usage
```
1. Go to Templates tab
2. Select platform: Instagram
3. Choose template: "Achievement Post"
4. Customize with your repo data
→ Ready-to-use branded content!
```

## 🏗️ **MVP Architecture**

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   GitHub API    │    │   AI Services   │    │  Web Interface  │
│                 │    │                 │    │                 │
│ • Repository    │◄──►│ • Gemini        │◄──►│ • Monitoring    │
│ • Commits       │    │ • OpenAI        │    │ • Content Gen   │
│ • README        │    │ • Claude        │    │ • Templates     │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

## 📊 **MVP Limitations & Future Roadmap**

### Current MVP Limitations
- Browser-based only (no mobile app)
- No direct social media posting
- No user authentication/multi-user support
- No analytics or performance tracking
- Limited template customization

### Post-MVP Features (Coming Soon)
- [ ] Direct posting to social media platforms
- [ ] Advanced analytics and engagement tracking
- [ ] Mobile application
- [ ] User accounts and team collaboration
- [ ] Advanced scheduling system
- [ ] Custom AI model integration
- [ ] Webhook integrations
- [ ] Enterprise features

## 🔧 **Technical Details**

### Built With
- **Frontend**: Vanilla HTML5, CSS3, JavaScript ES6+
- **APIs**: GitHub REST API, Google Gemini API, OpenAI API, Anthropic API
- **Storage**: Browser localStorage (no backend required)
- **Deployment**: Static hosting (GitHub Pages, Netlify, Vercel compatible)

### Browser Compatibility
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📝 **Contributing**

This is an MVP, and we welcome contributions! Here's how you can help:

1. **Bug Reports**: Open issues for any bugs you find
2. **Feature Requests**: Suggest improvements for post-MVP versions
3. **Code Contributions**: Fork, develop, and submit pull requests
4. **Documentation**: Help improve this README and add tutorials

### Development Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/ai-social-media-generator.git

# No build process required - just open index.html in your browser
# For development, you might want to use a local server:
python -m http.server 8000
# or
npx serve .
```

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ **Important Notes**

### Security
- API keys are stored in browser localStorage only
- No data is sent to external servers (except AI APIs)
- Clear browser data to remove stored keys

### Rate Limits
- GitHub API: 5000 requests/hour for authenticated users
- AI APIs: Vary by provider (check their documentation)
- Built-in rate limiting and error handling included

### Costs
- GitHub API: Free
- AI APIs: Pay-per-use (check current pricing)
- Estimated cost: $1-5/month for typical usage

## 🆘 **Support**

### Getting Help
- **Issues**: [GitHub Issues](https://github.com/yourusername/ai-social-media-generator/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/ai-social-media-generator/discussions)
- **Email**: support@yourproject.com

### FAQ

**Q: Do I need all three AI services?**
A: No! You can use just one. The app has smart fallback, so having multiple is recommended for reliability.

**Q: Can I use this for private repositories?**
A: Yes! Just ensure your GitHub token has appropriate permissions.

**Q: Is my data secure?**
A: Yes. All processing happens in your browser. API keys are stored locally only.

**Q: Can I customize the AI prompts?**
A: Absolutely! The app provides custom prompt fields and template management.

## 🎉 **Acknowledgments**

- GitHub API for excellent developer tools
- AI service providers for powerful language models
- Open source community for inspiration and feedback
- Beta testers who helped refine this MVP

---

**Made with ❤️ for developers who want to automate their social media presence**

*This is an MVP (Minimum Viable Product) - a functional version with core features ready for real-world use and feedback.*