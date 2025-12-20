# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Event Registration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
    <h1>Tech Fest 2025</h1>
    <img src="event.jpg" alt="Event Image" class="banner">

    <form action="success.html">
        <label>Name:</label>
        <input type="text" required>

        <label>Email:</label>
        <input type="email" required>

        <label>Phone Number:</label>
        <input type="tel" required>

        <label>Event Type:</label>
        <select required>
            <option>Workshop</option>
            <option>Seminar</option>
            <option>Hackathon</option>
        </select>

        <button type="submit">Register</button>
    </form>
</div>

</body>
</html>
```
```
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

.container {
    width: 400px;
    margin: auto;
    background: white;
    padding: 20px;
    border-radius: 8px;
}

h1 {
    text-align: center;
    color: #333;
}

.banner {
    width: 100%;
    border-radius: 5px;
}

label {
    display: block;
    margin-top: 10px;
}

input, select {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
}

button {
    margin-top: 15px;
    width: 100%;
    padding: 10px;
    background-color: #007BFF;
    color: white;
    border: none;
    cursor: pointer;
}
```
```
<!DOCTYPE html>
<html>
<head>
    <title>Registration Successful</title>
</head>
<body>
    <h2>Registration Successful!</h2>
    <p>Thank you for registering for the event.</p>
</body>
</html>
```

# OUTPUT:

![WhatsApp Image 2025-12-20 at 5 49 36 PM](https://github.com/user-attachments/assets/eb2d8044-2380-4a6c-803e-de231c7e7a0f)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
