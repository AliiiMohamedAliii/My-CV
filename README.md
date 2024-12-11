<html lang="en">
<head>
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ali Mohamed - Data Scientist & Business Analyst</title>
  <style>
    /* General body setup */
    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(-45deg, #4B6A4B, #6A7B50, #6F4F32, #585858, #4C5C3B);
      background-size: 700% 700%;
      animation: gradient 15s ease infinite;
      color: #4F6F52; 
      margin: 0;
      padding: 0;
      text-align: center;
      overflow: hidden;
    }

    @keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}


    /* Intro section */
    #intro {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      opacity: 0;
      transform: translateY(-100px);
      animation: fadeInUp 2s forwards;
    }

    h1 {
      font-size: 60px;
      color: #FFFFFF; /* Updated font color */
      font-weight: bold;
      margin: 0;
      opacity: 0;
      animation: fadeIn 1.5s forwards 0.5s;
    }

    p {
      font-size: 24px;
      color: #FFFFFF; /* Updated font color */
      margin: 20px 0;
      opacity: 0;
      animation: fadeIn 2s forwards 1s;
    }

    /* Button Animation */
    .btn {
      font-size: 20px;
      padding: 15px 30px;
      background-color: #222;
      color: #ECE3CE; 
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: transform 0.3s ease, background-color 0.3s ease;
      text-decoration: none;
      display: inline-block;
      margin-top: 30px;
      opacity: 0;
      animation: fadeIn 2s forwards 1.5s;
    }

    .btn:hover {
      background-color: #444;
      transform: scale(1.1);
    }

    /* CV Section */
    #cv {
      background-color: #FFFFFF;
      padding: 40px;
      display: none; /* Hidden initially */
      opacity: 0;
      animation: slideDown 1s forwards; /* Slide down animation */
      transform: translateY(-50px);
      height: 80vh;
      overflow-y: auto;
    }

    /* CV Rectangles */
    .cv-section {
      background: #4B6A4B;
      padding: 20px;
      margin: 20px auto;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
      max-width: 800px;
      text-align: left;
    }

    .cv-section h2 {
      font-size: 32px;
      color: #FFFFFF; 
      margin: 0 0 10px 0;
    }

    .cv-section h3 {
      font-size: 24px;
      color: #FFFFFF;
      margin: 10px 0;
    }

    .cv-section p, .cv-section ul {
      font-size: 18px;
      color: #FFFFFF;
      margin: 10px 0;
    }

    .cv-section ul {
      padding-left: 20px;
    }

    .contact-link {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
      font-size: 18px;
      color: #FFFFFF;
      text-decoration: none;
      transition: transform 0.3s ease, color 0.3s ease;
    }

    .contact-link img {
      width: 24px;
      height: 24px;
      margin-right: 10px;
    }

    .contact-link:hover {
      transform: scale(1.1);
      color: #FFFFFF; /* Updated hover color */
    }

    /* Smooth scroll */
    html {
      scroll-behavior: smooth;
    }

    /* Keyframe animations */
    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }

    @keyframes slideDown {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .show {
      display: block !important;
      opacity: 1 !important;
      animation: fadeIn 1.5s forwards;
      transform: translateY(0);
    }

    .hide {
      display: none !important;
    }

    /* Path animation */
    path {
      stroke-dasharray: 500;
      stroke-dashoffset: 500;
      animation: draw 2s linear forwards;
      fill: none;
      stroke: #4F6F52;
      stroke-width: 3;
    }

    @keyframes draw {
      to {
        stroke-dashoffset: 0;
      }
    }
  </style>
</head>
<body>
  <!-- Intro Section -->
  <div id="intro">
    <h1>Ali Mohamed</h1>
    <p>Data Scientist & Business Analyst | Transforming Data into Actionable Insights | Driving Business Growth through Analytics and Innovation</p>
    <a href="javascript:void(0)" class="btn" id="viewCvBtn">Click here to view the CV</a>
  </div>

  <!-- CV Section -->
  <div id="cv" class="cv-content">
    <div class="cv-section">
      <h2>About Me</h2>
      <p>I am a passionate developer with experience in Data Science, Machine Learning, and Business Analytics. I enjoy solving complex problems using data and building intelligent systems to drive business success.</p>
    </div>

    <div class="cv-section">
      <h2>Skills</h2>
      <p>Python, R Programming, SQL, Power BI, Machine Learning, Problem Solving, Excel, Communication, English (advanced level), Creativity, Team Leading .</p>
    </div>

    <div class="cv-section">
      <h2>Projects</h2>

      <h3>MUSIC STREAMING PLATFORM DEVELOPMENT</h3>
      <p><strong>Personal Project – Cairo, EG</strong><br>February 2024</p>
      <p>Designed and developed a music streaming platform with a focus on user authentication, playlist management, and advanced music discovery. Created a robust database system to facilitate seamless user experience, personalized recommendations, and efficient data management. Integrated a comprehensive set of features for immersive music exploration, leveraging skills in SQL, data analysis, and database design (ERD, schema).</p>

      <h3>ANALYZING HEALTHCARE DATA</h3>
      <p><strong>Personal Project – Cairo, EG</strong><br>January 2024</p>
      <p>This project emphasized the importance of data in enhancing patient outcomes, optimizing costs, and improving service quality in healthcare. By visualizing these complex datasets, I was able to uncover critical insights that can drive smarter decision-making in healthcare, ultimately contributing to more effective resource allocation.</p>

      <h3>CHURN RATE ANALYSIS</h3>
      <p><strong>Personal Project – Cairo, EG</strong><br>October 2023</p>
      <p>In today's competitive business landscape, understanding customer churn is essential for sustainability and growth. Churn rate, the percentage of customers who stop using a product or service, directly impacts revenue and profitability. By leveraging Power BI, this project provides actionable insights into churn trends, high-risk segments, and root causes, enabling businesses to implement data-driven strategies for improved customer retention.</p>

      <h3>EGYPTIAN LEAGUE PERFORMANCE ANALYSIS</h3>
      <p><strong>Personal Project – Cairo, EG</strong><br>April 2023</p>
      <p>Developed a Power BI dashboard analyzing Egyptian League data (2000/2001–2023/2024), providing insights into team performance, defensive strength, win/loss ratios, and high-scoring matches. The project helped identify trends, assess the impact of draws, and deliver actionable insights for fans and team management, supporting data-driven decision-making.</p>

      <h3>SALES PREDICTION MODEL DEVELOPMENT</h3>
      <p><strong>Personal Project – Cairo, EG</strong><br>December 2022</p>
      <p>Developed a sales prediction model using Python, involving data preprocessing (handling missing values, encoding, outlier removal), and exploratory analysis of Sales Amount, Quantity, and Customer Age. Applied Linear Regression, Random Forest Regressor, and SVR for predictive modeling, evaluating performance with MAE, MSE, and R-squared. Created a Streamlit app for real-time sales predictions, deploying the model as sales_model.pkl.</p>
    </div>

    <div class="cv-section">
      <h2>Career Achievements</h2>
      <ul>
        <li>Data analysis using Excel and Power BI. (from planet of skills academy)</li>
        <li>Data science using Python and SQL. (from planet of skills academy)</li>
        <li>Completing AI workshop (from DotPy)</li>
        <li>Dealing with ChatGPT (from Data Camp)</li>
        <li>Data Science in Python (from Data Camp)</li>
        <li>Communicating data insights (fom Data Camp)</li>
        <li>Data analysis in SQL (from Data Camp)</li>
        <li>R Programming (from 365 Data Science)</li>
        <li>How to Think Like a Data Scientist to Become One (from 365 Data Science)</li>
        <li>CCNAv7: Introduction to networks (from Cisco)</li>
        <li>CCNAv7: Switching, Routing and Wireless Essentials (from Cisco)</li>
        <li>CCNAv7: Enterprise Networking, Security and Automation (from Cisco)</li>
      </ul>
    </div>
<div class="cv-section">
      <h2>Contact</h2>
      <a href="mailto:alimohamedali2033@gmail.com" class="contact-link">
        <img src="https://img.icons8.com/ios/50/ffffff/email.png" alt="Email">
        alimohamedali2033@gmail.com
      </a>
      <a href="https://www.linkedin.com/in/ali-mohamed-2820312b0/" class="contact-link">
        <img src="https://img.icons8.com/ios/50/ffffff/linkedin.png" alt="LinkedIn">
        LinkedIn Profile
      </a>
      <a href="https://www.instagram.com/aliiiimohamedd/" class="contact-link">
        <img src="https://img.icons8.com/ios/50/ffffff/instagram.png" alt="Instagram">
        Instagram Profile
      </a>
      <a href="https://github.com/AliiiMohamedAliii" class="contact-link">
        <img src="https://img.icons8.com/ios/50/ffffff/github.png" alt="GitHub">
        GitHub Profile
      </a>
    </div>
  </div>

  <script>
    const viewCvBtn = document.getElementById('viewCvBtn');
    const cvSection = document.getElementById('cv');

    viewCvBtn.addEventListener('click', function() {
      document.getElementById('intro').classList.add('hide');
      cvSection.classList.add('show');
    });
  </script>
</body>
</html>
