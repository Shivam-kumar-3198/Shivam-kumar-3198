<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Shivam Kumar’s Cosmic Code Universe</title>
  <style>
    /* Dynamic Gradient Background */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      color: #ffffff;
      background: linear-gradient(45deg, #2b5876, #4e4376);
      background-size: 400% 400%;
      animation: gradientAnimation 15s ease infinite;
    }
    @keyframes gradientAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    /* Container Styling */
    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 40px;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }
    
    /* Typography & Animations */
    h1, h2, h3 {
      text-align: center;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin-bottom: 20px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    h1 {
      font-size: 2.5em;
      animation: fadeInDown 1.5s;
    }
    h2 {
      font-size: 2em;
      margin-top: 40px;
      border-bottom: 2px solid #fff;
      padding-bottom: 10px;
      animation: fadeIn 2s;
    }
    h3 {
      font-size: 1.8em;
      margin-top: 30px;
      cursor: pointer;
      transition: color 0.3s;
    }
    h3:hover {
      color: #ffd700;
    }
    p, ul {
      font-size: 1.1em;
      line-height: 1.6em;
      animation: fadeInUp 1.5s;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      margin: 10px 0;
      padding-left: 20px;
      position: relative;
    }
    ul li:before {
      content: "⭐";
      position: absolute;
      left: 0;
    }
    code {
      background: #333;
      padding: 3px 6px;
      border-radius: 5px;
      font-family: monospace;
    }
    /* Keyframes for Text Animations */
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-50px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    
    /* Hover Scale Effect */
    .hover-effect:hover {
      transform: scale(1.05);
      transition: transform 0.3s;
    }
    
    /* Dynamic Typing Effect */
    .typing {
      border-right: .15em solid #ffd700;
      white-space: nowrap;
      overflow: hidden;
      font-size: 1.5em;
      width: 0;
      animation: typingEffect 3s steps(30, end) forwards, blinkCursor 0.75s step-end infinite;
      margin: 0 auto 30px;
      text-align: center;
    }
    @keyframes typingEffect {
      from { width: 0; }
      to { width: 100%; }
    }
    @keyframes blinkCursor {
      from, to { border-color: transparent; }
      50% { border-color: #ffd700; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Shivam Kumar’s Cosmic Code Universe 🚀</h1>
    <div class="typing" id="dynamicText">Welcome to the universe of code!</div>
    <p>
      I’m Shivam Kumar, an explorer in the vast digital cosmos. My projects are dynamic constellations of innovation, creativity, and cutting-edge technology.
    </p>
    
    <h2>My Star Repositories</h2>
    
    <h3 class="hover-effect">🌟 Html_CSS_Javascript</h3>
    <p>
      Navigate the web galaxy with projects blending classic HTML, CSS, and JavaScript magic into engaging, beginner-friendly experiences.
    </p>
    
    <h3 class="hover-effect">🚀 React</h3>
    <p>
      Dive into modern web development with dynamic React projects harnessing powerful components, intuitive state management, and interstellar API integrations.
    </p>
    
    <h3 class="hover-effect">📸 Photo_Editor_Project</h3>
    <p>
      Unleash your creativity! Experiment with essential photo editing features—crop, filter, and sprinkle a little stardust on your images.
    </p>
    
    <h3 class="hover-effect">🌐 Webdev_for_Gdsc</h3>
    <p>
      Embark on a web development odyssey, where sleek landing pages and interactive portals bring your digital visions to life.
    </p>
    
    <h3 class="hover-effect">🎩 OH.STUDIO_webpage</h3>
    <p>
      Enter a realm where creativity meets pixels. Here, HTML spells, CSS enchantments, and JavaScript wizardry converge in an enigmatic display.
    </p>
    
    <h3 class="hover-effect">🤖 workingWithC++</h3>
    <p>
      Venture into the C++ cosmos—where algorithms solve real-world puzzles and code transcends boundaries.
    </p>
    
    <h3 class="hover-effect">📚 JavaProgram</h3>
    <p>
      Explore beginner-level Java projects that shine like shooting stars, illuminating the path to deeper learning.
    </p>
    
    <h3 class="hover-effect">🌌 legal_matrix_by_Shivam</h3>
    <p>
      Reimagine the legal framework with innovative tweaks. Legal wizards, assemble!
    </p>
    
    <h3 class="hover-effect">🎮 Calculator_Project_Js</h3>
    <p>
      Crunch numbers with a JavaScript-powered calculator—an alchemical blend of logic and creativity that makes math fun.
    </p>
    
    <h2>New Horizons & Achievements</h2>
    <ul>
      <li>
        <strong>Full-Stack Mastery:</strong> Expanded my toolkit with Node.js, Express, and MongoDB to build robust, scalable back-end architectures.
      </li>
      <li>
        <strong>Cloud Navigator:</strong> Leveraged AWS and Docker to deploy secure, scalable cloud solutions powering modern applications.
      </li>
      <li>
        <strong>AI & Machine Learning Explorer:</strong> Dived into Python’s AI ecosystem with TensorFlow and scikit-learn, unlocking new dimensions of data-driven insights.
      </li>
      <li>
        <strong>Hackathon Hero:</strong> Proud recipient of top honors at XYZ Hackathon, recognized for innovative problem-solving and dynamic teamwork.
      </li>
    </ul>
    
    <h2>Unique Functions & Innovations</h2>
    <p>
      Beyond conventional coding, I experiment with unique functions like <code>quantumLeap()</code> and <code>cosmicSync()</code>. These tailor-made routines integrate complex operations with intuitive simplicity, opening new frontiers in code.
    </p>
    
    <h2>Let’s Connect!</h2>
    <p>
      Whether you’re ready to embark on a collaborative project or simply chat about the digital cosmos, I’m always up for a code conversation. Connect with me and let’s build something extraordinary!
    </p>
  </div>
  
  <script>
    // Dynamic Typing Text Update
    const dynamicText = document.getElementById('dynamicText');
    const texts = [
      "Welcome to the universe of code!",
      "Exploring galaxies of innovation!",
      "Coding is my superpower!",
      "Join me on this cosmic journey!"
    ];
    let currentTextIndex = 0;
    
    setInterval(() => {
      currentTextIndex = (currentTextIndex + 1) % texts.length;
      dynamicText.textContent = texts[currentTextIndex];
      // Restart the typing animation
      dynamicText.style.animation = 'none';
      void dynamicText.offsetWidth;
      dynamicText.style.animation = '';
    }, 5000);
  </script>
</body>
</html>
