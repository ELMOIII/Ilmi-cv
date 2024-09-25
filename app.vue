<template>
  <div class="cv-container">
    <div class="cv">
      <div class="header">
        <div class="profile">
          <img src="assets/img/ilmi.jpg" alt="Profile Photo" class="profile-photo" />
        </div>
        <div class="info">
          <h1>CV Ilmi Ananda Putri Yuliani</h1>
          <p>Email: <a href="mailto:ilmii2508@gmail.com">ilmii2508@gmail.com</a></p>
          <p>Phone: <a href="tel:081378534920">081378534920</a></p>
          <p>Date of Birth: January 9, 2005</p>
          <p>Location: Malang</p>
        </div>
      </div>

      <div class="section">
        <h2>About Me</h2>
        <p>Hello, I am Ilmi Ananda Putri, usually called Ana. I am a third-semester student of Information Technology at Universitas Brawijaya. I am quite interested in modern technology and databases.</p>
      </div>

      <div class="section">
        <h2>Education</h2>
        <ul>
          <li>SMP Negeri 4 Pekanbaru (2016 - 2019)</li>
          <li>SMA Negeri 1 Pekanbaru (2019 - 2023)</li>
          <li>D3 Information Technology, Universitas Brawijaya (2023 - Present)</li>
        </ul>
      </div>

      <div class="section">
        <h2>Experience</h2>
        <ul>
          <li>International Business Plan Olivia 2023 – Solo (2023)</li>
        </ul>
      </div>

      <div class="section">
        <h2>Skills</h2>
        <ul>
          <li>Basic Databases</li>
          <li>Figma</li>
          <li>Vue.js</li>
          <li>Basic JavaScript</li>
          <li>Basic Vue.js</li>
          <li>Basic PHP</li>
          <li>Basic HTML</li>
          <li>Basic Python</li>
          <li>Basic CSS</li>
        </ul>
      </div>

      <div class="section">
        <h2>Hobbies</h2>
        <ul>
          <li>Travelling</li>
          <li>Photography</li>
          <li>Hiking</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style>
.cv-container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #a9def4; /* Light background for contrast */
  padding: 20px;
}

.cv {
  background-color: rgb(244, 165, 211);
  border-radius: 10px;
  box-shadow: 0 2px 15px rgba(0, 0, 0, 0.2);
  padding: 30px;
  width: 100%;
  max-width: 800px;
}

.header {
  display: flex;
  align-items: center;
  margin-bottom: 30px;
}

.profile-photo {
  width: 120px; /* Slightly larger size for better visibility */
  height: 120px; /* Slightly larger size for better visibility */
  border-radius: 50%; /* Makes the photo circular */
  margin-right: 20px; /* Space between photo and text */
}

.info {
  text-align: left; /* Align text to the left */
}

.header h1 {
  font-size: 2.5em;
  color: #000000; /* Black color for the name */
}

.header p {
  font-size: 1em;
  color: #000000;
}

.section {
  margin-bottom: 20px;
}

.section h2 {
  border-bottom: 2px solid #000000; /* Black border for section titles */
  padding-bottom: 5px;
  margin-bottom: 10px;
  color: #000000; /* Black color for section titles */
}

.section p {
  font-size: 1em;
  color: #333;
}

.section ul {
  list-style-type: none;
  padding-left: 0;
}

.section li {
  padding: 5px 0;
  font-size: 1em;
  color: #333;
}

a {
  color: #000000; /* Black color for links */
  text-decoration: none;
}

a:hover {
  text-decoration: underline; /* Underline links on hover for interactivity */
}
</style>
