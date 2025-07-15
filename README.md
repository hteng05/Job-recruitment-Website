# Job Recruitment Website – Assignment 1

**Live Site:** [https://hteng05.github.io/Job-recruitment-Website-1/index.html](https://hteng05.github.io/Job-recruitment-Website-1/index.html)

This project is a static recruitment website developed as part of **Assignment 1** for **COS10026 – Computing Technology Inquiry Project (Semester 1, 2024)** at Swinburne University of Technology. The assignment introduces students to the foundational tools and techniques of web development, with a focus on semantic HTML, external CSS styling, accessibility standards, and professional layout structuring.

---

## About the Unit

**COS10026 – Computing Technology Inquiry Project** is designed to provide students with a broad and practical foundation in modern web technologies. Students learn to create standards-compliant, accessible, and visually consistent web applications using HTML5 and CSS3, while also collaborating in teams to simulate real-world development environments.

---

## Project Overview

The task was to develop a **simple static job recruitment website** for a fictional IT company. It showcases available job positions and allows users to apply for a role using a structured HTML5 form. No JavaScript or server-side processing is used. All pages follow semantic markup conventions and are styled using a single validated CSS file.

The following pages are included:

- `index.html`: Company homepage
- `jobs.html`: Detailed job descriptions
- `apply.html`: Job application form with client-side validation
- `about.html`: Group profile and timetable
- `enhancements.html`: Description of implemented enhancements

---

## Features Implemented

### ✅ index.html
- Company overview with mission and logo
- Full-page layout with background graphic
- Navigation menu present on all pages

### ✅ jobs.html
- Two job listings with detailed descriptions
- Use of:
  - Hierarchical headings
  - `<section>` and `<aside>` elements
  - Ordered and unordered lists
- Structured requirements with essential/preferable skills
- Custom footer with semantic layout

### ✅ apply.html
- Fully functional form with HTML5 validation
- Fields:
  - Name, DOB, address, state (dropdown), contact info
  - Gender (radio group)
  - Skills (checkboxes)
  - Additional comments
- Validates using `pattern`, `required`, and input `type`
- Submits data via `POST` to Mercury server:
  ```
  action="https://mercury.swin.edu.au/it000000/formtest.php"
  ```

### ✅ about.html
- Group information displayed using `<dl>`, `<figure>`, and `<table>`
- Group photo with CSS styling
- Timetable using a styled HTML table
- Mailto group email link

### ✅ enhancements.html
- Lists and explains two CSS/HTML-based enhancements:
  1. Custom animation / pseudo-class effects
  2. Responsive design for mobile devices
- Each enhancement includes hyperlinks to where it’s applied and brief explanations

---

## CSS and Accessibility

- Single external stylesheet (`styles/style.css`) used for all styling
- Applied selectors: element, class, ID, grouping, pseudo-classes, and contextual
- Fluid layout: all pages reflow on browser resize
- Accessibility checked using **WAVE** extension and best practices followed (e.g., `alt` text, label association, semantic tags)

---

## Deployment

The website is deployed on GitHub Pages:  
📍 **[View Live Site](https://hteng05.github.io/Job-recruitment-Website-1/index.html)**

All file paths use **relative linking**, and folder structure strictly follows assignment requirements. The site was tested across multiple screen sizes and validated using:

- [W3C HTML5 Validator](https://validator.w3.org/nu/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

## Contribution

This assignment was developed collaboratively, with each team member contributing to content, layout, styling, form structure, and accessibility implementation. Individual reflections and accessibility reports were submitted separately on Canvas as required.

---

## Author

**Duong Ha Tien Le (@hteng05)**  
Swinburne University of Technology  
Bachelor of Computer Science  
Unit: COS10026 – Computing Technology Inquiry Project (2024)

---

## Reference

> For full project requirements and assessment criteria, refer to `assignment1_brief.pdf` in the repository.
