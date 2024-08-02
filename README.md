# my-portfolio (.html)
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="view port" content="width=device=width, initial=scale=1.0">
        <title>Document</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
       <div class="navbar">
        <div class="navbar-left">
        <img  class="logo-imagr"src="https://res.cloudinary.com/drkhss4dw/image/upload/v1722371763/WhatsApp_Image_2024-07-31_at_2.05.36_AM_mvigvc.jpg" alt="logo" > 
        </div>
        <div class="navbar-right"> 
            <a class="a-element" href="#About"> About </a>
            <a class="a-element" href="#Education"> Education</a>
            <a class="a-element" href="#Skills"> Skills</a>
            <a class="a-element" href="#Projects"> Projects</a>
        </div>
       </div>
       <div class="home">
        <div class="home-left">
            <h1>MANJU PATTAPU</h1>
            <p> Hi everyone., 
                My name is "PATTAPU MANJU BHARGAVI" , a passionate batchelors degree candidate in computer science and engineering  at "KALLAM HARANADHA REDDY INSTITUTE OF TECHNOLOGY".with a special
                intrest in frontend-developement and i bring a diverse background in frontend frontend-developement to contribute to the team's success. I am the student with proactive and adaptable
                professional who excels in problem solving and delevering high-quality results.</p>
        </div>
        <div class="home-right">
            <img src="https://res.cloudinary.com/drkhss4dw/image/upload/v1722367592/WhatsApp_Image_2024-07-31_at_12.55.51_AM_sxd0rx.jpg"alt=" my logo" >
        </div>
       </div>
       <div class="About" id="About">
        <h1 class="Abt-h1"> ABOUT ME</h1>
        <div class="About-sub-container">
            <div class="About-card">
                <P class="ps-p"> MY NAME IS "PATTAPU MANJU BHARGAVI" CURRENTLY PURSUING B.TECH FINAL YEAR.<br>
                     IN COMPUTER SCIENCE AND ENGINEERING AT "KALLAM HARANADHA REDDY INSTITUTE OF TECHNOLOGY"
                    WITH 8.24 AGGREGATE. SPECIAL INTREST ON DEVELOPING WEB SITES.<br>
                 GMAIL:-@pattapumanju576@gmail.com</P>
            </div>
        </div>
       </div>
       <div class="Education"> 
        <h1 class="Ed-h1"> EDUCATION </h1>
        <div class=" education-info">
                <p> CURRENTLY PURSUING B.TECH YEAR IN COMPUTER SCIENCE AND ENGINEERING AT "KALLAM HARANADHA REDDY INSTITUTE OF TECHNOLOGY".<br>
                    COMPLETED INTERMEDIATE IN THE YEAR 2021 WITH 70% PERCENTAGE. <br> SECURED 9.7 GPA IN SSC IN YEAR YEAR 2019.
                </p>
        </div>
        <div class="Skills">
            <h1 class="sd-h1"> SKILLS</h1>
            <div class="Skills-info">
                <p> BASICS IN C PROGRAMMING. <br>PYTHON PROGRAMMING<bR>
                HTML,CSS</p>
            </div>
        <div> 
            <div class="Project">
                <h1 class="pd-h1"> PROJECT</h1>
                <div class=" project-info">
                <p class="pd-p"> WE DONE A PROJECT CALLED COMMUNITY SERVICE PROJECT(CSP) I PLAYED A TEAM LEAD ROLE IN THIS PROJECT.<br>
                    WE PICKED A TOPIC CALLED "HORTICULTURE" THE DURATION OF THE PROJECT IS 2 MONTHS.<br>
                    OUR TEAM IS ABOUT 5 MEMBERS. WE ALSO CONDUCTED SURVEYS AT GARDENS.<br> 
                    I PLAYED MY ROLE IN A SINCIERE MANNER TO SUCCED THE PROJECT WITH BEST RESULTS</p>
                </div>
        </div>
        <div class="socialS-icons">
           <div class="social-icon">
            <a href="https://www.instagram.com/i.m_manju30?igsh=MW42bmU3ODlhcDZrcg==">
            <img src="https://th.bing.com/th/id/R.26d9974a1feec9905a4e0d5e5ddf8db6?rik=Og1ujXM2C1AJHQ&riu=http%3a%2f%2fupload.wikimedia.org%2fwikipedia%2fcommons%2fa%2fa5%2fInstagram_icon.png&ehk=1%2fZWXYn2nN%2fR80TOtcKH5SsdLkkUvMLrB%2fHUXRDHk9I%3d&risl=&pid=ImgRaw&r=0"class="social-icon-img">
            </a>
            </div>
        </div>
        <div class="social-icon">
            <a href= " https://www.linkedin.com/in/manju-pattapu-a3069a254?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
            <img src="https://pngimg.com/uploads/linkedIn/linkedIn_PNG29.png"class="social-icon-img">
            </a>
            </div>
        </div>

    </body>
</html>
(.css)
body {
    margin: 0;
    background-color:black;
    color: white;
 }
 .navbar {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    background-color: black;
}
.navbar-left {
    padding-left: 20px;
    height: 200px;
}
.logo-image {
    height 500px;
}
.navbar-right{
    padding-right: 20px;
    display: flex;
    flex-direction:row;
    align-items: center;
    color: white;
}
.a-element {
    padding: 10px;
    margin: 10px;
font-family:'Times New Roman', Times, serif ;
font-size: 25px;
font-weight: bold;

}   
.home {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    height: 85vh;
} 
.home-left {
    width:50vw;
    padding-right: 100px;
    text-align: right;
    padding-left: 200px;
}
.home-right{
    width: 50vw;   
}
.About {
  padding: 10px;
  text-align: center;
}
.Abt-h1 {
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: rgb(232, 192, 255);
    letter-spacing: 3px;
    font-size: 35px;
}
.ps-h1{
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: aqua;
}
.ps-p {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.Education {
    text-align: center;
    padding: 10px;
}
.Ed-h1 {
    font-family:  Georgia, Times, 'Times New Roman', serif;
    color :rgb(232, 192, 255);
    letter-spacing: 3px;
    font-size: 35px;
}
.education-info {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.Skills {
    text align: center;
    padding: 10px;
}
.sd-h1 {
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: rgb(232, 192, 255);
    letter-spacing:3px ;

}
.Project{
    text-align: center;
    padding: 10px;
}
.pd-h1 {
    font-family:  Georgia, Times, 'Times New Roman', serif;
    color :rgb(232, 192, 255);
    letter-spacing: 4px;
    font-size: 35px;
}
.pd-p {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    letter-spacing: 1px;
}

.social-icon-img {
    height :50px;
    padding :20px;
}

    






