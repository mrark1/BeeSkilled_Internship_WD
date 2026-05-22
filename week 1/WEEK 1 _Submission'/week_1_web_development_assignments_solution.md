# Week 1 – Web Development Assignment Solutions



---

# Assignment 1: Portfolio Webpage

## index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arpit Raj Katiyar Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <img src="profile.jpg" alt="Profile Photo" class="profile-img">
        <h1>Arpit Raj Katiyar</h1>
        <p>B.Tech CS-AIML Student | Web Developer | Python Enthusiast</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>
            Hello! I am Arpit Raj Katiyar, a passionate B.Tech student interested in
            Web Development, Artificial Intelligence, and Python Programming.
        </p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <ul>
            <li>B.Tech in CS-AIML – Kanpur Institute of Technology</li>
            <li>12th – CBSE Board</li>
            <li>10th – CBSE Board</li>
        </ul>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Python</li>
            <li>C++</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: arpitraj@example.com</p>
        <p>Phone: +91 9876543210</p>
    </section>

    <footer>
        <p>© 2026 Arpit Raj Katiyar. All Rights Reserved.</p>
    </footer>

</body>
</html>
```

---

## style.css

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #0d6efd;
    color: white;
    text-align: center;
    padding: 30px;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid white;
}

section {
    background: white;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

h2 {
    color: #0d6efd;
}

ul {
    list-style-type: square;
}

footer {
    text-align: center;
    background-color: #222;
    color: white;
    padding: 15px;
}
```

---

# Practice Questions Solutions

---

# Question 1: HTML Page with Heading, Paragraph, and Image

```html
<!DOCTYPE html>
<html>
<head>
    <title>Simple Webpage</title>
</head>
<body>

    <h1>Welcome to My Website</h1>

    <p>
        This is a simple HTML page containing a heading, paragraph, and image.
    </p>

    <img src="nature.jpg" alt="Nature Image" width="300">

</body>
</html>
```

---

# Question 2: Student Table

```html
<!DOCTYPE html>
<html>
<head>
    <title>Student Table</title>
</head>
<body>

    <h2>Student Details</h2>

    <table border="1" cellpadding="10">
        <tr>
            <th>Name</th>
            <th>Roll Number</th>
            <th>Marks</th>
        </tr>

        <tr>
            <td>Arpit</td>
            <td>101</td>
            <td>92</td>
        </tr>

        <tr>
            <td>Rahul</td>
            <td>102</td>
            <td>88</td>
        </tr>

        <tr>
            <td>Priya</td>
            <td>103</td>
            <td>95</td>
        </tr>
    </table>

</body>
</html>
```

---

# Question 3: Registration Form

```html
<!DOCTYPE html>
<html>
<head>
    <title>Registration Form</title>
</head>
<body>

    <h2>Registration Form</h2>

    <form>

        <label>Name:</label>
        <input type="text" name="name"><br><br>

        <label>Email:</label>
        <input type="email" name="email"><br><br>

        <label>Gender:</label>
        <select>
            <option>Male</option>
            <option>Female</option>
            <option>Other</option>
        </select><br><br>

        <input type="submit" value="Register">

    </form>

</body>
</html>
```

---

# Question 4: Navigation Links Between Three Pages

## home.html

```html
<!DOCTYPE html>
<html>
<head>
    <title>Home</title>
</head>
<body>

    <h1>Home Page</h1>

    <a href="about.html">Go to About Page</a><br>
    <a href="contact.html">Go to Contact Page</a>

</body>
</html>
```

---

## about.html

```html
<!DOCTYPE html>
<html>
<head>
    <title>About</title>
</head>
<body>

    <h1>About Page</h1>

    <a href="home.html">Go to Home Page</a><br>
    <a href="contact.html">Go to Contact Page</a>

</body>
</html>
```

---

## contact.html

```html
<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
</head>
<body>

    <h1>Contact Page</h1>

    <a href="home.html">Go to Home Page</a><br>
    <a href="about.html">Go to About Page</a>

</body>
</html>
```

---

# How to Run the Project

1. Create a folder on your computer.
2. Save all HTML files inside that folder.
3. Save the CSS file as `style.css`.
4. Add your profile photo and rename it `profile.jpg`.
5. Open `index.html` in your browser.

---

# Topics Covered

- HTML Structure
- Semantic Tags
- Tables
- Forms
- Navigation Links
- CSS Styling
- Layout Design

---

# Submitted By

Arpit Raj Katiyar
B.Tech CS-AIML
Kanpur Institute of Technology

