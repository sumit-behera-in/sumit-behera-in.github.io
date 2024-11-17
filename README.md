<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sumit Behera's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background: #333;
      color: #fff;
      padding: 1.5rem 0;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }
    header p {
      font-size: 1.2rem;
      margin: 0.5rem 0 0;
    }
    section {
      padding: 1.5rem 2rem;
      margin: 1rem auto;
      background: #fff;
      max-width: 800px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
    }
    h2 {
      color: #444;
      margin-bottom: 0.8rem;
    }
    a {
      color: #0066cc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .project-video {
      margin-top: 0.8rem;
      border: 1px solid #ddd;
      border-radius: 8px;
      overflow: hidden;
    }
    footer {
      text-align: center;
      padding: 1rem 0;
      background: #222;
      color: #fff;
      margin-top: 1.5rem;
    }
    ul {
      padding-left: 1.5rem;
    }
    .section-desc {
      margin-top: -0.5rem;
      color: #555;
    }
  </style>
</head>
<body>

<header>
  <h1>Sumit Behera's Portfolio</h1>
  <p><strong>Android Developer | Golang Developer | Problem Solver </strong></p>
</header>

<section>
  <h2>About Me</h2>
  <p>
    Hello! I’m <b>Sumit Behera</b>, a passionate software developer with a focus on building efficient and innovative solutions. 
    With a strong foundation in <b>programming</b> and <b>problem-solving</b>, I specialize in developing real-world projects 
    that bridge complex systems with simple, user-friendly interfaces.  
  </p>
  <p>
    My journey into the tech world has been driven by curiosity, determination, and a love for creating. From writing
    my first "Hello World" program to developing advanced CLI tools and Android apps, every project has been a stepping stone toward achieving excellence.
  </p>
</section>

<section>
  <h2>Contact Information</h2>
  <p class="section-desc">Feel free to reach out or connect with me!</p>
  <ul>
    <li><strong>Email:</strong> <a href="mailto:sumit.behera@outlook.in"><strong>sumit.behera@outlook.in</strong></a></li>
    <li><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/sumit-behera" target="_blank"><strong>linkedin.com/in/sumit-behera</strong></a></li>
    <li><strong>GitHub:</strong> <a href="https://github.com/sumit-behera-in" target="_blank"><strong>github.com/sumit-behera-in</strong></a></li>
    <li><strong>LeetCode:</strong> <a href="https://leetcode.com/u/sumitbehera" target="_blank"><strong>leetcode.com/u/sumitbehera</strong></a></li>
  </ul>
</section>

<section>
  <h2>Projects</h2>
  <p class="section-desc"><strong>A showcase of my most impactful projects:</strong></p>
  
  <h3>Go Storage Handler</h3>
  <p>
    Developed a powerful <b>CLI tool</b> for seamless integration between <b>PostgreSQL</b> and <b>MongoDB</b>. This project allows for 
    efficient binary data <b>storage</b>, <b>retrieval</b>, and <b>migration</b>, with support for distributed environments. It includes 
    robust <b>logging</b>, <b>error handling</b>, and customizable settings for advanced data operations.
    <br>
    <strong>Tech Stack:</strong> **Go, PostgreSQL, MongoDB**
    <br>
    <a href="https://github.com/sumit-behera-in/go-storage-handler" target="_blank"><strong>View Project on GitHub</strong></a>
  </p>
  <div class="project-video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_LINK" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>

  <h3>Hand Sign Detection</h3>
  <p>
    Created a <b>machine learning-based system</b> for recognizing hand gestures in real-time using <b>OpenCV</b> and <b>MediaPipe</b>. 
    The model achieved an impressive <b>99.86% accuracy</b> in identifying the English alphabet gestures. This project aims 
    to bridge communication gaps for the <b>deaf</b> and <b>mute</b> communities.
    <br>
    <strong>Tech Stack:</strong> **Python, OpenCV, MediaPipe, RandomForest Algorithm**
    <br>
    <a href="https://github.com/sumit-behera-in/Hand_Sign_detection" target="_blank"><strong>View Project on GitHub</strong></a>
  </p>
  <div class="project-video">
    <iframe width="560" height="315" src="https://github.com/sumitbehera1508/Hand_Sign_detection/assets/100491275/7200aa61-7053-473e-81e0-018bbd8be77a" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>

  <h3>News App</h3>
  <p>
    Built a feature-rich <b>Android application</b> that fetches news articles from multiple sources using <b>News API</b> and provides <b>offline access</b> with <b>RealmDB</b>. The app emphasizes <b>modularity</b> and <b>testability</b> with a clean MVVM architecture.
    <br>
    <strong>Tech Stack:</strong> **Kotlin, Jetpack Compose, RealmDB, Retrofit**
    <br>
    <a href="https://github.com/sumit-behera-in/MVVM-News-App" target="_blank"><strong>View Project on GitHub</strong></a>
  </p>
  <div class="project-video">
    <iframe width="560" height="315" src="https://github.com/sumitbehera1508/MVVM-News-App/assets/100491275/cf704d2d-18ab-4f84-bbc1-a56984629b91" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>
</section>

<section>
  <h2>Technical Skills</h2>
  <ul>
    <li><strong>Languages:</strong> **C++, Python, Kotlin, Go**</li>
    <li><strong>Frameworks:</strong> **Jetpack Compose, Firebase, Retrofit, Dagger-Hilt**</li>
    <li><strong>Tools:</strong> **Android Studio, Jupyter Notebook, Git**</li>
    <li><strong>Databases:</strong> **PostgreSQL, MongoDB, RealmDB**</li>
  </ul>
</section>

<section>
  <h2>Achievements</h2>
  <ul>
    <li>Qualified <b>GATE (DA) 2024</b> with rank <b>1588</b>.</li>
    <li>Secured rank <b>4</b> in <b>OJEE MCA 2022</b>.</li>
    <li>Solved <b>850+ problems</b> on <b>LeetCode</b>, showcasing advanced problem-solving skills.</li>
  </ul>
</section>

<section>
  <h2>Future Goals</h2>
  <p>
    I aim to expand my expertise in <b>software development</b>, focusing on <b>cloud-based solutions</b>, <b>distributed systems</b>, 
    and <b>machine learning</b>. My long-term goal is to contribute to impactful <b>open-source projects</b> and lead a team of 
    innovative developers to create technology that transforms lives.
  </p>
</section>

<footer>
  <p>&copy; 2024 <b>Sumit Behera</b> | Built with passion and dedication</p>
</footer>

</body>
</html>
