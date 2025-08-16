# apex_planet_task1
developed all three codes using html,css,js
#HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>my profile</h1>
    </header>
    
    <div class="content">
        <section class="biography">
            <img src="C:\Users\kolluruudaykiran\OneDrive\Pictures\img1.jpg".>
            <h2>About me</h2>
            
            <p>I am uday kiran,from ravikamatham village anakapalli district.I have studied 1st to 8th at montessori english medium school,9th to 10th at SSNM English Medium School.Stepin to diploma KIET College at korangi kakinada district.After joined btech in Sri Venkateswara college of engineering and technology(Autonomous) in Chittoor.Iam currently pursuing 3rd year in SVCET </p>
        </section>

        <section class="achievements">
            <h2>Achievements</h2>
            <ul>
                <li>i had achieved a certificate on communication skills in unnati program</li>
                <li>i had achieved a certificate on ibm skills</li>
                <li>i haad achueved a certificate on infosys springboard on python</li>
            </ul>
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>PYTHON</li>
                <li>JAVA</li>  
           </ul>
        </section>
    </div>
   <section>
            <h2>Contact Me</h2>
            <p>Visit my Linkdin: <a href="https://www.linkedin.com/in/uday-kiran-kolluru?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Get In Touch</a></p>
            <p>visit instagram: <a href="https://www.instagram.com/?__pwa=1">Instagram</a></p>
            <button id="alertButton">Click Me!</button>
    </section>
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
