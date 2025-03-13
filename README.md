# portfolio

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="port.css">
    <title>Swayam R Vernekar</title>
</head>

<body>
    <div class="main">
        <div class="left-panel">
            <img src="swayam.jpg" alt="Swayam R Vernekar" class="profileimg" />
            <div>
                <h2 class="name">Swayam R Vernekar</h2>
                <p class="place">Davanager,Karnataka,India</p>
            </div>
            <ul class="logos">
                <li>
                    <a href="https://github.com/ver1619">
                        <img src="logo.png" alt="GitHub" class="img" /></a>
                </li>
                <li>
                    <a href="https://www.linkedin.com/in/swayam-vernekar-626aaa2b9/">
                        <img src="linkedin.jpg" alt="LinkedIn" class="img" /></a>
                </li>


            </ul>
        </div>
        <div class="right-panel">
            <h3>About:</h3>
            <hr />
            <p class="desc">Swayam Ramnath Vernekar</p>
            <h4>Education Status:</h4>
            <ul>

                <p>
                <h5 class="hi">Currently Pursueing B.E in Artificial Intelligence & Machine Learning</h5><br />
                <p class="e1">In Bapuji Institute Of Engineering and Technology,Davanagere,Karnataka</p>
                <p class="year">2023-27</p>
                </p>
            </ul>

            <ul>
                <p>
                <h5 class="hi">Pre-University Education</h5><br />
                <p class="e1">From Vishnavi Chetna PU College,Davanagere,Karnataka</p>
                </p>
                <p class="year">2021-23</p>
                </p>
            </ul>

            <ul>
                <p>
                <h5 class="hi">Secondary Education</h5><br />
                <p class="e1">From Bapuji Higher Primary English Medium School,Davanagere,Karnataka
                </p>
                <p class="year">2016-21</p>
                </p>
            </ul><br />

            <h4 id="skill"> Skills:</h4><br />
            <hr />
            <p class="skills">
                <img src="python.png" alt="python" />
                <img src="bash.png" alt="bash" />
                <img src="html.png" alt="html" />
                <img src="css.png" alt="css" />
                <img src="sql.png" alt="js" />

            </p>

            <h4>Projects:</h4><br />
            <hr />
            <ul>
                <li></li>
                <li></li>
            </ul>

            <h4>Credentials:</h4><br />
            <hr />
            <ul>
                <li>
                    <h5 class="id">Contact:</h5>
                    <p class="cre">Phone: +91 861-82-77436</p>
                </li>
                <li>
                    <h5 class="id">E-mail</h5>
                    <p class="cre">swmvernekar@gmail.com</p>
                </li>
            </ul>





        </div>
</body>

</html>



body {
    margin: 0;
    padding: 0;
    overflow: hidden;
}

.main {
    display: flex;
    height: 100vh;
}

.left-panel {
    width: 20%;
    height: 100%;
    background-color: rgb(0, 0, 0);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.right-panel {
    width: 80%;
    height: 100%;
    overflow-y: scroll;
    background-color: rgb(153, 125, 238);
    padding: 1rem;
}

.profileimg {
    height: 12rem;
    width: 12rem;
    object-fit: cover;
    filter: blur(0.5);
    filter: saturate(5);
    filter: contrast(100%) brightness(100%);
    border-radius: 100%;
}

.logos {
    list-style-type: none;
    display: flex;
    gap: 1rem;
    margin-left: -60px;
}

.img {
    margin-left: -10%;
    height: 4rem;
    width: 4rem;
}


.name {
    font-size: xx-large;
    color: white;
}



h2 {
    font-family: 'Times New Roman', Times, serif;
}

.place {
    font-size: larger;
    margin-top: -10px;
    margin-left: 25px;
    color: white;
    font-family: 'Segoe UI', sans-serif;
}

h3 {
    color: black;
    font-family: Impact, sans-serif;
    font-size: 2rem;
    margin-bottom: 0%;

}

.desc {
    margin-top: 0%;
    font-size: x-large;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

}

.education {
    font-size: xx-large;
    margin-left: -30px;
}

.year {
    margin-top: -1%;
    font-style: normal;
    font-size: larger;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif
}

h4 {
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    margin-bottom: -1%;
    font-size: xx-large;
    text-decoration: underline;
}

h5 {
    margin-bottom: -1%;
    font-size: medium;
    font-family: Georgia, 'Times New Roman', Times, serif;
}

#skill {
    font-size: xx-large;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.skills {
    display: flex;
    justify-content: flex-start;
    /* Align items to the start */
    align-items: center;
    /* Vertically center items */
    padding: 20px;
    /* Add some padding around the container */

}

.skills img {
    margin-top: -1%;
    margin-right: 120px;
    /* Add space between images */
    max-width: 80px;
    /* Adjust image size as needed */
    height: auto;
    /* Maintain aspect ratio */

}

.hi {
    font-size: x-large;
}

.e1 {
    margin-top: 0rem;
    font-size: x-large;
}

.id {
    font-size: larger;
    font-style: normal;
    margin-bottom: -1%;
    margin-top: -1%;

}

.cre {
    font-size: x-large;
}
