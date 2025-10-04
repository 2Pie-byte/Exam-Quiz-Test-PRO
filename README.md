# Exam-Quiz-Test-PRO

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)

> ❤️ **All-in-one open-source advanced browser-based quiz maker software with dark & light mode and over 20+ features!**

The **PRO version** of [Exam-Quiz-Test](https://github.com/Refloow/Exam-Quiz-Test) - A powerful, feature-rich quiz creation and management platform that takes quiz-making to the next level with an intuitive quiz builder, enhanced editing capabilities, and support for rich media content.

![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

## 🎯 What's New in PRO

The PRO version is a complete upgrade from the basic Exam-Quiz-Test platform, featuring:

### 🚀 **Advanced Quiz Builder**
- **Visual Quiz Builder Interface** - Create quizzes without touching code
- **Real-time Preview** - See your quiz as you build it
- **Drag & Drop Question Management** - Reorder questions with ease
- **Intuitive Question Editor** - Add, edit, and delete questions in seconds

### 📝 **Enhanced Question Management**
- **Easy Add/Remove/Edit** - Manage questions before generating your test
- **Bulk Operations** - Import/export question sets
- **Question Templates** - Pre-built templates for common question types
- **Duplicate Questions** - Clone existing questions to save time

### 🖼️ **Rich Media Support**
- **Image Support** - Add images to questions and answers
- **Multimedia Content** - Embed videos, audio, and other media
- **Code Syntax Highlighting** - Enhanced code block display
- **LaTeX/Math Equations** - Support for mathematical formulas

### ⚡ **Additional PRO Features**
- **Improved JSON Format** - Better data structure for complex quizzes
- **Advanced Scoring Options** - Customizable point systems
- **Question Categories** - Organize questions by topic/category
- **Time Per Question** - Set individual time limits
- **Detailed Analytics** - Track performance and statistics
- **Quiz Templates** - Save and reuse quiz configurations

---

## ✨ Features (20+ Capabilities)

### Core Features
✅ **Customizable Questions & Timer** - Set quiz duration and question pool  
✅ **Single & Multiple Choice Questions** - Support for both formats  
✅ **Dark Mode & Light Mode** - Eye-friendly themes  
✅ **Randomized Question & Answer Order** - Prevent cheating  
✅ **Instant Feedback on Mistakes** - Learn while taking the quiz  
✅ **Accurate Scoring System** - Fair and precise grading  
✅ **No Installation Required** - Runs directly in browser  
✅ **Mobile Responsive** - Works perfectly on all devices  

### PRO Exclusive Features
✅ **Visual Quiz Builder** - No coding required  
✅ **Question Image Support** - Add visual elements  
✅ **Advanced Media Embedding** - Videos, audio, and more  
✅ **Question Bank Management** - Organize and reuse questions  
✅ **Custom Themes** - Personalize your quiz appearance  
✅ **Export/Import Functionality** - Share quiz data easily  
✅ **Question Categories/Tags** - Better organization  
✅ **Detailed Statistics** - Performance analytics  
✅ **Quiz Templates** - Pre-configured quiz formats  
✅ **Partial Credit Scoring** - Advanced grading options  
✅ **Time Management Options** - Global and per-question timers  
✅ **Accessibility Features** - WCAG compliant  
✅ **Multi-language Support** - Internationalization ready  

---

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
1. Visit the hosted version (link coming soon)
2. Start creating your quiz immediately
3. Download your quiz as a standalone HTML file

### Option 2: Local Installation
```bash
# Clone the repository
git clone https://github.com/Refloow/Exam-Quiz-Test-PRO.git

# Navigate to the directory
cd Exam-Quiz-Test-PRO

# Open index.html in your browser
# or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

No dependencies, no build process, no complications! 🎉

---

## 📖 Usage Guide

### Creating a Quiz with the Visual Builder

1. **Open the Quiz Builder**
   - Launch the application in your browser
   - Click on "Create New Quiz" or "Quiz Builder"

2. **Configure Quiz Settings**
   ```
   - Set quiz title
   - Set total time limit
   - Choose number of questions to display
   - Select theme (light/dark)
   - Configure scoring options
   ```

3. **Add Questions**
   - Click "Add Question" button
   - Choose question type (single/multiple choice)
   - Enter your question text
   - Add images if needed (drag & drop or upload)
   - Add answer options
   - Mark correct answers
   - Save the question

4. **Manage Questions**
   - **Edit**: Click on any question to modify it
   - **Delete**: Remove unwanted questions
   - **Duplicate**: Clone questions for similar variations
   - **Reorder**: Drag and drop to rearrange

5. **Generate Quiz**
   - Review your questions in preview mode
   - Click "Generate Quiz" to create the final test
   - Download as standalone HTML file
   - Share with students/participants

### Question Format Options

#### Text-Based Questions
```
Simple text questions with multiple choice answers
```

#### Questions with Images
```
Upload images to accompany questions or answer options
Supports: JPG, PNG, GIF, SVG
```

#### Questions with Code
```
Syntax-highlighted code blocks for programming tests
Supports multiple programming languages
```

#### Math/Science Questions
```
LaTeX support for mathematical equations
Chemical formulas and scientific notation
```

### Taking a Quiz

1. **Start Quiz**
   - Open the generated quiz HTML file
   - Click "Start Quiz" button
   - Timer begins automatically

2. **Answer Questions**
   - Read each question carefully
   - Select single or multiple answers as required
   - Questions are presented randomly
   - Answer options are shuffled

3. **Review Results**
   - Instant feedback on completion
   - See correct and incorrect answers
   - View detailed score breakdown
   - Option to retake the quiz

---

## 🔧 Configuration

### Quiz Configuration (in Builder)
```javascript
{
  totalTime: 90,              // Total quiz time in seconds
  questionsToPick: 5,         // Number of questions to display
  randomizeQuestions: true,   // Shuffle question order
  randomizeAnswers: true,     // Shuffle answer options
  showFeedback: true,         // Show immediate feedback
  allowRetake: true,          // Allow quiz retake
  passingScore: 70            // Passing percentage
}
```

### Advanced Options
- **Partial Credit**: Award points for partially correct answers
- **Negative Marking**: Deduct points for wrong answers
- **Question Categories**: Filter questions by category
- **Time Per Question**: Individual question time limits
- **Review Mode**: Allow reviewing all questions before submission

---

## 📊 Scoring System

### Single Choice Questions
- **Correct Answer**: 100% points
- **Wrong Answer**: 0% points

### Multiple Choice Questions
- **All Correct**: 100% points
- **Partial Correct (No wrong selections)**: Proportional percentage
- **Any Wrong Selection**: 0% points (default) or configurable

### Custom Scoring (PRO Feature)
- Define custom point values per question
- Weight questions by difficulty
- Bonus points for speed
- Penalty for incorrect attempts

---

## 🎨 Customization

### Themes
- **Light Mode** - Clean, professional appearance
- **Dark Mode** - Reduced eye strain for longer sessions
- **Custom Themes** - Create your own color schemes
- **High Contrast Mode** - Accessibility-focused theme

### Branding
- Add custom logos
- Customize colors and fonts
- Personalize success/failure messages
- White-label capability

---

## 📱 Browser Compatibility

✅ Chrome (latest)  
✅ Firefox (latest)  
✅ Safari (latest)  
✅ Edge (latest)  
✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 🆚 PRO vs Basic Version

| Feature | Basic Version | PRO Version |
|---------|--------------|-------------|
| Visual Quiz Builder | ❌ | ✅ |
| Easy Question Management | ❌ Manual JSON editing | ✅ GUI-based |
| Image Support | ❌ | ✅ |
| Video/Audio Support | ❌ | ✅ |
| Drag & Drop Interface | ❌ | ✅ |
| Question Categories | ❌ | ✅ |
| Advanced Analytics | ❌ | ✅ |
| Export/Import | ❌ | ✅ |
| Quiz Templates | ❌ | ✅ |
| Custom Themes | ❌ | ✅ |
| Math Equation Support | ❌ | ✅ |
| Code Syntax Highlighting | Basic | Enhanced |
| Mobile Optimization | Good | Excellent |

---

## 🤝 Community & Support

### Discord Server
Join our community to:
- Ask questions and get help
- Share your quizzes and experiences
- Discover other free open-source software
- Contribute to development

**👉 [Join Discord Server](https://discord.gg/4enDY8yhuS)**

### Contributing
We welcome contributions! Here's how you can help:

1. **Report Bugs** - Submit issues on GitHub
2. **Suggest Features** - Share your ideas
3. **Submit Pull Requests** - Improve the code
4. **Improve Documentation** - Help others understand
5. **Share the Project** - Spread the word

---

## 📄 License

This project is **open-source** under the **MIT License**.

```
Copyright (c) 2025 Veljko Vuckovic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
```

See the [LICENSE](LICENSE) file for full details.

---

## 🔗 Related Projects

- **[Exam-Quiz-Test](https://github.com/Refloow/Exam-Quiz-Test)** - The basic version (predecessor)
- More open-source projects by Refloow coming soon!

---

## 🌟 Show Your Support

If you find this project useful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🔀 Forking and contributing
- 📢 Sharing with others

---

## 📞 Contact

- **GitHub**: [@Refloow](https://github.com/Refloow)
- **Discord**: [Join our server](https://discord.gg/4enDY8yhuS)

---

**Built with ❤️ by Veljko Vuckovic and the open-source community**

*Enjoy building amazing quizzes with Exam-Quiz-Test-PRO! 🚀*
