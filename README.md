# 🌈 PRISM - The Ultimate AI Research Assistant

<div align="center">
  <img src="public/logo.svg" alt="Prism Logo" width="300"/>
  
  ### Transform How You Understand Research
  
  [![Built with React](https://img.shields.io/badge/React-18.2-61dafb?logo=react)](https://reactjs.org/)
  [![Powered by AI](https://img.shields.io/badge/Powered-AI-4285f4)](https://github.com)
  [![Vite](https://img.shields.io/badge/Vite-5.0-646cff?logo=vite)](https://vitejs.dev/)
</div>

---

## 🚀 What is Prism?

**Prism** is not just a document summarization tool—it's a revolutionary, end-to-end AI-powered workflow designed to accelerate scientific discovery. It transforms passive reading into an active, interactive, and generative research experience.

### 🎯 Key Differentiators

- **🧠 Adaptive Intelligence**: Optional expertise quiz personalizes analysis depth for students, engineers, or domain experts
- **✅ Evidence-Grounded**: Every insight backed by direct quotes from the source—no hallucinations
- **💡 Generative AI Lab**: Creates novel hypotheses and experimental designs from any paper
- **🖼️ Multimodal Analysis**: Chat with AI about specific figures and visualizations
- **📚 Multi-Paper Synthesis**: Comparative analysis across multiple papers with conflict detection
- **🔒 Privacy-First**: Client-side file parsing—your research never leaves your machine
- **📱 Mobile-Optimized**: Blazing-fast performance on phones, tablets, and laptops with zero lag

### 📱 How to Upload Files

#### On Desktop:
1. **Drag & Drop**: Drag PDF/DOCX/TXT files onto the upload area
2. **Click to Browse**: Click the "Choose Files" button to select files
3. **Multiple Files**: Hold Ctrl/Cmd to select multiple papers

#### On Mobile (iOS/Android):
1. **Tap the Upload Button**: Tap "Choose Files" button
2. **Select Source**:
   - 📷 Take Photo (for scanned papers)
   - 🖼️ Photo Library (if PDF is saved as image)
   - 📁 Files App (iOS) / File Manager (Android)
   - ☁️ Cloud Storage (iCloud, Google Drive, etc.)
3. **Multiple Selection**: Long-press files to select multiple
4. **Wait for Processing**: Upload shows progress automatically

**Supported Formats**: PDF, DOCX, DOC, TXT (up to 50MB each)

---

## ✨ Features

### 🎓 Intelligent Onboarding
- **Multi-format Support**: PDF, DOCX, TXT (up to 50MB)
- **Client-side Parsing**: Privacy-preserving document processing
- **AI Validation**: Automatically detects if document is a scientific paper
- **Adaptive Expertise Quiz**: 5-question assessment tailors analysis to your level

### 📊 Single-Paper Analysis Dashboard

#### Key Takeaways Tab
- 3-5 critical contributions at a glance
- Beautifully designed cards with gradient accents

#### Overview Tab
- **Regenerative Summaries**: Customize by persona, length, and technical depth
- Structured breakdown: Problem Statement, Methodology, Key Findings
- **Verifiable Findings**: Each finding paired with direct quote evidence

#### Critique Tab
- **Strengths**: Evidence-backed positive aspects
- **Weaknesses**: Critical analysis with citations
- Professional peer-review style presentation

#### AI Ideation Lab 🔬
- **Novel Hypotheses**: Testable ideas extending from the paper
- **Experimental Designs**: Detailed protocols for each hypothesis
- **Expected Outcomes**: Predicted results and implications

#### Figures Tab
- Automatic extraction from PDFs
- **AI Figure Explanations**: Click any figure for detailed analysis
- High-quality rendering with zoom functionality

#### References Tab
- Extracted and formatted bibliography
- **Dual Format**: Toggle between APA and BibTeX
- One-click copy all references

#### Related Papers Tab
- AI-generated search queries
- Direct links to Google Scholar
- Finds similar, contradictory, and foundational work

### 💬 Interactive Multimodal Chat
- **Context-Aware**: Full paper context in every response
- **Streaming Responses**: Real-time token-by-token output
- **Figure Attachment**: Upload figures to ask visual questions
- Persistent conversation history

### 🎨 Multi-Paper Synthesis
- **Overall Synthesis**: Narrative weaving core ideas
- **Common Themes**: Shared concepts across papers
- **Conflicting Findings**: Disagreements and contradictions
- **Concept Evolution**: How ideas develop across the literature

### 🛠️ Utility Features
- **Interactive Glossary**: Hover definitions for technical terms
- **Presentation Generator**: Auto-create slides from analysis
- **Multi-Format Export**: PDF, Markdown, PowerPoint (PPTX)
- **Analysis History**: Access your last 10 papers instantly

---

## 🏗️ Technology Stack

### Frontend
- **React 18.2** - Modern UI framework
- **Vite 5.0** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first styling with custom theme
- **Framer Motion** - Smooth animations
- **Lucide React** - Beautiful icon library

### AI & Processing
- **Advanced AI Models** - Fast & accurate analysis
- **Structured Output (JSON Mode)** - Reliable, parseable responses
- **PDF.js** - Client-side PDF parsing
- **Mammoth.js** - DOCX document processing
- **Intelligent Caching** - Smart data persistence

### State Management & Utilities
- **Zustand** - Lightweight state management with persistence
- **React Router** - Client-side routing
- **jsPDF** - PDF generation
- **PptxGenJS** - PowerPoint export

---

## 📦 Installation

### Prerequisites
- **Node.js** 18+ and npm/yarn
- Modern web browser (Chrome, Edge, Firefox, Safari)

### Setup

1. **Clone or navigate to the project**
```bash
cd researchnew
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```

4. **Open your browser**
```
http://localhost:3000
```

### Build for Production
```bash
npm run build
npm run preview
```

---

## 🎮 How to Use

### 1. Upload Papers
- Drag & drop or click to browse
- Single paper → Detailed analysis
- Multiple papers → Comparative synthesis

### 2. Take the Quiz (Optional)
- 5 adaptive questions assess your expertise
- Results personalize all AI outputs
- Can skip and use default persona

### 3. Explore Analysis
- Navigate through 7 comprehensive tabs
- Click figures for AI explanations
- Regenerate summaries with custom settings

### 4. Chat with AI
- Ask questions about methodology, findings, etc.
- Attach figures for visual questions
- Get instant, context-aware answers

### 5. Export & Share
- Download as PDF for reports
- Export Markdown for notes
- Generate PowerPoint presentations

---

## 🔐 API Configuration

The Gemini API key is included for demo purposes. For production:

1. Get your own key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Replace in `src/services/geminiApi.js`:
```javascript
const GEMINI_API_KEY = 'YOUR_API_KEY_HERE';
```

---

## 🎨 Design Philosophy

### Color Palette
- **Primary (Prism)**: `#0ea5e9` - Trust, intelligence
- **Accent Purple**: `#8b5cf6` - Creativity, innovation
- **Accent Pink**: `#ec4899` - Energy, breakthrough
- **Gradients**: Smooth transitions symbolizing light refraction

### Typography
- **Display**: Poppins (headings)
- **Body**: Inter (readable, modern)
- **Code**: JetBrains Mono (technical content)

### Animations
- Floating elements for depth
- Gradient animations for dynamism
- Smooth transitions for polish
- Skeleton loaders for perceived performance

---

## 📚 Project Structure

```
researchnew/
├── public/
│   ├── favicon.svg          # Prism logo favicon
│   └── logo.svg             # Full Prism logo
├── src/
│   ├── components/
│   │   ├── analysis/        # Tab components
│   │   ├── chat/            # Chat interface
│   │   ├── quiz/            # Expertise quiz
│   │   └── ui/              # Reusable UI components
│   ├── pages/
│   │   ├── HomePage.jsx     # Landing & upload
│   │   ├── AnalysisPage.jsx # Single paper analysis
│   │   ├── MultiPaperPage.jsx # Multi-paper synthesis
│   │   └── HistoryPage.jsx  # Analysis history
│   ├── services/
│   │   ├── geminiApi.js     # AI API integration
│   │   ├── fileParser.js    # Document parsing
│   │   ├── analysisService.js # Analysis orchestration
│   │   └── exportService.js # Export utilities
│   ├── store/
│   │   └── useAppStore.js   # Global state
│   ├── utils/
│   │   └── helpers.js       # Utility functions
│   ├── App.jsx              # Root component
│   ├── main.jsx             # Entry point
│   └── index.css            # Global styles
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

---

## 🌟 Advanced Features

### Prompt Engineering Excellence
- **Granular Pipelines**: Separate prompts for each analysis type
- **Persona-Aware**: Instructions adapt to user expertise
- **Evidence Forcing**: Schema requires direct quotes
- **Structured Output**: JSON schemas ensure reliability

### Performance Optimization
- **Lazy Loading**: Non-blocking async operations
- **Skeleton Loaders**: Instant perceived responsiveness
- **Client-Side Processing**: Reduces server load
- **Smart Caching**: LocalStorage for history

### Error Handling
- Comprehensive validation at every stage
- Graceful degradation for missing data
- User-friendly error messages
- Retry mechanisms for API calls

---

## 🚀 Future Enhancements

- [ ] Real-time collaboration
- [ ] Knowledge graph visualization
- [ ] Citation network analysis
- [ ] ArXiv/PubMed direct import
- [ ] Voice-to-text queries
- [ ] Mobile app (React Native)
- [ ] Browser extension
- [ ] API for developers

---

## 🤝 Contributing

This is a hobby project built for researchers by researchers. Contributions welcome!

### Areas for Improvement
- Additional file formats (LaTeX, XML)
- More export options (Notion, Obsidian)
- Enhanced visualizations
- Accessibility improvements

---

## 📄 License

This project is open source for educational and research purposes.

---

## 🙏 Acknowledgments

- **Advanced AI Technologies** for powerful capabilities
- **React community** for excellent libraries
- **Open source contributors** for foundational tools

---

## 📧 Support

For questions, suggestions, or bug reports, please open an issue on GitHub.

---

<div align="center">
  
  ### For the Research Community
  
  **Accelerate your scientific discovery with Prism**
  
  [🌐 Demo](#) | [📖 Documentation](#) | [💬 Community](#)
  
</div>
