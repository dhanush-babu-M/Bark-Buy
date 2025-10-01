# 🐾 Bark & Buy – Online Pet Store

A **frontend e-commerce style pet store** built with **HTML, CSS, and JavaScript**. This project was created to strengthen frontend fundamentals by simulating a **real-world online shopping experience**.

---



## 🌟 Why This Project?

I chose this project because **e-commerce websites are common in the industry** and provide practical learning opportunities. Building an online pet store was simple, relatable, and allowed me to practice:

-   **HTML** → for semantic structure
-   **CSS** → for design & responsiveness
-   **JavaScript** → for interactivity (validation & filtering)

---

## 🛠️ Tech Stack

-   **HTML5** – Semantic structure (`<header>`, `<nav>`, `<section>`, `<footer>`)
-   **CSS3** – Flexbox, Grid, Media Queries for responsive layouts
-   **JavaScript (ES6)** – DOM manipulation, event handling, form validation, filtering

---

## 📌 Features

-   🧭 **Navigation bar** for browsing
-   🐕 **Product display grid** with filtering options (₹0–10, ₹0–50)
-   📝 **Contact form** with JavaScript validation
-   ⭐ **Review/Feedback option**
-   📱 **Responsive design** (Flexbox + Grid + Media Queries)

---

## 🚀 Key Implementation Details

### 🔍 Price Filtering

-   Each product has a **custom attribute** `data-price`:
    ```html
    <div class="product" data-price="25">Dog Food</div>
    ```
-   In **JavaScript**, filtering is handled🐾 Bark & Buy – Online Pet Store

A frontend e-commerce style pet store built with HTML, CSS, and JavaScript.
This project was created to strengthen frontend fundamentals by simulating a real-world online shopping experience.

🚀 Live Demo

You can view and interact with the live project here:

➡️ barkandbuy.netlify.app

🌟 Why This Project?

I chose this project because e-commerce websites are common in the industry and provide practical learning opportunities.
Building an online pet store was simple, relatable, and allowed me to practice:

HTML → Semantic structure

CSS → Design & responsiveness

JavaScript → Interactivity (validation & filtering)

🛠️ Tech Stack

HTML5 – Semantic structure (<header>, <nav>, <section>, <footer>)

CSS3 – Flexbox, Grid, Media Queries for responsive layouts

JavaScript (ES6) – DOM manipulation, event handling, form validation, filtering

📌 Features

🧭 Navigation bar for browsing

🐕 Product display grid with filtering options (₹0–10, ₹0–50)

📝 Contact form with JavaScript validation

⭐ Review/Feedback option

📱 Responsive design (Flexbox + Grid + Media Queries)

🚀 Key Implementation Details
🔍 Price Filtering

Each product has a custom attribute data-price:

<div class="product" data-price="25">Dog Food</div>


In JavaScript, filtering is handled with:

document.querySelectorAll('.product').forEach(product => {
    const price = parseInt(product.getAttribute('data-price'));
    if (price <= selectedRange) {
        product.style.display = "block";
    } else {
        product.style.display = "none";
    }
});


✅ This makes filtering dynamic without page reload.

📧 Contact Form Validation

Added event listeners to check required fields

Validates:

Email format (regex)

Name & message not empty

Shows error messages for invalid input → prevents incorrect submissions

📱 Responsiveness

Used Flexbox & CSS Grid for layouts

Applied media queries to adapt navigation, grids, and font sizes for mobile devices

🧠 Challenges Faced

Making the website responsive across devices

Implementing JavaScript form validation correctly

Both challenges improved my problem-solving skills with layouts & DOM manipulation

📈 Scalability & Improvements
Scalability – If products grow into thousands:

Implement pagination or lazy loading

Fetch dynamically via APIs

Use caching for performance

Making it Industry-Ready:

Add a backend (Node.js / Java + MySQL)

Implement authentication, cart & payment system

Optimize frontend (minify CSS/JS, optimize images)

Ensure security (input sanitization) & cross-browser support

🎯 Learning Outcomes

Stronger grasp of frontend fundamentals

Hands-on practice with responsive design

Real-world use of DOM manipulation & validation

Understanding how to scale and improve projects

📌 This project is for learning purposes, showcasing practical application of HTML, CSS, and JavaScript in a real-world inspired system.
