<!DOCTYPE html>
<html>
<head>
    <title>Document</title>
</head>
<body>
    <ol>
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
    </ol>

    <!-- External image from Pexels -->
    <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Beautiful Landscape" width="300">

    <img src="Papi.png" alt="Screenshot" width="300">

    <table border="1">
        <tr><th>Name</th><th>Address</th><th>Mobile</th><th>Email</th></tr>
        <tr><td>Tonny</td><td>123 Main St</td><td>+123456789</td><td>lordjarvis02@gmail.com</td></tr>
        <tr><td>Jane</td><td>456 Mombasa St</td><td>+987654321</td><td>janeboro2@gmail.com</td></tr>
        <tr><td>Michael</td><td>789 Oak St</td><td>+2567894431</td><td>michaelwamutu09@gmail.com</td></tr>
        <tr><td>Emily</td><td>321 Pine St</td><td>+25466712344</td><td>emilyndirangu04@yahoo.com</td></tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
        <input type="text" name="name" placeholder="Full Name" required><br>
        <input type="email" name="email" placeholder="Email" required><br>
        <input type="password" name="password" placeholder="Password" required minlength="6"><br>
        <input type="date" name="dob" required><br>

        <!-- Dropdown -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender">
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select><br>

        <!-- Radio Buttons -->
        <p>Subscription Plan:</p>
        <input type="radio" name="plan" value="basic" required> Basic
        <input type="radio" name="plan" value="premium"> Premium <br>

        <!-- Checkboxes -->
        <p>Interests:</p>
        <input type="checkbox" name="interest" value="sports"> Sports
        <input type="checkbox" name="interest" value="music"> Music
        <input type="checkbox" name="interest" value="tech"> Technology <br>

        <button type="submit">Register</button>
    </form>
</body>
</html>
