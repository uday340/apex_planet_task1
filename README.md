# apex_planet_task1
developed all three codes using html,css,js
#HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Profile</h1>
    </header>

    <div class="content">
        <section class="biography">
            <!-- Use relative path or upload to web location if using on web -->
            <img src="C:\Users\kolluruudaykiran\OneDrive\Pictures\img1.jpg" alt="Profile Image" width="200">
            <h2>About Me</h2>
            <p>
                I am Uday Kiran, from Ravikamatham village, Anakapalli district. I studied from 1st to 8th grade at Montessori English Medium School, then completed my 9th and 10th at SSNM English Medium School.
                I pursued a diploma at KIET College, Korangi, in Kakinada district, and currently I'm pursuing B.Tech at Sri Venkateswara College of Engineering and Technology (Autonomous), Chittoor. 
                I am now in my 3rd year at SVCET.
            </p>
        </section>

        <section class="achievements">
            <h2>Achievements</h2>
            <ul>
                <li>Certificate on Communication Skills (Unnati Program)</li>
                <li>Certificate from IBM Skills Program</li>
                <li>Certificate on Python from Infosys Springboard</li>
            </ul>

            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Python</li>
                <li>Java</li>  
            </ul>
        </section>
    </div>

    <section class="contact">
        <h2>Contact Me</h2>
        <p>Visit my LinkedIn: <a href="https://www.linkedin.com/in/uday-kiran-kolluru" target="_blank">Uday LinkedIn Profile</a></p>
        <p>Visit Instagram: <a href="https://www.instagram.com/?__pwa=1" target="_blank">Uday Instagram</a></p>
        <p>Visit GitHub: <a href="https://github.com/dashboard" target="_blank">Uday GitHub</a></p>
        <button id="alertButton">Click Me!</button>
    </section>

    <script>
        document.getElementById("alertButton").addEventListener("click", function () {
            alert("Thank you for visiting my profile!");
        });
    </script>
</body>
</html>

#CSS---------------------------------------------------------------------------------------------------------------------------------------------------------------

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
    color: #333;
}


header {
    background-color: #006400;
    color: #fff;
    text-align: center;
    padding: 20px;
}

h1 {
    font-size: 36px;
    margin: 0;
}


.content {
    padding: 20px;
    max-width: 900px;
    margin: 0 auto;
}

/* Biography section styling */
.biography {
    background-color: #ffffff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
}

.biography h2 {
    font-size: 24px;
    margin-bottom: 10px;
    text-align: center;
}




/* Achievements section styling */
.achievements {
    background-color: #ffffff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.achievements h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

.achievements ul {
    list-style-type: disc;
    padding-left: 20px;
}

.achievements li {
    margin-bottom: 10px;
}
.skills h2{
  background-color: #ffffff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.biography img {
    width: 150px;
    height: 150px;
}
---------------------------------------------JAVA SCRIPT----------------------------------------------------------------------------------------
document.getElementById('alertButton').addEventListener('click', function() {
    alert('Hello! You clicked the button!');
});
