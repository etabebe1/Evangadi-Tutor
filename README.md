# Evangadi-Tutor

# Profile Card Project – HTML & CSS Basics

## 📌 About This Project
This is a simple project I made to demonstrate the basics of **HTML** and **CSS**.  
In this lesson, we built a **Profile Card** step by step, starting from the structure with HTML and then styling it with CSS.  

The goal is to show how HTML provides the **structure** of a webpage, and CSS adds the **style** to make it look nice.

---

## 🛠 What We Learned
1. **HTML Basics**
   - `<h1>` for titles  
   - `<p>` for paragraphs  
   - `<a>` for links  
   - `<img>` for images  
   - `<div>` for grouping content  

2. **CSS Basics**
   - Changing background colors  
   - Styling text (color, font)  
   - Adding spacing and layout  
   - Using `class` selectors  

3. **Small Project: Profile Card**
   - A simple card with an image, name, and description.  
   - Added styles for rounded corners, shadow, and centered layout.  

---

## 💻 Code Example

Here’s the final code we built together:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Profile Card</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }
    .card {
      width: 300px;
      margin: 50px auto;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
      text-align: center;
    }
    .card img {
      width: 100px;
      border-radius: 50%;
    }
    .card h2 {
      margin: 10px 0;
    }
    .card p {
      color: #777;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://via.placeholder.com/100" alt="Profile Picture">
    <h2>John Doe</h2>
    <p>Student & Web Developer</p>
  </div>
</body>
</html>
