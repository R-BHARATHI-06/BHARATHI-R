<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            padding: 10px 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            background: #fff;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        form input, form select {
            display: block;
            margin: 10px 0;
            padding: 10px;
            width: 100%;
            max-width: 400px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form input[type="submit"] {
            background: #5cb85c;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Our Gym</h1>
</header>

<nav>
    <a href="#registration">Registration</a>
    <a href="#packages">Packages</a>
    <a href="#timings">Timings</a>
    <a href="#offers">Offers</a>
    <a href="#gym-gears">Gym Gears</a>
    <a href="#nutrition">Nutrition & Supplements</a>
</nav>

<section id="registration">
    <h2>Registration Form</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone" required>
        
        <label for="package">Select Package:</label>
        <select id="package" name="package">
            <option value="basic">Basic</option>
            <option value="standard">Standard</option>
            <option value="premium">Premium</option>
        </select>
        
        <input type="submit" value="Register">
    </form>
</section>

<section id="packages">
    <h2>Packages</h2>
    <p>We offer the following membership packages:</p>
    <ul>
        <li>Basic Package: Access to gym facilities during off-peak hours.</li>
        <li>Standard Package: Access to gym facilities at any time, plus one personal training session per month.</li>
        <li>Premium Package: Unlimited access to gym facilities, personal training sessions, and group classes.</li>
    </ul>
</section>

<section id="timings">
    <h2>Timings</h2>
    <p>Our gym is open during the following hours:</p>
    <ul>
        <li>Monday to Friday: 6:00 AM - 10:00 PM</li>
        <li>Saturday: 8:00 AM - 8:00 PM</li>
        <li>Sunday: 8:00 AM - 6:00 PM</li>
    </ul>
</section>

<section id="offers">
    <h2>Current Offers</h2>
    <p>Check out our latest offers and discounts:</p>
    <ul>
        <li>Get 10% off on the Premium Package for the first 3 months.</li>
        <li>Refer a friend and get one month free.</li>
        <li>Sign up for a year and get two months free.</li>
    </ul>
</section>

<section id="gym-gears">
    <h2>Gym Gears</h2>
    <p>We offer a range of gym gears and accessories:</p>
    <ul>
        <li>Dumbbells and free weights</li>
        <li>Resistance bands</li>
        <li>Yoga mats</li>
        <li>Fitness trackers</li>
    </ul>
</section>

<section id="nutrition">
    <h2>Nutrition & Supplements</h2>
    <p>Enhance your workouts with our range of nutrition and supplements:</p>
    <ul>
        <li>Protein powders</li>
        <li>Pre-workout supplements</li>
        <li>Vitamins and minerals</li>
        <li>Meal replacement shakes</li>
    </ul>
</section>

<footer>
    <p>&copy; 2024 Our Gym. All rights reserved.</p>
</footer>

</body>
</html>
