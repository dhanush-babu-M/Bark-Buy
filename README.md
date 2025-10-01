🐾 Bark & Buy – Online Pet Store
A frontend e-commerce style pet store built with HTML, CSS, and JavaScript. This project was created to strengthen frontend fundamentals by simulating a real-world online shopping experience.

🚀 Live Demo
You can view and interact with the live project here:

➡️ barkandbuy.netlify.app

🌟 Why This Project?
I chose this project because e-commerce websites are common in the industry and provide practical learning opportunities. Building an online pet store was simple, relatable, and allowed me to practice:

HTML → for semantic structure

CSS → for design & responsiveness

JavaScript → for interactivity (validation & filtering)

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

HTML

<div class="product" data-price="25">Dog Food</div>
In JavaScript, filtering is handled by checking this attribute against the selected range and showing or hiding the product accordingly:

JavaScript

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
Added event listeners to the form to check inputs before submission.

Validates that the name and message fields are not empty and that the email format is correct using regex.

Displays error messages for invalid input, preventing incorrect submissions.

📱 Responsiveness
Used a combination of Flexbox and CSS Grid to create flexible and robust layouts.

Applied media queries to adapt the navigation bar, product grids, and font sizes for different screen sizes, ensuring a good user experience on both mobile and desktop.

🧠 Challenges Faced
Making the website fully responsive across a wide range of devices.

Implementing client-side JavaScript form validation correctly.

Both challenges improved my problem-solving skills with CSS layouts and DOM manipulation.

📈 Scalability & Improvements
Scalability – If products grow into the thousands:

Implement pagination or lazy loading to improve performance.

Fetch product data dynamically from APIs.

Use caching strategies to reduce load times.

Making it Industry-Ready:

Add a backend (e.g., Node.js or Java with a MySQL database).

Implement user authentication, a shopping cart, and a payment system.

Optimize frontend assets (minify CSS/JS, compress images).

Ensure security (input sanitization) and cross-browser support.

🎯 Learning Outcomes
Stronger grasp of frontend fundamentals (HTML, CSS, JS).

Hands-on practice with responsive design techniques.

Real-world application of DOM manipulation and event handling.

A better understanding of how to scale and improve a frontend project.

📌 This project is for learning purposes, showcasing the practical application of HTML, CSS, and JavaScript in a real-world inspired system.
