   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

      

        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            color: #222222;
        }

   

        header {
            background: #0750b5;
            color: white;
            padding: 15px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h2 {
            font-size: 22px;
        }

        nav a {
            color: rgb(255, 255, 255);
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
        }

    

        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 50px 5%;
            min-height: 280px;
        }

        .hero h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        .hero h2 {
            color: #5eeaff;
            font-size: 38px;
            margin-bottom: 15px;
        }

        .hero p {
            color: #777;
            font-size: 14px;
        }

        .profile {
            width: 230px;
            height: 190px;
            border-radius: 50%;
            background: #ffc8de;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 100px;
        }

       

        section {
            padding: 25px 3%;
        }

        section h2 {
            font-size: 24px;
            margin-bottom: 15px;
        }

       

        #about p {
            font-size: 13px;
            
            color: #555;
        }

       

        .skills-container {
            display: flex;
            gap: 20px;
            padding: 10px 20px;
        }

        .skill {
            
            background: #0750b5;
            color: white;
            text-align: center;
            padding: 18px;
            border-radius: 6px;
            font-size: 15px;
           
        }

      

        

        .projects-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        .project {
            background: white;
            width: 65%;
            min-height: 120px;
            padding: 20px;
            text-align: center;
            border-radius: 6px;
            
           
        }

     

        .project p {
            color: #777;
            font-size: 13px;
        }

      

        .contact-form {
            background: white;
            width: 320px;
            margin: auto;
            padding: 20px;
            border-radius: 6px;
        }

        .contact-form label {
            display: block;
            font-size: 13px;
            margin-top: 10px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #0750b5;
            border-radius: 4px;
        }

        .contact-form textarea {
            height: 80px;
        }

        .contact-form button {
            width: 100%;
            padding: 10px;
            margin-top: 12px;
            background: #0750b5;
            color: white;
            border: none;
         
        }

     

        footer {
            background: #0750b5;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 13px;
        }

      

        .top-button {
            position: fixed;
            bottom: 15px;
            right: 15px;
            background: #0750b5;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 4px;
            font-size: 12px;
        }

        

       
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 5px;
            }

            .hero {
                flex-direction: column-reverse;
                text-align: center;
                gap: 25px;
            }

            .hero h1 {
                font-size: 30px;
            }

            .hero h2 {
                font-size: 27px;
            }

            .skills-container {
                flex-direction: column;
            }

            .project {
                width: 95%;
            }

        

         

            .contact-form {
                width: 100%;
            }

            .profile {
                width: 170px;
                height: 150px;
                font-size: 75px;
            }

            .img1{
                width: 200px;
                height: 200px;
                border-radius: 50%;
                object-fit: cover;
                border-style: double;
            
             
            }

        

    </style>
</head>

<body id="top">

  

    <header>

        <h2>My Portfolio</h2>

        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>

    </header>


  

    <div class="hero">

        <div>
            <h1>Hi, I am</h1>

            <h2>Mangal Singh </h2>

            <p>
                Aspiring Web Developer | B.Tech CSE AI/ML Student
            </p>

        </div>

       <div class="">
      <img src="image.jpeg" class="img1">

       </div>

    </div>


    

    <section id="about">

        <h2>About Me</h2>

        <p>
            Hello! My name is Mangal singh, and I am currently
            learning web development. I am interested in
            programming, technology and creating interactive
            websites. My goal is to improve my skills and
            build useful web projects.
        </p>

    </section>


    

    <section id="skills">

        <h2>My Skills</h2>

        <div class="skills-container">

            <div class="skill">
                <h3>HTML</h3>
                <p>Beginner</p>
            </div>

            <div class="skill">
                <h3>CSS</h3>
                <p>Beginner</p>
            </div>

            <div class="skill">
                <h3>Python</h3>
                <p>Learning</p>
            </div>

        </div>

    </section>


   

    <section id="projects">

        <h2>My Projects</h2>

        <div class="projects-container">

            <div class="project">

                <h3>Project 1</h3>

                <p>
                    A simple HTML and CSS webpage.
                </p>

            </div>

            <div class="project">

                <h3>Project 2</h3>

                <p>
                    My personal portfolio website.
                </p>

            </div>

        </div>

    </section>


  

    <section id="contact">

        <h2>Contact Me</h2>

        <form class="contact-form">

            <label>Name:</label>
            <input type="text"
                   placeholder="Enter your name"
                   required>

            <label>Email:</label>
            <input type="email"
                   placeholder="Enter your email"
                   required>

            <label>Message:</label>
            <textarea placeholder="Write your message"
                      required></textarea>

            <button type="submit">
                Send
            </button>

        </form>

    </section>


    

    <footer>

        <p>
            © 2026 Bhupender Saini. All rights reserved.
        </p>

    </footer>


    

</body>
</html>
