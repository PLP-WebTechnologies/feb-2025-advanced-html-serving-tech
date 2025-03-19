# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Registration Page</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to the Registration Page</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Steps to Register</h2>
        <ol type="I">
            <li>Fill out the form</li>
            <li>Review your details</li>
            <li>Submit the registration</li>
            <li>Check your email</li>
            <li>Log in to your account</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Featured Image</h2>
        <img src="https://images.pexels.com/photos/31190087/pexels-photo-31190087/free-photo-of-majestic-northern-harrier-in-flight-over-quincy.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load" 
             alt="free-photo-of-majestic-northern-harrier-in-flight-over-quincy" 
             width="300">
        <p>Image sourced from Pexels.com</p>
    </section>

    <!-- Contact Table -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Gideon Kibe</td>
                    <td>3KR St</td>
                    <td>0765431287</td>
                    <td>gideon@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Kiare</td>
                    <td>Tom Mboya Ave</td>
                    <td>0789786745</td>
                    <td>jane@gmail.com</td>
                </tr>
                <tr>
                    <td>Penina Johnson</td>
                    <td>Eldoret Rd</td>
                    <td>0756453423</td>
                    <td>Penina@yahoo.com</td>
                </tr>
                <tr>
                    <td>Peter John</td>
                    <td>Nairobi St</td>
                    <td>0745657654</td>
                    <td>peter@gmail.com</td>
                </tr>
                <tr>
                    <td>Moses Wilson</td>
                    <td>Nakuru Ln</td>
                    <td>071516171819</td>
                    <td>moses@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form>
            <fieldset>
                <legend>Personal Details</legend>

                <label for="name">Full Name:</label><br>
                <input type="text" 
                       id="name" 
                       name="name" 
                       placeholder="Enter your name" 
                       required><br>

                <label for="email">Email:</label><br>
                <input type="email" 
                       id="email" 
                       name="email" 
                       placeholder="your@email.com" 
                       required><br>

                <label for="password">Password:</label><br>
                <input type="password" 
                       id="password" 
                       name="password" 
                       placeholder="Create a password" 
                       minlength="8" 
                       required><br>

                <label for="birthdate">Date of Birth:</label><br>
                <input type="date" 
                       id="birthdate" 
                       name="birthdate" 
                       required><br>

                <!-- Dropdown -->
                <label for="country">Country:</label><br>
                <select id="country" name="country" required>
                    <option value="">Select a country</option>
                    <option value="tz">Tanzania</option>
                    <option value="ug">Uganda</option>
                    <option value="ke">Kenya</option>
                </select><br>

                <!-- Radio Buttons -->
                <p>Account Type:</p>
                <input type="radio" 
                       id="personal" 
                       name="account_type" 
                       value="personal" 
                       required>
                <label for="personal">Personal</label>
                <input type="radio" 
                       id="business" 
                       name="account_type" 
                       value="business">
                <label for="business">Business</label><br>

                <!-- Checkboxes -->
                <p>Interests:</p>
                <input type="checkbox" 
                       id="tech" 
                       name="interests" 
                       value="tech">
                <label for="tech">Technology</label>
                <input type="checkbox" 
                       id="sports" 
                       name="interests" 
                       value="sports">
                <label for="sports">Sports</label>
                <input type="checkbox" 
                       id="music" 
                       name="interests" 
                       value="music">
                <label for="music">Music</label><br>

                <input type="submit" value="Register">
            </fieldset>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>Contact: gathimoses@gmail.com | Phone: +254718180048 </p>
    </footer>
</body>
</html>
