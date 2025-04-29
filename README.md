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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>HTML5 Practice Page</title>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>HTML5 Practice Page</h1>
  </header>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Ordered List - Roman Numerals</h2>
    <ol type="I">
      <li>Introduction to HTML</li>
      <li>HTML Elements</li>
      <li>Forms and Validation</li>
      <li>Multimedia in HTML</li>
      <li>Conclusion</li>
    </ol>
  </section>

  <!-- External Image from Pexels -->
  <section>
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg" 
         alt="Nature from Pexels" 
         width="500">
  </section>

  <!-- Table of Contacts -->
  <section>
    <h2>Contact Table</h2>
    <table border="1" cellpadding="8">
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
          <td>John Doe</td>
          <td>123 Main St</td>
          <td>+260978000001</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Mary Jane</td>
          <td>456 Park Ave</td>
          <td>+260978000002</td>
          <td>mary@example.com</td>
        </tr>
        <tr>
          <td>Peter Parker</td>
          <td>789 Broadway</td>
          <td>+260978000003</td>
          <td>peter@example.com</td>
        </tr>
        <tr>
          <td>Lucy Liu</td>
          <td>321 Sunset Blvd</td>
          <td>+260978000004</td>
          <td>lucy@example.com</td>
        </tr>
        <tr>
          <td>Bruce Wayne</td>
          <td>100 Wayne Manor</td>
          <td>+260978000005</td>
          <td>bruce@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form action="#" method="post">
      <!-- Name -->
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

      <!-- Email -->
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

      <!-- Password -->
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Create a password" required><br><br>

      <!-- Date of Birth -->
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required><br><br>

      <!-- Dropdown -->
      <label for="country">Country:</label>
      <select id="country" name="country" required>
        <option value="">Select your country</option>
        <option value="zambia">Zambia</option>
        <option value="kenya">Kenya</option>
        <option value="nigeria">Nigeria</option>
        <option value="ghana">Ghana</option>
      </select><br><br>

      <!-- Radio Buttons -->
      <p>Gender:</p>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label><br>
      <input type="radio" id="female" name="gender" value="female">
      <label for="female">Female</label><br><br>

      <!-- Checkboxes -->
      <p>Choose your interests:</p>
      <input type="checkbox" id="tech" name="interest" value="Technology">
      <label for="tech">Technology</label><br>
      <input type="checkbox" id="music" name="interest" value="Music">
      <label for="music">Music</label><br>
      <input type="checkbox" id="sports" name="interest" value="Sports">
      <label for="sports">Sports</label><br><br>

      <!-- Submit Button -->
      <button type="submit">Register</button>
    </form>
  </section>

  <!-- Multimedia Elements -->
  <section>
    <h2>Multimedia</h2>

    <!-- Audio -->
    <h3>Audio Sample</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <!-- Video -->
    <h3>Video Sample</h3>
    <video width="500" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 HTML5 Practice Page</p>
  </footer>

</body>
</html>

