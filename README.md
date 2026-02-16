# 📊 GED Subject Planner

A responsive web-based quiz application that analyzes a student's strengths across four subjects and recommends:

- 📌 The optimal exam order  
- 🏆 Subject ranking (1–4)  
- 📚 Recommended study sheets for each subject  

---

## 🌐 Live Demo

🔗 https://ged-subject-planner.netlify.app

---

## 🚀 Features

- 4-Subject Quiz (Math, Science, Social Studies, RLA)
- Automatic score calculation
- Subject ranking from highest to lowest score
- Locked explanation logic based on ranking
- Recommended sheets section (multiple sheets per subject)
- Fully responsive design (Mobile / Tablet / Desktop)
- Clean UI with animated transitions

---

## 🗂️ Project Structure

   /project-root
   │
   ├── index.html # Landing page
   ├── quiz.html # Quiz page
   ├── summary.html # Result & analysis page
   ├── style.css # Main styling file
   └── images/ # Sheet images & favicon


---

## ⚙️ How It Works

1. Users complete the quiz in `quiz.html`.
2. Answers are stored using `localStorage`.
3. On `summary.html`, the system:
   - Calculates scores for each subject
   - Sorts them from highest to lowest
   - Assigns rankings (1–4)
   - Displays explanations based on ranking logic
4. The **"Recommended Sheets!"** section shows study materials grouped by subject.

---

## Ranking Logic

- Subjects are sorted using JavaScript `.sort()` in descending order.
- If two subjects have the same score:
  - The system preserves their original order.
  - Default subject order:


---

## Tech Used

- HTML5  
- CSS3 (Flexbox + Media Queries)  
- Vanilla JavaScript  
- Font Awesome  

---

## 🔧 Installation

1. Clone the repository:
  git clone https://github.com/N4thapatC/GED-Subject-Planner.git

2. Open `index.html` in your browser.

No build tools or server required.

---

## 📌 Future Improvements

- User login & result history
- Backend database integration
- Sheet e-commerce system

---

## Author

Developed as an educational exam strategy analysis project.
