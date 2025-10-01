🐾 Bark & Buy – Online Pet Store

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


In JavaScript, filtering is handled like this:

document.querySelectorAll('.product').forEach(product => {
    const price = parseInt(product.getAttribute('data-price'));
    if (price <= selectedRange) {
        product.style.display = "block";
    } else {
        product.style.display = "none";
    }
});


✅ This makes filtering dynamic without reloading the page.

📧 Contact Form Validation

Added event listeners to the form to check inputs before submission

Validates that:

Name and message fields are not empty

Email format is correct using regex

Displays error messages for invalid input, preventing incorrect submissions

📱 Responsiveness

Used a combination of Flexbox and CSS Grid to create flexible and robust layouts

Applied media queries to adapt the navigation bar, product grids, and font sizes for different screen sizes

🧠 Challenges Faced

Making the website fully responsive across a wide range of devices

Implementing client-side JavaScript form validation correctly

Both challenges improved my problem-solving skills with CSS layouts and DOM manipulation

📈 Scalability & Improvements
Scalability – If products grow into the thousands:

Implement pagination or lazy loading

Fetch product data dynamically from APIs

Use caching strategies to reduce load times

Making it Industry-Ready:

Add a backend (Node.js / Java + MySQL)

Implement user authentication, shopping cart, and payment system

Optimize frontend assets (minify CSS/JS, compress images)

Ensure security (input sanitization) & cross-browser support

🎯 Learning Outcomes

Stronger grasp of frontend fundamentals (HTML, CSS, JS)

Hands-on practice with responsive design techniques

Real-world application of DOM manipulation and event handling

Understanding of scaling and improving frontend projects

📌 This project is for learning purposes, showcasing practical application of HTML, CSS, and JavaScript in a real-world inspired system.
