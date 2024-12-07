
---

# 📝 Suraj Kumar's Resume

This repository contains the LaTeX source code for my professional resume, designed to showcase my skills, projects, internships, and achievements in a clean and visually appealing format.

---

## 🔥 Features

- **Elegant Design:** Minimalistic and professional design with a focus on readability.
- **Customizable Template:** Easily tweak sections like skills, projects, and education.
- **ATS-Friendly:** Optimized for Applicant Tracking Systems (ATS) with Unicode support.
- **Modern Tools:** Includes fonts, icons, and responsive layout options.

---

## 📂 File Structure

```plaintext
├── resume.tex         # Main LaTeX file
├── mteck.sty          # Custom style file for formatting
├── output.pdf         # Compiled PDF of the resume
└── README.md          # Project documentation
```

---

## 📋 Prerequisites

### For macOS:
1. Install **MacTeX**:
   - [Download MacTeX](https://tug.org/mactex/)
   - Ensure installation is verified:
     ```bash
     pdflatex --version
     ```

2. Install **VS Code** and the **LaTeX Workshop** extension.

### For Windows/Linux:
- Install TeX distributions like **TeX Live** or **MiKTeX**.

---

## 🚀 Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/surajkr97/resume.git
   cd resume
   ```

2. Open `resume.tex` in any LaTeX editor (e.g., VS Code).

3. Compile using `pdflatex` or an IDE (e.g., Overleaf).

4. Generate the PDF:
   ```bash
   pdflatex resume.tex
   ```

5. Find the output as `output.pdf`.

---

## 🛠 Customization

1. **Contact Information**:
   Modify your contact details in the `\documentTitle` section:
   ```latex
   \documentTitle{Suraj Kumar}{
       \href{tel:+917367089724}{\faPhone +91 7367089724} ~ | ~
       \href{mailto:surajkumar06174@gmail.com}{\faEnvelope surajkumar06174@gmail.com}
   }
   ```

2. **Skills, Projects, Education**:
   Update respective sections (`\section{}`) as needed.

3. **Style**:
   Modify `mteck.sty` for color, font, and layout preferences.

---

## 📦 Dependencies

- **Packages Used**:
  - `fancyhdr`
  - `hyperref`
  - `titlesec`
  - `fontawesome5`

---

## 🏆 Achievements & Projects

### **Achievements**
- First Runner-Up: Incubate India Hackathon 2021, powered by GitHub.
- First Runner-Up: Inter College Tech Talent Hackathon 2023, Haryana.

### **Highlighted Projects**
- **[Investment Services Website](https://shivamsecurities.com/)**
- **[Memory Game](https://github.com/surajkr97/MemoryGame/tree/master/matchthecards)**
- **[Expense Tracker App](https://github.com/surajkr97/Expense-Tracker-App)**
- **[Hand Gesture Controlled Robot Car](https://surajkr97.hashnode.dev/exploring-the-world-of-iot-from-robo-cars-to-robo-warrior)**

---

## 🖼 Preview

![Resume Screenshot](https://drive.google.com/file/d/1_VnAXFsJnfc26dlYP4KOlTNX7EKHqi3L/view?usp=sharing)

---

## 🙌 Acknowledgements

Thanks to:
- [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop)
- Community contributors to [Overleaf](https://www.overleaf.com/).

---

## 📬 Contact Me

Connect with me on [LinkedIn](https://linkedin.com/in/suraj-gupta-679815215) or visit my [GitHub](https://github.com/surajkr97).

---

Feel free to update this file to reflect future changes to your resume!
