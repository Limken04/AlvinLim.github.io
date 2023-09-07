
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Your Name - Portfolio</title>
</head>
<style>
    /* Reset some default styles */
    
    body,
    h1,
    h2,
    h3,
    p,
    ul,
    li {
        margin: 5;
        padding: 5;
        text-align: center;
    }
    
    /* Set background and text colors */
    
    body {
        font-family: 'Times New Roman', Times, serif, sans-serif;
        background-color: #8bdff865;
        color: #000000;
    }
    
    .container {
        max-width: 960px;
        margin: 0 auto;
        padding: 10px;
    }
    
    header {
        background-color: #333;
        color: #fff;
        padding: 10px 0;
    }
    
    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-image: "https://cdn.wallpapersafari.com/58/81/SGBTp8.png";
    }
    
    nav ul {
        list-style-type: none;
    }
    
    nav ul li {
        display: inline;
        margin-right: 20px;
    }
    
    nav a {
        text-decoration: none;
        color: #fff;
        font-weight: bold;
    }
    
    section {
        padding: 40px 0;
        text-align: center;
    }
    
    .project-card {
        background-color: rgba(255, 68, 0, 0.425);
        padding: 20px;
        box-shadow: 0 4px 8px rgba(23, 34, 250, 13.2);
        margin-bottom: 20px;
    }
    
    footer {
        background-color: #3f1b1b;
        color: #fff;
        text-align: center;
        padding: 5px 10;
    }
    /* Add styles for the profile picture */
    
    .profile {
        text-align: center;
        margin: 20px 10;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
    
    .profile img {
        width: 200px;
        /* Set the width to your desired size */
        height: 200px;
        /* Set the height to your desired size */
        border-radius: 50%;
        /* To make it a circular image (optional) */
    }
    /* Add more custom styles as needed */
    /* Add styles for the profile picture */
    
    .profile {
        text-align: center;
        margin: 20px 0;
        background-color: #3f1b1b;
    }
    
    .profile img {
        width: 200px;
        /* Set the width to your desired size */
        height: 200px;
        /* Set the height to your desired size */
        border-radius: 50%;
        /* To make it a circular image (optional) */
    }
</style>

<body>
    <header>
        <nav>
            <div class="container">
                <h1>Welcome to My Page</h1>
                <div class="profile">
                    <img src="https://scontent.fmnl4-4.fna.fbcdn.net/v/t39.30808-6/293849200_738770540667150_8618902460215894261_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=1b51e3&_nc_eui2=AeFqZzAXGVG4Sn29YdNxjkrKJrbBYXZbjuEmtsFhdluO4dIPy9WzS1pDDIFlWhO9p4B0B1b7UVYo9wFJ-DlBXWkn&_nc_ohc=DeW0HRSJobMAX9O1PC-&_nc_ht=scontent.fmnl4-4.fna&oh=00_AfBMtL4LLbGFUltjLfzsEw3k1GcSjnyywVRqLZXQn35LKw&oe=64FEDF6F" alt="Your Profile Picture">
                </div>
                <ul>
                    <li><a href="#Profile">Profile</a></li>
                    <li><a href="#About me">About me</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <section id="Profile" class="section">
        <div class="container">
            <h2>My profile</h2>
            <p>"Magandang araw! I'm Alvin, a dedicated web developer student from the Philippines. I'm currently pursuing my Bachelor's degree in Computer Science at Pamantasan ng Lungsod ng Muntinlupa a University, with a focus on web development. My passion
                for coding ignited when I built my first webpage, and I've been on an exciting journey ever since. </p>
        </div>
    </section>

    <section id="About me" class="section">
        <div class="container">
            <h2>About Me</h2>
            <!-- Add your project cards here -->
            <div class="project-card">
                <h3>My Skills</h3>
                <p>I'm enthusiastic about crafting immersive and user-friendly websites. I'm well-versed in front-end technologies like HTML, CSS, and JavaScript, and I'm diving into back-end development using languages like PHP and Python. Being part of
                    coding clubs and PLMUN in my university has allowed me to work on collaborative projects and enhance my coding skills.</p>
                <div class="profile">
                    <img src="https://www.interviewbit.com/blog/wp-content/uploads/2021/06/Front-End-Developer-Skills.jpg" alt="Your Profile Picture">
                </div>
            </div>

            <div class="project-card">
                <h3>Why Computer Science?</h3>
                <p>As a Filipino, I'm particularly interested in creating web solutions that cater to the unique needs of our local communities. I'm keen on promoting digital literacy and accessibility, ensuring that the internet is an inclusive space for
                    everyone.
                </p>
                <div class="profile">
                    <img src="https://wallpaperaccess.com/full/3239444.jpg" alt="Your Profile Picture">
                </div>
            </div>
            <!-- Add more project cards as needed -->
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me through the following channels:</p>
            <ul>
                <li>Email:Alvinken04@gmail.com.com</li>
                <li>Facebook: <a href="https://www.facebook.com/alvinken04">Facebook Profile</a></li>
                <!-- Add other contact information as needed -->
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 HCI</p>
        </div>
    </footer>
    <script src="script.js"></script>
</body>

</html>
