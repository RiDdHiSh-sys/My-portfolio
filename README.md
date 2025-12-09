# My-portfolio
index:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Name | Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Riddhish</span> Vashisht</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="skills.html">Skills</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="showcase">
        <div class="container">
            <h1>Welcome To My Portfolio</h1>
            <p>Showcasing my projects and skills in web development.</p>
        </div>
  About:
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Student Name</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Riddhish</span> Vashisht</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li class="current"><a href="about.html">About</a></li>
                    <li><a href="skills.html">Skills</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <h2>About Me</h2>
        <div class="about-content">
            <img src="PHOTO.JPG" alt="Profile Picture" class="profile-image">
            <p>Hi, I'm Riddhish, a first-year B.Tech CSE (AI) student at KIET Group of Institutions.I am currently also a member technical club called CPBYTE.
I'm passionate about technology, AI, and building things that solve real problems. Being early in my engineering journey, I love exploring new tools, ideas, and projects that help me grow both technically and creatively.</p>
            <p>I'm curious by nature — whether it's understanding how systems work, experimenting with new concepts, or diving into discussions around technology, markets, geopolitics, and how they shape the world. I enjoy challenging assumptions, learning deeply, and improving a little every day.</p>
            <p>My goal is to evolve into a strong problem-solver and engineer, build impactful projects, and constantly push myself to think smarter and work smarter.</p>
        </div>
    </main>
</body>
</html>
skills:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skills | Student Name</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Riddhish</span> Vashisht</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li class="current"><a href="skills.html">Skills</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <h2>Skills & Projects</h2>
        <div class="skills-container">
            <div class="skill-card">
                <h3>HTML5 & CSS3</h3>
                <p>I have solid skills in HTML and CSS, enabling me to build clean, well-structured, and responsive webpages. I work confidently with modern styling tools like flexbox and grid to create user-friendly, visually consistent layouts.</p>
            </div>
            <div class="skill-card">
                <h3>Python</h3>
                <p>I have a solid foundation in Python, with hands-on experience writing clean code, solving logical problems, and building small projects. I’m comfortable with core concepts like functions, loops, data structures, and basic OOP.</p>
            </div>
            <div class="skill-card">
                <h3>C and Java</h3>
                <p>I’m developing a solid foundation in C and Java, with hands-on practice in core concepts like variables, loops, functions, and basic object-oriented ideas. I also have a good understanding of strings and arrays in both languages, and I’m actively strengthening my logic-building and problem-solving skills through regular coding practice</p>
            </div>
        </div>
    </main>
</body>
</html>
Contact:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact | Student Name</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Riddhish</span> Vashisht</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="skills.html">Skills</a></li>
                    <li class="current"><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <h2>Contact Me</h2>
        <form class="contact-form">
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>
            </div>
            <button type="submit" class="submit-btn">Send Message</button>
        </form>
    </main>
</body>
</html>
CSS:
/* General Body Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
    padding: 0 20px;
}

/* Header and Navigation Bar */
header {
    background: #333;
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #77aaff 3px solid;
}

header a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
}

header ul {
    padding: 0;
    margin: 0;
    list-style: none;
}

header li {
    display: inline;
    padding: 0 20px 0 20px;
}

header #branding {
    float: left;
}

header #branding h1 {
    margin: 0;
}

header nav {
    float: right;
    margin-top: 10px;
}

header .highlight, header .current a {
    color: #77aaff;
    font-weight: bold;
}

header a:hover {
    color: #ccc;
    font-weight: bold;
}

/* Main Content Area */
main {
    padding: 20px 0;
}

/* Home Page */
.showcase {
    min-height: 400px;
    background: #333 url('https://via.placeholder.com/1500x400') no-repeat 0 -200px; /* Placeholder background */
    text-align: center;
    color: #ffffff;
}

.showcase h1 {
    margin-top: 100px;
    font-size: 55px;
    margin-bottom: 10px;
}

.showcase p {
    font-size: 20px;
}

/* About Page - Using Float */
.about-content {
    overflow: hidden; /* Contains the floated elements */
}

.profile-image {
    float: left;
    width: 250px;
    height: 250px;
    margin-right: 20px;
    border-radius: 50%;
}

/* Skills Page - Using Flexbox */
.skills-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-top: 20px;
}

.skill-card {
    background: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    margin: 10px;
    width: 30%;
    box-sizing: border-box;
    text-align: center;
}

.skill-card h3 {
    color: #77aaff;
}

/* Contact Page */
.contact-form {
    background: #fff;
    padding: 20px;
    border: 1px solid #ddd;
}

.form-group {
    margin-bottom: 15px;
}

.form-group label {
    display: block;
    margin-bottom: 5px;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 8px;
    box-sizing: border-box;
}

.submit-btn {
    display: block;
    width: 100%;
    padding: 10px;
    background: #77aaff;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 18px;
}
    </section>
</body>
</html>
