<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barak Chauffeur Service</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .trip-booking {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .trip-booking input, .trip-booking button {
            padding: 10px;
            font-size: 16px;
        }
        .trip-booking button {
            background-color: red; /* Initial color for both buttons */
            color: #fff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .trip-booking button.booked {
            background-color: green; /* Color after booking */
        }
        .login-signup {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 10px;
        }
        .login-signup a {
            text-decoration: none;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            flex: 1;
        }
        .login-signup a.login {
            background-color: skyblue; /* Sky blue color for login button */
            color: #fff;
        }
        .login-signup a.signup {
            background-color: red; /* Red color for signup button */
            color: #fff;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
            margin-top: 20px;
        }
        .popup {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            padding: 20px;
            border-radius: 10px;
            display: none;
        }
        /* Carousel styles */
        .carousel {
            max-width: 800px;
            margin: 0 auto 20px auto;
            overflow: hidden;
            position: relative;
        }
        .carousel .slides {
            display: flex;
            transition: transform 0.5s ease;
        }
        .carousel img {
            width: 100%;
            display: block;
        }
        .carousel-nav {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            width: 100%;
            display: flex;
            justify-content: space-between;
        }
        .carousel-nav .arrow {
            background-color: rgba(0, 0, 0, 0.5);
            color: #fff;
            padding: 10px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .carousel-nav .arrow:hover {
            background-color: rgba(0, 0, 0, 0.7);
        }
    </style>
</head>
<body>

<header>
    <h1>Barak Chauffeur Service 24x7</h1>
</header>

<!-- Carousel Section -->
<div class="carousel">
    <div class="slides">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcShjemFRkXyqcuEt2BF6lO5XGaQtDd4YXuhsg&usqp=CAU" alt="Slide 1">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfldSjzJFqk68LmXd2p9o5pg3jM3JXW3TxyA&usqp=CAU" alt="Slide 2">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwfQDZaefsdjQQvAlu916sbhnooo5LDLhGHQ&usqp=CAU" alt="Slide 3">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT7TIOENWyS4iA1Ri_Uxbk3ZcbHFHiy4In21A&usqp=CAU" alt="Slide 4">
    </div>
    <div class="carousel-nav">
        <div class="arrow prev" onclick="prevSlide()">&#10094;</div>
        <div class="arrow next" onclick="nextSlide()">&#10095;</div>
    </div>
</div>

<!-- Main Content Container -->
<div class="container">
    <p>Barak Chauffeur Service offers premium, yet affordable, chauffeur services that can be booked with ease at your fingertips. Our services include transfers within the city and to nearby districts, ensuring you reach your desired destination comfortably and on time. Our fleet of premium cars features well-maintained interiors, air conditioning, WiFi, magazines, tissue paper, hygienic aro purified water bottles, and large LED screens for your entertainment. We also specialize in airport transfers, providing a seamless and luxurious travel experience from start to finish.</p>

    <div class="trip-booking">
        <input type="date" id="trip-date" name="trip-date">
        <input type="text" id="pickup-location" name="pickup-location" placeholder="Enter Pickup Location">
        <input type="text" id="dropoff-location" name="dropoff-location" placeholder="Enter Dropoff Location">
        <button id="book-now" onclick="bookNow()">Book Now</button>
    </div>
    <div class="login-signup">
        <a href="login.html" class="login">Login</a>
        <a href="/storage/emulated/0/Bills/New folder/Credentials /login.html" class="signup">Sign Up</a>
    </div>
</div>

<div class="footer">
    <p>Contact Us | Privacy Policy | Terms & Conditions</p>
</div>

<div class="popup" id="booking-success-popup">
    Booking successful! Your booking ID is: <span id="booking-id"></span>
</div>

<script>
    // Automatic slideshow functionality
    var slides = document.querySelector('.slides');
    var slideWidth = slides.clientWidth;
    var slideIndex = 0;

    function slideNext() {
        slideIndex++;
        if (slideIndex * slideWidth >= slides.scrollWidth) {
            slideIndex = 0;
        }
        slides.style.transform = `translateX(${-slideIndex * slideWidth}px)`;
    }

    function slidePrev() {
        slideIndex--;
        if (slideIndex < 0) {
            slideIndex = slides.children.length - 1;
        }
        slides.style.transform = `translateX(${-slideIndex * slideWidth}px)`;
    }

    setInterval(slideNext, 3000); // Change slide every 3 seconds

    // Manual navigation with arrows
    function nextSlide() {
        slideNext();
    }

    function prevSlide() {
        slidePrev();
    }

    // Function to handle booking process
    function bookNow() {
        var tripDate = document.getElementById('trip-date').value;
        var pickupLocation = document.getElementById('pickup-location').value;
        var dropoffLocation = document.getElementById('dropoff-location').value;

        // Simulate booking confirmation
        var bookingId = generateBookingId();
        showBookingConfirmation(bookingId);

        // Reset input fields
        document.getElementById('trip-date').value = '';
        document.getElementById('pickup-location').value = '';
        document.getElementById('dropoff-location').value = '';

        // Change button style to 'booked'
        var bookNowButton = document.getElementById('book-now');
        bookNowButton.textContent = 'Booked';
        bookNowButton.classList.add('booked');
    }

    // Function to generate random booking ID
    function generateBookingId() {
        return Math.floor(Math.random() * 9000000000) + 1000000000; // Generates a 10-digit number
    }

    // Function to show booking confirmation popup
    function showBookingConfirmation(bookingId) {
        var popup = document.getElementById('booking-success-popup');
        var bookingIdSpan = document.getElementById('booking-id');
        bookingIdSpan.textContent = bookingId;

        popup.style.display = 'block';
        setTimeout(function() {
            popup.style.display = 'none';
        }, 5000); // Popup disappears after 5 seconds
    }
</script>

</body>
</html>
</html>login
