<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h2>Event Registration Form</h2>
        <form id="registrationForm">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="event">Select Event:</label>
            <select id="event" name="event" required>
                <option value="">-- Choose an Event --</option>
                <option value="music">Music Concert</option>
                <option value="tech">Tech Conference</option>
                <option value="sports">Sports Meetup</option>
            </select>

            <button type="submit">Register</button>
        </form>
        <p id="message"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>

