<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML5 Multimedia & Forms Demo</title>
  </head>
  <body>
    <!-- Header Section -->
    <header>
      <h1>Welcome to My HTML5 Demo</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section id="list">
      <h2>Ordered List (Roman Numerals)</h2>
      <ol type="I">
        <li>Car</li>
        <li>Apartment</li>
        <li>Land</li>
        <li>Real Estate</li>
      </ol>
    </section>

    <!-- External Image from Pexels -->
    <section id="image">
      <h2>External Image</h2>
      <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="Beautiful Landscape" width="600" />
    </section>

    <!-- Table of 5 Contacts -->
    <section id="contacts">
      <h2>Contacts Table</h2>
      <table border="1" cellpadding="8" cellspacing="0">
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
            <td>John Kimani</td>
            <td>123 Main St, Kiambu</td>
            <td>+25474567890</td>
            <td>johnkimani90@gmail.com</td>
          </tr>
          <tr>
            <td>Jane Wanjiru</td>
            <td>456 Oak Ave, Syokimau</td>
            <td>+25476543210</td>
            <td>janewanjiru10@gmail.com</td>
          </tr>
          <tr>
            <td>Mike Brown</td>
            <td>789 Pine Rd, Kitisuru</td>
            <td>+25471234567</td>
            <td>mikebrown67@gmail.com</td>
          </tr>
          <tr>
            <td>Mwanaisha Juma</td>
            <td>321 Likoni Ln, Mombasa</td>
            <td>+25479876543</td>
            <td>mwanaishajuma43@gmail.com</td>
          </tr>
          <tr>
            <td>Robert Otieno</td>
            <td>654 Spruce St, Kisumu</td>
            <td>+25472221111</td>
            <td>robertotieno11@gmail.com</td>
          </tr>
        </tbody>
      </table>
    </section>

    <!-- Registration Form with Various Input Types -->
    <section id="registration">
      <h2>Registration Form</h2>
      <form action="/submit_registration" method="post">
        <!-- Name Field -->
        <div>
          <label for="regName">Name:</label>
          <input type="text" id="regName" name="regName" placeholder="Enter name"                  required />
        </div>
        <br>

        <!-- Email Field -->
        <div>
          <label for="regEmail">Email:</label>
          <input type="email" id="regEmail" name="regEmail" placeholder="Enter Email"              required />
        </div>
        <br>

        <!-- Password Field -->
        <div>
          <label for="regPassword">Password:</label>
          <input type="password" id="regPassword" name="regPassword" placeholder="Enter Password" required minlength="6" />
        </div>
        <br>

        <!-- Date Field -->
        <div>
          <label for="regDate">Date of Birth:</label>
          <input type="date" id="regDate" name="regDate" required />
        </div>
        <br>

        <!-- Dropdown for Gender -->
        <div>
          <label for="regGender">Gender:</label>
          <select id="regGender" name="regGender" required>
            <option value="">Select Gender</option>
            <option value="female">Female</option>
            <option value="male">Male</option>
            <option value="other">Other</option>
          </select>
        </div>
        <br>

        <!-- Radio Buttons for Subscription Options -->
        <div>
          <p>Subscribe to Newsletter:</p>
          <label>
            <input type="radio" name="subscribe" value="yes" required /> Yes
          </label>
          <label>
            <input type="radio" name="subscribe" value="no" /> No
          </label>
        </div>
        <br>

        <!-- Checkboxes for Interests -->
        <div>
          <p>Select your interests:</p>
          <label>
            <input type="checkbox" name="interests" value="technology" /> Technology
          </label>
          <label>
            <input type="checkbox" name="interests" value="music" /> Music
          </label>
          <label>
            <input type="checkbox" name="interests" value="sports" /> Sports
          </label>
        </div>
        <br>

        <button type="submit">Register</button>
      </form>
    </section>

    <!-- Multimedia Elements: Audio and Video -->
    <section id="media">
      <h2>Multimedia Elements</h2>
      <!-- Audio Element -->
      <div>
        <h3>Audio Example</h3>
        <audio controls>
          <source src="audio-file.mp3" type="audio/mpeg" />
          Your browser does not support the audio element.
        </audio>
      </div>
      <br>
      <!-- Video Element -->
      <div>
        <h3>Video Example</h3>
        <video width="640" height="360" controls>
          <source src="video-file.mp4" type="video/mp4" />
          Your browser does not support the video element.
        </video>
      </div>
    </section>

    <!-- Footer Section -->
    <footer>
      <p>&copy; 2025 KOYO SAMUEL. All rights reserved.</p>
    </footer>
  </body>
</html>
