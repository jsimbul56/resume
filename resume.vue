<template>
  <body>
    <template>
        <div id="resume">

                <div id="profile">
                    <img src="./assets/pic01.jpg" alt="Profile" id="profile-image">
                    <h1> JIMUEL SIMBUL</h1>
                    <h2>WEB DEVELOPER</h2>
                </div>

            <section id="content">
                <div id="left-column">
                    <h3>Profile</h3>
                    <p>I have five years of expertise designing websites and managing databases as a professional web developer. strong analytical and creative abilities. a detail-oriented team player.</p> <br>

                    <h3>Experience</h3>
                    <div class="experience-item">
                        <h4>Applications Developer</h4>
                        <p>Really Great Company</p>
                        <p>2016 - Present</p>
                        <ul>
                            <li>Database administration and website design</li>
                            <li>Built the logic for a streamlined, all-in-one platform</li>
                            <li>Educational institutions and online classroom management</li>
                        </ul>
                    </div>


                </div>

                <div id="right-column">
                    <h3>Contact</h3>
                    <p>📞 0912-345-6789</p>
                    <p>✉️ simbul@example.com</p>
                    <p>🏠 123 Anywhere St, Any City</p>
                    <p>🌐 reallynicesite.com</p> <br>

                    <h3>Education</h3>
                    <p>Secondary School<br>Really Nice High School<br>2010 - 2014</p>
                    <p>Bachelor of Technology<br>Really Nice University<br>2014 - 2016</p> <br>

                    <h3>Skills</h3>
                    <ul>
                        <li>Web Design</li>
                        <li>Design Thinking</li>
                        <li>Front End Coding</li>
                        <li>Database Management</li>
                        <li>Computer Literacy</li>
                        <li>Strong Communication</li>
                    </ul>
                </div>
            </section>
        </div>
    </template>
</body>
</template>

<script>

</script>

<style>

body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

#resume {
    background-color: white;
    width: 70%;
    margin: 50px auto;
    padding: 20px;
    box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
    align-items: flex-start;
}

header {
    grid-column: span 2;
    text-align: center;
    margin-bottom: 30px;
}

#profile {
    margin-bottom: 20px;
    padding-top: 40px;
}

#profile-image {
    border-radius: 50%;
    width: 200px;
    height: 200px;
    display: block;
    margin: 0 auto 20px;
}

h1 {
    font-size: 36px;
    color: #333;
    margin: 10px 0 0;
    text-align: center;
}

h2 {
    font-size: 20px;
    color: #b08d70;
    margin: 0;
    text-align: center;
    letter-spacing: 2px;
}

#content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
}

#left-column {
    padding-right: 40px;
    border-right: 1px solid #ddd;
}

#right-column {
    padding-left: 40px;
}

h3 {
    font-size: 18px;
    color: #b08d70;
    margin-bottom: 15px;
    text-transform: uppercase;
    letter-spacing: 1px;
}

p, ul, li {
    font-size: 14px;
    line-height: 1.6;
    color: #333;
}

ul {
    list-style: none;
    padding-left: 0;
}

ul li::before {
    content: "• ";
    color: #b08d70;
}

.experience-item h4 {
    font-size: 16px;
    margin-top: 10px;
    color: #333;
}

.experience-item p {
    margin: 5px 0;
    color: #555;
}

</style>
