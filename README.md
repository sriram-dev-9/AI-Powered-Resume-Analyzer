# AI Resumize 🚀

**Smart feedback for your dream job!**

AI Resumize is an intelligent resume analysis platform that provides comprehensive feedback on your resume to help you land your dream job. Our AI-powered system evaluates multiple aspects of your resume and provides actionable insights for improvement.

## 🌟 Features

- **AI-Powered Analysis**: Advanced algorithms analyze your resume across multiple dimensions
- **ATS Optimization**: Ensure your resume passes Applicant Tracking Systems
- **Comprehensive Scoring**: Get detailed scores for different aspects of your resume
- **Visual Feedback**: Easy-to-understand visual representations of your resume performance
- **Secure Storage**: Your resumes are stored securely using Puter's cloud infrastructure
- **Real-time Processing**: Upload and get instant feedback on your resume
- **Multiple Format Support**: Support for PDF resume uploads

## 🎯 What We Analyze

### 📊 Scoring Categories

- **Overall Score**: Comprehensive evaluation of your entire resume
- **ATS Compatibility**: How well your resume performs with Applicant Tracking Systems
- **Content Quality**: Relevance and strength of your resume content
- **Structure & Format**: Organization and visual appeal of your resume
- **Tone & Style**: Professional language and communication style
- **Skills Assessment**: Evaluation of your technical and soft skills presentation

## 🚀 Live Demo

Visit the live application: **[https://ai-resumize.vercel.app/](https://ai-resumize.vercel.app/)**

## 🛠️ Tech Stack

- **Frontend**: React 19 with React Router 7
- **Styling**: Tailwind CSS 4
- **File Processing**: PDF.js for PDF handling
- **State Management**: Zustand
- **Cloud Storage**: Puter for file storage and authentication
- **Deployment**: Vercel
- **Build Tool**: Vite
- **Language**: TypeScript

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sriram-dev-9/AI-Powered-Resume-Analyzer.git
   cd AI-Powered-Resume-Analyzer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Build & Deployment

### Development
```bash
npm run dev
```

### Production Build
```bash
npm run build
```

### Start Production Server
```bash
npm start
```

### Type Checking
```bash
npm run typecheck
```

## 📁 Project Structure

```
├── app/
│   ├── components/          # Reusable UI components
│   │   ├── Accordion.tsx    # Collapsible content sections
│   │   ├── ATS.tsx         # ATS analysis display
│   │   ├── Details.tsx     # Detailed feedback view
│   │   ├── FileUploader.tsx # Resume upload component
│   │   ├── Navbar.tsx      # Navigation bar
│   │   ├── ResumeCard.tsx  # Resume preview cards
│   │   ├── ScoreBadge.tsx  # Score indicator badges
│   │   ├── ScoreCircle.tsx # Circular score displays
│   │   ├── ScoreGauge.tsx  # Score gauge visualization
│   │   └── Summary.tsx     # Analysis summary
│   ├── lib/                # Utility libraries
│   │   ├── pdf2img.ts      # PDF to image conversion
│   │   ├── puter.ts        # Puter cloud integration
│   │   └── utils.ts        # General utilities
│   ├── routes/             # Page routes
│   │   ├── auth.tsx        # Authentication page
│   │   ├── home.tsx        # Dashboard/home page
│   │   ├── resume.tsx      # Resume analysis view
│   │   ├── upload.tsx      # Resume upload page
│   │   └── wipe.tsx        # Data cleanup page
│   ├── app.css            # Global styles
│   ├── root.tsx           # Root component
│   └── routes.ts          # Route configuration
├── constants/             # Application constants
├── public/               # Static assets
│   ├── icons/           # SVG icons
│   ├── images/          # Application images
│   └── readme/          # README assets
├── types/               # TypeScript type definitions
└── package.json        # Project configuration
```

## 🎨 Key Components

### FileUploader
Drag-and-drop interface for uploading PDF resumes with real-time processing feedback.

### ScoreGauge
Visual representation of resume scores using animated gauges and progress indicators.

### ATS Analysis
Comprehensive ATS compatibility checker that ensures your resume passes through automated screening systems.

### Resume Analytics
Detailed breakdown of resume performance across multiple categories with actionable improvement suggestions.

## 🔐 Authentication & Storage

- **Puter Integration**: Secure cloud storage and user authentication
- **File Management**: Efficient PDF processing and storage
- **Session Management**: Persistent user sessions across visits

## 🎯 How It Works

1. **Upload**: Upload your resume in PDF format
2. **Process**: Our AI analyzes your resume across multiple dimensions
3. **Review**: Get comprehensive feedback with scores and suggestions
4. **Improve**: Apply the recommendations to enhance your resume
5. **Resubmit**: Upload improved versions to track progress

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- React Router team for the excellent routing solution
- Tailwind CSS for the utility-first CSS framework
- Puter for cloud storage and authentication services
- PDF.js for client-side PDF processing
- Vercel for seamless deployment

## 📞 Contact

For questions, feedback, or support, please reach out through:
- GitHub Issues
- Live Demo: [https://ai-resumize.vercel.app/](https://ai-resumize.vercel.app/)

---

**Made with ❤️ for job seekers everywhere**

*AI Resumize - Smart feedback for your dream job!*
