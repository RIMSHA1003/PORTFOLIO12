<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rimsha - Web Developer Portfolio</title>
</head>
<body bgcolor="#eef4f8" id="top">

  <!-- ===== HEADER ===== -->
  <table width="100%" bgcolor="#d9e8f5" cellpadding="20">
    <tr>
      <td align="center">
        <h3>WEB DEVELOPMENT</h3>
        <h1>RIMSHA</h1>
        <p>Computer Science graduate focused on front-end web development with <b>HTML, CSS and JavaScript</b>. Academic experience building rental marketplace and office management interfaces with <b>PHP and MySQL</b>. Seeking an entry-level front-end role or full-time internship.</p>
        <p><b>Dummy Contact:</b> +92 300 1234567 | rimsha.demo@gmail.com | Lahore, Pakistan</p>
      </td>
    </tr>
  </table>

  <!-- ===== NAV - ANCHOR TAG ===== -->
  <p align="center" bgcolor="#0f2a44">
    <a href="#about">About</a> |
    <a href="#skills">Skills</a> |
    <a href="#projects">Projects</a> |
    <a href="#education">Education</a> |
    <a href="#contact">Contact</a> |
    <a href="https://www.google.com" target="_blank">Google</a>
  </p>

  <!-- ===== MARQUEE ===== -->
  <marquee behavior="alternate" bgcolor="#0f2a44">
    <font color="white"><b>WELCOME TO RIMSHA'S PORTFOLIO</b> | <i>Front-End Developer</i> | <mark>Available for Internship</mark></font>
  </marquee>

  <!-- ===== MAIN LAYOUT - TABLE ===== -->
  <table width="100%" border="0" cellpadding="20" cellspacing="0">
    <tr>
      <!-- LEFT SIDE -->
      <td width="30%" bgcolor="#d9e8f5" valign="top">

        <!-- CONTACT - DUMMY ONLY -->
        <h2>CONTACT</h2>
        <p><b>Phone:</b> +92 300 1234567 <i>(Dummy Number)</i></p>
        <p><b>Email:</b> rimsha.demo@gmail.com</p>
        <p><b>Location:</b> Lahore, Pakistan</p>
        <p><a href="https://www.google.com" target="_blank">My Google Profile</a></p>

        <!-- SKILLS - UNORDERED LIST -->
        <h2 id="skills">SKILLS</h2>
        <ul>
          <li>Web Design</li>
          <li>Design Thinking</li>
          <li>Wireframe Creation</li>
          <li>Front End Coding</li>
          <li>Problem-Solving</li>
          <li>Computer Literacy</li>
          <li>Project Management Tools</li>
          <li>Strong Communication</li>
        </ul>

        <!-- TECHNICAL SKILLS - DESCRIPTION LIST -->
        <h2>TECHNICAL SKILLS</h2>
        <dl>
          <dt><b>Front End</b></dt>
          <dd>HTML, CSS,JavaScript, Web Design & Development.</dd>
          <dt><b>Tools</b></dt>
          <dd>Visual Studio Code, NetBeans.</dd>
          <dt><b>Foundations</b></dt>
          <dd>Data Structures & Algorithms, Software Engineering, SDLC.</dd>
        </dl>

        <!-- ABOUT - FORMATTING -->
        <h2 id="about">ABOUT ME</h2>
        <p>Hello! I am <strong>Rimsha</strong>.</p>
        <p>I love <b>Web Development</b> and my dream is to become a <em>Full Stack Developer</em>.</p>
        <p><del>Old Goal: Just pass exam</del> <ins>New Goal: Become Best Developer</ins></p>

        <!-- IMAGE -->
        <h2>MY PHOTO</h2>
        <img src="123.jpg" width="180" alt="Rimsha Profile Photo">
        <p><i>Front-End Developer</i></p>

      </td>

      <!-- RIGHT SIDE -->
      <td width="70%" bgcolor="white" valign="top">

        <!-- PROJECTS - ORDERED LIST + UNORDERED LIST -->
        <h2 id="projects">PROJECTS</h2>

        <h3>1.Lahore House rental Project</h3>
        <p><b>MCS Final Project / 2024 </b></p>
        <p><b>HTML / CSS / JavaScript / PHP / MySQL</b></p>
        <ul>
          <li>Built the front-end of a rental marketplace connecting house owners and tenants.</li>
          <li>Implemented property listings, search and filtering, registration and one-click booking flows.</li>
          <li>Created Admin, Owner and User dashboards to manage users and property listings.</li>
        </ul>

        <h3>2. OFFICE MANAGEMENT SYSTEM</h3>
        <p><b>ADPCS Final Project / 2021</b></p>
        <p><b>HTML / CSS / JavaScript/ PHP / MySQL</b></p>
        <ul>
          <li>Developed web interfaces for an office management system that replaced paper records.</li>
          <li>Built Admin and Employee panels for departments, salaries, attendance, tasks and leave, supported by PHP and MySQL.</li>
        </ul>

        <h3>MY LEARNING STEPS - ORDERED LIST</h3>
        <ol>
          <li>Learn HTML</li>
          <li>Learn CSS</li>
          <li>Learn JavaScript</li>
          <li>Build Projects</li>
        </ol>

        <!-- EDUCATION - TABLE -->
        <h2 id="education">EDUCATION</h2>
        <table border="1" width="100%">
          <tr>
            <th>Year</th>
            <th>Degree</th>
            <th>Institute</th>
          </tr>
          <tr>
            <td>2022 - 2024</td>
            <td><b>MASTER OF COMPUTER SCIENCE</b></td>
            <td>Virtual University of Pakistan</td>
          </tr>
          <tr>
            <td>2019 - 2021</td>
            <td><b>ASSOCIATE DEGREE IN COMPUTER SCIENCE</b></td>
            <td>The Superior University</td>
          </tr>
        </table>

        <!-- CONTACT - FORM -->
        <h2 id="contact">CONTACT ME</h2>
        <p>Fill this form, I will reply soon! <i>(Dummy Form)</i></p>
        <form>
          <label>Full Name:</label><br>
          <input type="text" placeholder="Enter your name" required><br><br>

          <label>Email:</label><br>
          <input type="email" placeholder="example@gmail.com" required><br><br>

          <label>Phone:</label><br>
          <input type="number" placeholder="0300-1234567"><br><br>

          <label>Date of Birth:</label><br>
          <input type="date"><br><br>

          <p><b>Gender:</b></p>
          <input type="radio" name="gender"> Female
          <input type="radio" name="gender"> Male<br><br>

          <p><b>What do you need?</b></p>
          <input type="checkbox"> Website
          <input type="checkbox"> Design
          <input type="checkbox"> Help in HTML<br><br>

          <label>City:</label><br>
          <select>
            <option>-- Select City --</option>
            <option>Lahore</option>
            <option>Karachi</option>
            <option>Islamabad</option>
            <option>Multan</option>
          </select><br><br>

          <label>Your Message:</label><br>
          <textarea rows="4" placeholder="Write your message here..."></textarea><br><br>

          <label>Upload File:</label><br>
          <input type="file"><br><br>

          <label>Favourite Color:</label><br>
          <input type="color"><br><br>

          <input type="submit" value="Send Message">
          <input type="reset" value="Clear Form">
        </form>

      </td>
    </tr>
  </table>

  <!-- ===== FOOTER ===== -->
  <table width="100%" bgcolor="#0f2a44" cellpadding="15">
    <tr>
      <td align="center">
        <font color="white">
          <p>© 2026 Rimsha | Made with HTML Only | Front-End Developer</p>
          <p><a href="#top"><font color="white">Back to Top</font></a> | <a href="https://www.youtube.com" target="_blank"><font color="white">YouTube</font></a> | <a href="https://www.google.com" target="_blank"><font color="white">Google</font></a></p>
        </font>
      </td>
    </tr>
  </table>

</body>
</html>
