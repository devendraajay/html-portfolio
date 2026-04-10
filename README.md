# Personal Portfolio Website — Week 1 Submission

**Name:** Devendra Ajay Kumar T  
**Student ID:** CB.SC.U4AIE23070  
**Course:** Web Development — Week 1: HTML  
**University:** Amrita School of Artificial Intelligence, Amrita Vishwa Vidyapeetham, Coimbatore  
**Email:** ajaykumartdevendra@gmail.com  

---

## Project Overview

This is a personal portfolio website built using pure HTML5 as part of the Week 1 assignment on HTML fundamentals. The website showcases personal information, technical skills, and academic projects across multiple structured sections. It demonstrates the use of semantic HTML, proper document structure, internal navigation, forms with validation, and responsive layout — all without any external libraries or frameworks.

---

## Project Goals and Objectives

- Build a complete, multi-section HTML webpage from scratch
- Apply semantic HTML5 tags correctly (`header`, `nav`, `main`, `section`, `footer`)
- Create a working contact form with input validation attributes
- Use internal anchor navigation to move between sections
- Embed images with proper `alt` text for accessibility
- Structure code in a clean, readable, and well-organized manner

---

## Repository Structure

```
your-repo/
├── index.html         ← Main portfolio page (all content)
├── README.md          ← This file
└── images/
    └── profile.jpg    ← Profile picture used in the hero section
```

---

## Sections Included

| Section | Description |
|---|---|
| Header & Navigation | Sticky header with name, degree info, and nav links |
| Hero | Profile photo, greeting, and one-line introduction |
| About | Personal details in a grid layout (name, ID, degree, email, location) |
| Skills | Grouped unordered lists for languages, AI/ML tools, technologies, and concepts |
| Projects | Project cards with title, description, and GitHub links |
| Contact | Form with name, email, subject dropdown, message textarea, and submit button |
| Footer | Copyright info with GitHub and LinkedIn links |


## HTML Concepts Used

### 1. HTML5 Document Structure
Every HTML file must begin with a proper structure. This project uses `<!DOCTYPE html>` to declare HTML5, followed by `<html lang="en">`, `<head>` (for metadata and styles), and `<body>` (for visible content).

### 2. Semantic Tags
Semantic tags give meaning to the structure of a webpage. This project uses:
- `<header>` — top navigation bar with name and links
- `<nav>` — navigation menu containing anchor links
- `<main>` — wraps all primary page content
- `<section>` — individual page sections (About, Skills, Projects, Contact)
- `<footer>` — bottom of page with copyright and social links

### 3. Headings and Paragraphs
`<h1>` is used for the main site title in the header. `<h2>` is used for each section heading. `<h3>` is used for skill subcategories and project titles. `<p>` is used for descriptive text throughout.

### 4. Navigation with Internal Links
The `<nav>` element contains `<a>` tags with `href="#section-id"` values. Clicking these links smoothly scrolls the page to the matching `<section id="...">` element — no JavaScript needed.

### 5. Images with Alt Text
The profile photo is inserted using `<img src="images/profile.jpg" alt="Devendra Ajay Kumar T's profile picture" />`. The `alt` attribute is required for accessibility — screen readers use it to describe the image.

### 6. Lists
Skills are displayed using `<ul>` (unordered list) and `<li>` (list item) tags. Unordered lists are semantically appropriate here because the skills have no specific ranking or order.

### 7. Forms and Input Validation
The contact section uses a `<form>` with the following input elements:
- `<input type="text">` — for full name
- `<input type="email">` — for email (browser validates format automatically)
- `<select>` with `<option>` tags — for subject dropdown
- `<textarea>` — for the message body
- `<button type="submit">` — to submit the form

HTML5 validation attributes used: `required`, `minlength`, `type="email"`.

### 8. HTML Attributes
Key attributes used throughout:
- `id` — uniquely identifies sections for internal navigation
- `class` — groups elements for CSS styling
- `href` — specifies link destination
- `src` — specifies image file path
- `alt` — image description for accessibility
- `target="_blank"` — opens external links in a new tab
- `placeholder` — hint text inside form inputs

---

## Projects Showcased

### Brain Tumor Segmentation (3D Deep Learning)
A 3D brain tumor segmentation pipeline built using a custom Strassen Convolution U-Net, V-Net, and SegNet on the BraTS dataset. Grad-CAM explainability was added to visualize model decisions at the feature level.

### Multimodal Depression Detection
A system combining BERT (text), Whisper (audio), LSTM, and SVM to detect depression signals from multimodal input. Deployed with a Streamlit interface for real-time predictions.

### InvenTrack — Inventory Forecasting System
An inventory demand forecasting system using ARIMA, SARIMA, and LSTM on the Walmart M5 dataset. Produced alongside a full IEEE-format research paper and project report.

---

## Challenges Faced

- Understanding the difference between block-level and inline HTML elements
- Structuring the form correctly with labels linked to inputs using `for` and `id`
- Using `href="#section-id"` properly so internal navigation scrolls to the right place
- Organizing the skills section into logical groups using nested lists

---

