<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NASSUR HUSSEIN IDRIS</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon">
  <link rel="stylesheet" href="style3.css">
</head>

<body>
  <header>
    <nav>
      <a href="#home" class="nav-button home-button">Home</a>
      <a href="#about" class="nav-button about-button">About</a>
      <a href="#resume" class="nav-button resume-button">Resume/Cv</a>
      <a href="#portfolio" class="nav-button portfolio-button">Portfolio</a>
      <a href="#contact" class="nav-button contact-button">Contact</a>
    </nav>
    <div id="darkModeContainer">
      <button id="darkModeToggle" class="button">Dark Mode</button>
    </div>
  </header>

  <main>
    <section id="home">
      <h1>"Hi There!" 👋<br>Welcome to My Website</h1>
      <p>I'M NASSUR HUSSEIN IDRIS An Enthusiastic and results-driven Full Stack Developer with a solid two-year track record in web development. Proficient in both front-end and back-end technologies, I bring a unique blend of technical expertise and creative problem-solving to every project. My commitment to delivering high-quality, scalable solutions is matched by my ability to collaborate effectively with cross-functional teams.</p>

      <p><strong>Technical Skills::</strong></p><hr>
      <ul>
        <li> Front-end Development: HTML, CSS, JavaScript, React.js</li>
        <li>Back-end Development: Node.js, Express.js</li>
        <li>Database: MongoDB, MySQL</li>
        <li>Additional Skills: RESTful API design, Responsive Web Design, Agile/Scrum methodologies</li>
      </ul>
      <p>
        <strong>Professional Experience:</strong></p><hr>

      <p>In my previous role at IME INC, I played a pivotal role in developing and maintaining cutting-edge web applications. I specialize in translating complex requirements into seamless user experiences, ensuring the efficient functioning of applications from conception to deployment. My hands-on experience with frameworks such as React.js and Node.js has equipped me to tackle challenges and deliver robust solutions.</p>

      <p><strong>Key Achievements:</strong></p><hr>

      <p>Successfully delivered number projects on time, meeting or exceeding client expectations.
        Implemented responsive design techniques, improving user experience and increasing mobile accessibility.
        Collaborated with cross-functional teams to troubleshoot and resolve complex technical issues.</p>
      <a href="#" class="button">View Portfolio</a>
    </section>

    <section id="about">
      <h2>About Me</h2>
      <p>Embark on an Enriching Digital Odyssey with Your Multifaceted Guide</p>

      <p><strong>🚀 Welcome to a Pantheon of Digital Excellence</strong></p>

      <p>Immerse yourself in a realm where possibilities know no bounds—where creativity intertwines seamlessly with technical prowess. I am your full-stack developer and graphic designer, dedicated to breathing life into your visions. Whether you're navigating the digital landscape or embarking on a quest for profound learning with an insightful Quran tutor, I am your dedicated companion on this transformative journey.</p>

      <p><strong>🌐 Linguistic Tapestry: Crafting Connections Across Borders</strong></p>

      <p>Witness the magic of a linguistic tapestry woven with threads of English, Arabic, Swahili, and Luo. This multilingual advantage isn't just about communication; it's about crafting experiences that resonate globally, embracing the richness of diverse cultures.</p>

      <p><strong>📚 Educator Extraordinaire: Cultivating Minds and Guiding Explorers</strong></p>

      <p>Venturing beyond the digital horizon, I wear the mantle of an Islamic studies and Quran tutor. With over two years of expertise in Quran tutoring and a year in Islamic studies, I am not merely a freelancer but a compass guiding you through the vast sea of knowledge.</p>

      <p><strong>🎨 Creative Maestro: Artistry in Technology and Design</strong></p>

      <p>Embark on a journey through my freelancing kaleidoscope, where roles morph from crafting compelling content to conjuring visually mesmerizing graphics. Social media presence? I curate it. Administrative wizardry? I'm your virtual assistant. Data entry, transcription, translation—I navigate these realms with finesse, turning tasks into creative endeavors.</p>
      <p><strong>💎 Why Entrust Me?</strong></p>

      <p>Quality Beyond the Expected: Beyond mere completion, I am committed to perfection. Meticulous attention to detail ensures your projects emerge as refined masterpieces.</p>

      <p>Global Insight: My multilingual prowess extends beyond language; it broadens the vistas of what we can create together, transcending cultural boundaries.</p>

      <p><strong>🌟 Client-Centric Collaboration: Allies in Triumph</strong></p>

      <p>Your satisfaction is not a goal; it's my guiding star. I don't just meet expectations; I exceed them. Our collaboration is not transactional; it's a partnership in the pursuit of success, fueled by transparent communication.</p>

      <p><strong>🚀 Let's Ascend Together</strong></p>

      <p>Whether you're in pursuit of a tech virtuoso or a guide through the corridors of insightful Quranic knowledge, our collaborative journey awaits. Together, let's transform your ideas into digital masterpieces and your learning aspirations into triumphant achievements. Join me, and together, we'll elevate your online experience to new heights! 💼✨
      </p>
    </section>

    <section id="resume">
      <h2>Resume/CV</h2>
      <p>Explore my professional journey through my detailed resume. Feel free to download and share!</p>

      <!-- Link to PDF file -->
      <a href="/F:/NASSUR-HUSSEIN-IDRIS/Professional%20CV%20Resume.pdf" target="_blank" class="button resume-link">View Resume</a>

      <!-- Download button for the PDF file -->
      <a href="/F:/NASSUR-HUSSEIN-IDRIS/Professional%20CV%20Resume.pdf" download="Nassur_Hussein_Idris_Resume.pdf"
        class="button resume-download">Download Resume</a>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <ul>
        <li>
          <h3>Project 1</h3>
          <p>IME INC<br>Community APP</p>
          <a href="https://github.com/Islam-Made-Easy/ime-api" class="button project-link">View Project</a>
        </li>
        <li>
          <h3>Project 2</h3>
          <p>Main contributor @IME INC</p>
          <a href="https://github.com/HusseinIdrisNassur/ime-api" class="button project-link">View Project</a>
        </li>
        <li>
          <h3>Project 3</h3>
          <p>My Website Projects</p>
          <a href="https://husseinidrisnassur.github.io/NASSUR-HUSSEIN-IDRIS/" class="button project-link">View Project</a>
        </li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <form action="/submit_form" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>
        <button type="submit" class="button">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 NASSUR HUSSEIN IDRIS</p>
  </footer>

  <script src="script.js"></script>
  <script>
    // Smooth scrolling for anchor links
    document.querySelectorAll('.nav-button').forEach(button => {
      button.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });

    // Dark mode/light mode switch logic
    const darkModeToggle = document.getElementById('darkModeToggle');
    const body = document.body;

    darkModeToggle.addEventListener('click', () => {
      body.classList.toggle('dark-mode');
      updateDarkModeButtonText();
    });

    // Function to update dark mode button text
    function updateDarkModeButtonText() {
      const darkModeButtonText = body.classList.contains('dark-mode') ? 'Light Mode' : 'Dark Mode';
      darkModeToggle.textContent = darkModeButtonText;
    }
  </script>
</body>

</html>
