# Case Study: Dribble Clone
## Date:29/3/2026

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Design a navigation bar with links: Inspiration, Find Work, Learn Design, Go Pro, Sign In, Sign Up.

### Step 5:
Add a catchy headline with a search bar.

### Step 6:
Use ```<div>``` containers for each dribbble shot thumbnail.

### Step 7:
Include designer name and likes count below each image.

### Step 8:
Include text like “Find your next design inspiration” with a button (“Join Dribbble” or “Explore”).

### Step 9:
Create a footer with your name and register number.

### Step 10:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="main">

<div class="navbar">
    <div>
        <a href="#">Shots</a>
        <a href="#">Designers</a>
        <a href="#">Teams</a>
        <a href="#">Community</a>
        <a href="#">Jobs</a>
    </div>

    <div>
        <a href="#">Sign up</a>
        <a href="#">Sign in</a>
    </div>
</div>

<div class="hero">
    <h2>What are you working on?</h2>
    <p>Show your creativity to the world</p>
    <button class="btn1">Learn more</button>
    <button class="btn2">Sign up</button>
</div>

<div class="filter">
    <b>Popular • Shots • Now</b>
</div>

<div class="grid">

    <div class="card">
        <img src="lo.jpg">
        <div class="title">Love</div>
        <div class="info">Love Design</div>
    </div>

    <div class="card">
        <img src="nature.jpg">
        <div class="title">Nature heals</div>
        <div class="info">Nature UI</div>
    </div>

    <div class="card">
        <img src="music.jpg">
        <div class="title">Love music</div>
        <div class="info">Music dashboard</div>
    </div>

    <div class="card">
        <img src="quote.jpg">
        <div class="title">Inspire</div>
        <div class="info">Quote </div>
    </div>

</div>

</div>

<footer>
    Dharshan Sanjay | Reg No: 25013972
</footer>

</body>
</html>
body {
    margin: 0;
    font-family: Arial;
    background: #f4f4f4;

    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.main {
    flex: 1;
}

.navbar {
    background: #f26a6a;
    color: rgb(239, 187, 187);
    padding: 15px 30px;
    display: flex;
    justify-content: space-between;
}

.navbar a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

.hero {
    background: #444;
    color: white;
    text-align: center;
    padding: 30px;
}

.hero button {
    padding: 8px 15px;
    margin: 10px;
    border: none;
    border-radius: 5px;
}

.btn1 {
    background: lightgray;
}

.btn2 {
    background: hotpink;
    color: white;
}

.filter {
    text-align: center;
    padding: 10px;
    background: #eee;
}

.grid {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.card {
    flex: 1;
    max-width: 250px;
    background: white;
    border-radius: 10px;
    overflow: hidden;
}

.card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.title {
    font-weight: bold;
    padding: 5px 10px;
}

.info {
    padding: 0 10px 10px;
    font-size: 14px;
}

footer {
    background: #ebcfcf;
    color: rgb(236, 38, 38);
    text-align: center;
    padding: 15px;
}

```


## OUTPUT:


## RESULT:
The project for responsive web design in creating a clone of dribble.com is completed successfully.
