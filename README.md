# Syed Muhammad Hussain - Portfolio Website

[![Jekyll](https://img.shields.io/badge/Jekyll-4.0-blue)](https://jekyllrb.com/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-green)](https://syed-m-hussain.github.io)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

## 🌐 Live Website
Visit my portfolio at: [https://syed-m-hussain.github.io](https://syed-m-hussain.github.io)

## 👨‍💻 About Me
I'm a Machine Learning Engineer at Beam AI specializing in Large Language Models (LLMs), Retrieval-Augmented Generation (RAG) systems, and AI-driven automation. My work focuses on developing production-ready AI systems that transform how enterprises operate.

## 🚀 Portfolio Highlights

### 🎯 Featured Projects
- **OpenRobotics Lab** - Open-source learning platform for robotics education
- **Enterprise RAG System** - High-performance document search with 40% improved accuracy
- **Autonomous AI Agents** - Multi-agent systems reducing manual oversight by 70%
- **Document Intelligence** - Multimodal AI achieving 96% extraction accuracy

### 📚 Research & Publications
- **5+ IEEE Conference Papers** on topics including:
  - Camouflaged object detection
  - Robotics and trajectory planning
  - Ensemble learning for health monitoring
  - Computer vision applications

### 🛠️ Technical Stack
- **Languages**: Python, JavaScript
- **ML/AI**: PyTorch, TensorFlow, LangChain, LlamaIndex
- **Cloud**: Azure AI Services, Docker, MLflow
- **Specializations**: LLM Evaluation, RAG, Prompt Engineering, MLOps

## 🏗️ Website Features

This portfolio website is built using:
- **Jekyll** - Static site generator
- **Academic Pages Theme** - Clean, professional academic template
- **GitHub Pages** - Hosting and deployment
- **Dark Theme** - Custom dark mode implementation

### Site Structure
```
├── _pages/          # Static pages (About, CV, etc.)
├── _portfolio/      # Project showcase
├── _publications/   # Research papers and publications
├── _posts/          # Blog posts
├── _sass/           # Custom styling (dark theme)
├── assets/          # CSS, JS, and images
└── _config.yml      # Site configuration
```

## 🚀 Local Development

### Prerequisites
- Ruby 2.5+
- Bundler
- Jekyll 4.0+

### Installation

1. Clone the repository:
```bash
git clone https://github.com/syed-m-hussain/syed-m-hussain.github.io.git
cd syed-m-hussain.github.io
```

2. Install dependencies:
```bash
bundle install
```

3. Run the site locally:
```bash
bundle exec jekyll serve
```

4. Visit `http://localhost:4000` in your browser

### Development Commands

```bash
# Clean build files
bundle exec jekyll clean

# Build the site
bundle exec jekyll build

# Serve with live reload
bundle exec jekyll serve --livereload

# Build JavaScript assets
npm run build:js

# Watch JavaScript files
npm run watch:js
```

## 📝 Content Management

### Adding a New Project
Create a new file in `_portfolio/` with the format:
```markdown
---
title: "Project Title"
excerpt: "Brief description"
collection: portfolio
---

Project details here...
```

### Adding a Publication
Create a new file in `_publications/` with the format:
```markdown
---
title: "Paper Title"
collection: publications
permalink: /publication/paper-name
venue: 'Conference Name'
date: YYYY-MM-DD
---

Paper abstract and details...
```

## 🤝 Connect With Me

- **LinkedIn**: [syed-muhammad-hussain](https://www.linkedin.com/in/syed-muhammad-hussain-00b2a7214/)
- **GitHub**: [SYED-M-HUSSAIN](https://github.com/SYED-M-HUSSAIN)
- **Google Scholar**: [Profile](https://scholar.google.com/citations?user=TqMFlMYAAAAJ&hl=en)
- **IEEE Xplore**: [Author Page](https://ieeexplore.ieee.org/author/949288735174528)
- **Email**: sh06892@st.habib.edu.pk

## 🙏 Acknowledgments

- Built on the [Academic Pages](https://academicpages.github.io/) template
- Hosted on [GitHub Pages](https://pages.github.com/)
- Dark theme inspired by GitHub's dark mode

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*"Building AI systems that are not just intelligent, but reliable, ethical, and transformative for real-world applications."*