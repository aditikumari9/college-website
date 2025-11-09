<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DIT University - Cloud Computing Project</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f7fb;
      color: #333;
    }
    header {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 20px;
      position: relative;
    }
    header img {
      position: absolute;
      left: 30px;
      top: 10px;
      height: 80px;
    }
    nav {
      background: #004d99;
      text-align: center;
      padding: 12px;
    }
    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 25px;
    }
    h2 {
      color: #003366;
      border-bottom: 2px solid #003366;
      padding-bottom: 5px;
    }
    .banner {
      width: 100%;
      height: 300px;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/1/17/DIT_University_campus.jpg');
      background-size: cover;
      background-position: center;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    table, th, td {
      border: 1px solid #bbb;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 20px;
    }
    .social a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }
    .form-box {
      background-color: #eef4fc;
      padding: 15px;
      border-radius: 8px;
      margin-top: 15px;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin: 5px 0;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #004d99;
      color: white;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      border-radius: 4px;
    }
    button:hover {
      background-color: #002b5c;
    }
  </style>
</head>
<body>

<header>
  <img src="https://upload.wikimedia.org/wikipedia/en/f/fb/DIT_University_logo.png" alt="DIT Logo">
  <h1>DIT University, Dehradun</h1>
  <p><i>Imagine | Innovate | Inspire</i></p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About Us</a>
  <a href="#departments">Departments</a>
  <a href="#admissions">Admissions</a>
  <a href="#contact">Contact</a>
</nav>

<div class="banner"></div>

<section id="home">
  <h2>Welcome to DIT University</h2>
  <p>DIT University is one of the most prestigious institutions in North India, known for its commitment to academic excellence, innovation, and research. Established in 1998, the university offers diverse programs in Engineering, Computer Applications, Management, Architecture, Pharmacy, and more.</p>
</section>

<section id="about">
  <h2>About Us</h2>
  <p><b>History:</b> DIT University (formerly Dehradun Institute of Technology) was established in 1998 and has since evolved into a center of excellence in education, research, and innovation. The campus is spread over 21 acres amidst the scenic foothills of Mussoorie, providing an inspiring learning environment.</p>
  
  <p><b>Vision:</b> To be a world-class university recognized for teaching excellence, innovation, and sustainable development.</p>
  <p><b>Mission:</b> To empower students through education, research, and skills that enable them to be future-ready professionals and responsible citizens.</p>

  <p><b>Principal’s Message:</b> “At DIT University, we believe that knowledge is the foundation of progress. Our goal is to provide an education that not only informs but transforms — shaping minds to lead and innovate.”</p>

  <p><b>Campus Highlights:</b></p>
  <ul>
    <li>21-acre lush green campus with advanced digital infrastructure</li>
    <li>State-of-the-art laboratories and research centers</li>
    <li>Wi-Fi enabled campus with digital classrooms</li>
    <li>Student clubs, innovation cell, and entrepreneurship programs</li>
    <li>Scholarship and Financial Aid programs for meritorious students</li>
    <li>Dedicated Sports Complex and Fitness Facilities</li>
  </ul>

  <h3>🏅 Scholarships & Sports Encouragement</h3>
  <p><b>Scholarships:</b> DIT University offers several merit-based scholarships for outstanding academic performers, economically weaker sections, and wards of defense personnel.</p>
  <ul>
    <li>100% tuition fee waiver for top rankers (based on 10+2 or entrance exam)</li>
    <li>Up to 50% scholarship for students scoring 85% or above</li>
    <li>Special scholarships for female students to encourage participation in STEM</li>
  </ul>

  <p><b>Sports Encouragement:</b> The university promotes sportsmanship through:</p>
  <ul>
    <li>Annual Sports Fest “Aarohan”</li>
    <li>Cricket, Football, Volleyball, Badminton, Athletics, and Gym facilities</li>
    <li>Special rewards and attendance benefits for students participating in inter-college tournaments</li>
  </ul>
</section>

<section id="departments">
  <h2>Departments and Courses</h2>
  <p>DIT University offers undergraduate, postgraduate, and doctoral programs across various disciplines.</p>
  
  <h3>🎓 School of Computing</h3>
  <ul>
    <li><b>BCA (Bachelor of Computer Applications)</b> – Focus on software development, database management, and cloud computing.</li>
    <li><b>B.Tech CSE</b> – Core computer science subjects with electives in AI, Data Science, and Cybersecurity.</li>
    <li><b>MCA</b> – Advanced programming, machine learning, and data analytics specialization.</li>
  </ul>

  <h3>🏗️ School of Engineering</h3>
  <ul>
    <li>B.Tech in Civil, Electrical, Mechanical, and Electronics Engineering</li>
    <li>Integrated programs in Robotics, IoT, and Renewable Energy</li>
  </ul>

  <h3>📊 School of Management</h3>
  <ul>
    <li>BBA and MBA programs with specializations in HR, Marketing, Finance, and International Business</li>
  </ul>

  <h3>🏛️ Faculty Details</h3>
  <table>
    <tr>
      <th>Name</th>
      <th>Designation</th>
      <th>Department / Subject</th>
    </tr>
    <tr>
      <td>Dr. Shashank Singh</td>
      <td>Associate Professor</td>
      <td>Cloud Computing</td>
    </tr>
    <tr>
      <td>Dr. Kanu Priya Goyal</td>
      <td>Professor</td>
      <td>Data Analytics and Python Programming</td>
    </tr>
    <tr>
      <td>Ms. Ritu Verma</td>
      <td>Assistant Professor</td>
      <td>Artificial Intelligence</td>
    </tr>
    <tr>
      <td>Mr. Rajesh Sharma</td>
      <td>Assistant Professor</td>
      <td>Business Management</td>
    </tr>
  </table>
</section>

<section id="admissions">
  <h2>Admissions 2025</h2>
  <p><b>Admission Process:</b></p>
  <ol>
    <li>Visit the official website: <a href="https://www.dituniversity.edu.in" target="_blank">www.dituniversity.edu.in</a></li>
    <li>Fill out the online application form</li>
    <li>Appear for the entrance test or merit-based counseling</li>
    <li>Document verification and fee submission</li>
  </ol>

  <p><b>Eligibility Criteria:</b></p>
  <ul>
    <li>UG Courses: 10+2 with minimum 60% marks</li>
    <li>PG Courses: Bachelor's Degree in relevant stream</li>
  </ul>

  <p><b>Important Dates:</b></p>
  <ul>
    <li>Application Opens: March 2025</li>
    <li>Last Date to Apply: June 2025</li>
    <li>Classes Commence: August 2025</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p><b>Address:</b> DIT University, Mussoorie Diversion Road, Dehradun, Uttarakhand – 248009</p>
  <p><b>Phone:</b> +91-135-300-1234 | <b>Email:</b> info@dituniversity.edu.in</p>
  <p><b>Office Hours:</b> Monday to Saturday – 9:00 AM to 5:00 PM</p>

  <div class="form-box">
    <h3>📩 Enquiry Form</h3>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="4" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </div>

  <p><b>Follow Us:</b></p>
  <div class="social">
    <a href="https://www.facebook.com/dituniversity" target="_blank">Facebook</a> |
    <a href="https://www.instagram.com/dituniversity" target="_blank">Instagram</a> |
    <a href="https://www.linkedin.com/school/dit-university/" target="_blank">LinkedIn</a>
  </div>

  <br>
  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3443.7941816607896!2d78.07016887509018!3d30.379973606169886!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390929f4b1428e2d%3A0xabc742b1a0588150!2sDIT%20University!5e0!3m2!1sen!2sin!4v1709913770100!5m2!1sen!2sin"
    width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
</section>

<footer>
  <p>© 2025 DIT University | Cloud Computing Project by Aditi Kumari</p>
</footer>

</body>
</html>

