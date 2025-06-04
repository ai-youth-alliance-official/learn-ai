<div align="center">
    <h1>LearnAI</h1>
  
  <h3>World's First Open-Source Peer-Verified AI Education Platform</h3>

  <p>
    <a href="https://github.com/ai-youth-alliance-official/learn-ai/stargazers"><img src="https://img.shields.io/github/stars/ai-youth-alliance-official/learn-ai?style=for-the-badge" alt="GitHub stars"></a>
    <a href="https://github.com/ai-youth-alliance-official/learn-ai/network/members"><img src="https://img.shields.io/github/forks/ai-youth-alliance-official/learn-ai?style=for-the-badge" alt="GitHub forks"></a>
    <a href="https://github.com/ai-youth-alliance-official/learn-ai/issues"><img src="https://img.shields.io/github/issues/ai-youth-alliance-official/learn-ai?style=for-the-badge" alt="GitHub issues"></a>
    <a href="https://github.com/ai-youth-alliance-official/learn-ai/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ai-youth-alliance-official/learn-ai?style=for-the-badge" alt="License"></a>
  </p>

  <p>
    <a href="#features">Features</a> •
    <a href="#getting-started">Getting Started</a> •
    <a href="#content-structure">Content Structure</a> •
    <a href="#contributing">Contributing</a> •
    <a href="#licensing">Licensing</a> •
    <a href="#community">Community</a>
  </p>
</div>

## Overview

LearnAI is revolutionizing AI education as the world's first platform combining 100% open-source learning materials with live peer-verified certification. Created by AI Youth Alliance, our platform offers distraction-free learning with a focus on practical skills, ethical AI development, and accessibility for everyone.

Our unique approach includes a public fraud registry, biometric verification, and project-based assessments to ensure certification integrity while maintaining a completely free and open educational resource.

## Features

<table>
  <tr>
    <td width="50%">
      <h3>🔍 Live Peer Verification</h3>
      <p>Real-time peer review ensures certification integrity and prevents fraud through our innovative verification system.</p>
    </td>
    <td width="50%">
      <h3>🛡️ Public Fraud Registry</h3>
      <p>Transparent system with public registry of fraudulent certification attempts, maintaining the value of our credentials.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔒 Privacy First</h3>
      <p>No tracking, no cookies, no data collection. Your progress is stored locally, respecting your privacy completely.</p>
    </td>
    <td width="50%">
      <h3>🚫 No Sign-up Required</h3>
      <p>Start learning immediately without creating accounts, providing emails, or setting passwords.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>📚 Project-Based Learning</h3>
      <p>Earn certificates through real projects and peer review, not multiple-choice tests, ensuring practical skill development.</p>
    </td>
    <td width="50%">
      <h3>💻 100% Open Source</h3>
      <p>All code and content available on GitHub. Fork, modify, and use freely under our dual license structure.</p>
    </td>
  </tr>
</table>

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ai-youth-alliance-official/learn-ai.git
   cd learn-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   ```
   http://localhost:5173
   ```

### Production Build

```bash
npm run build
# or
yarn build
```

## Content Structure

```
learn-ai/
├── LICENSE                # Dual license: AGPL-3.0 (code), CC BY-NC 4.0 (content)
├── index.html             # Main HTML entry point
├── package.json           # Project dependencies and scripts
├── tsconfig.json          # TypeScript configuration
├── vite.config.ts         # Vite build config
├── public/                # Static assets and all learning content
│   ├── Content-Structure-Guide.md
│   ├── LICENSE            # CC BY-NC 4.0 for content
│   └── content/           # All lessons, images, and code examples
├── src/                   # Application source code
│   ├── components/        # React components (UI, certification, sidebar, etc.)
│   ├── data/              # Lesson index and home page data
│   ├── pages/             # Main app pages (Home, Learn, Certification, etc.)
│   ├── styles/            # Global and component CSS
│   └── utils/             # Utility functions
├── docs/                  # Project documentation
├── scripts/               # Utility scripts
└── netlify/               # Netlify serverless functions and config
```

## 🤝 Contributing

We welcome contributions from everyone! See our detailed guides:

- [Content Contributor Guide](docs/contributor-content.md)
- [Video Contributor Guide](docs/contributor-video.md)
- [Code Contributor Guide](docs/contributor-code.md)
- [Peer Interviewer Guide](docs/contributor-peer-interviewer.md)
- [Code of Conduct](docs/contributor-code-of-conduct.md)
- [Contributor Recognition Program](docs/contributor-recognition.md)

For lesson authoring, see [`public/Content-Structure-Guide.md`](public/Content-Structure-Guide.md).

## 📜 Licensing

LearnAI is dual-licensed to protect both open-source principles and educational content:

- **Source Code**: [GNU Affero General Public License v3.0 (AGPL-3.0)](https://www.gnu.org/licenses/agpl-3.0.html)  
  Ensures that modifications to our code remain open source, especially for network services.

- **Educational Content**: [Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)  
  Allows sharing and adaptation of our educational materials while preventing commercial exploitation.

This dual licensing approach ensures that LearnAI remains free and open while protecting against unauthorized commercial use.

## 👥 Community

- **GitHub Issues**: Report bugs or request features
- **GitHub Discussions**: Ask questions and collaborate
- **Social Media**: Follow us for updates
  - [Website](https://aiyouthalliance.tech)
  - [LinkedIn](https://www.linkedin.com/company/aiyouthalliance)
  - [Instagram](https://www.instagram.com/aiyouthalliance/)
  - [X (Twitter)](https://x.com/aiyouthalliance)

## 🌟 Acknowledgments

- **AI Youth Alliance**: For creating and maintaining this platform
- **Open Source Community**: For tools and libraries that make this project possible
- **Contributors**: Everyone who has contributed code, content, and ideas
- **Learners**: For being part of our mission to democratize AI education

---

<div align="center">
  <p>© AI Youth Alliance. All rights reserved.</p>
  <p>Made with ❤️ for the global AI learning community</p>
</div>
