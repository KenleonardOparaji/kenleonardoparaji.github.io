<!DOCTYPE html>
<html lang="en">
<meta charset="UTF-8">
<title>Page Title</title>
<meta name="viewport" content="width=device-width,initial-scale=1">
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
<link rel="stylesheet" href="carousel/carousel/slick/slick.css">
<link rel="stylesheet" href="carousel/carousel/slick/slick-theme.css">
<style>

html{
    scroll-behavior: smooth;
}
    
    body{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color:  rgb(8, 24, 58);
    font-size: large;
}

#menu{
    display: flex;
    border-radius: 50px;
    flex-direction: column;
    border-color: black;
    border-width: 3px;
    height: 175px;
}


#navbar{
    display: flex;
    margin: auto;
    border: 5px solid black;
    border-radius: 30px;
    font-weight: bold;
}

.tab{
    transition: all 1s;
    font-size: 24px;
    width: 175px;
    height: 70px;
    text-align: center;
    line-height: 70px;
    text-decoration: none;
    border-radius: 30px;
    color: white;
}

.tab:hover{
    transition: all 1s ease 0s;
    background: purple;
}

#summaryblock{
    display: flex;
    margin: auto;
}

#summary{
    font-size: 28px;
    margin: auto;
    width: 1300px;
    height: 300px;
    color: white;
    line-height: 3rem;
    text-align: center;
    vertical-align: middle;
}



#portraitbox{
    display: flex;
    flex-direction: column;
    margin-left: 100px;
}

#portrait{
    border-radius: 50%;
    margin: auto;
    width: 400px;
    height: auto;
}


#scrollingcontainer{
    margin: auto;
    width: 1200px;
    height: auto;
    display: flex;
}
.sunset{
    height: 550px;
    margin: auto;
    border-radius: 30px;
    border: 3px;
    border-color: black;
}

#name{
    color: white;
    margin: auto;
}

#experiences{
    display: flex;
    flex-direction: column;
    width: 1300px;
    margin: auto;
    margin-top: 50px;
}

#experienceblocks{
    display: flex;
    flex-direction: row;
}

.experienceblock{
    display: flex;
    width: 375px;
    flex-direction: column;
    height: 600px;
    background-color: aliceblue;
    margin: auto;
    text-align: center;
    line-height: 1rem;
    border-radius: 50px;
    color: white;
}

.experienceblock.nuprizm{
    background-color: purple;
    border: 5px solid white;
}

.experienceblock.addisonconsultinggroup{
    background-color: blue;
    border: 5px solid yellow;
}

.experienceblock.therundown{
    background-color: red;
    border: 5px solid blue;
}

.workicon.nuprizm{
    height: 100px;
    width: 100px;
    margin: auto;
    
}

.experiencedetails{
    margin: 10px;
}

#work{
    display: flex;
    flex-direction: column;
    width: 1300px;
    margin: auto;
    margin-top: 70px;
}

#workblocks{
    display: flex;
    margin: auto;
    flex-direction: column;
}

#workblocks > div{
    display: flex;
    width: 1200px;
    height: 300px;
    margin-top: 50px;
    flex-direction: row;
    
}

.project{
    display: flex;
    width: 500px;
    flex-direction: column;
    height: 700px;
    margin: auto;
    text-align: center;
}

.project.publicrelations{
    display: flex;
    flex-direction: column;
    border: 5px solid white;
    height: 700px;
    border-radius: 30px;
    color: white;
    background-color: red;
    line-height: 2rem;
}

.project a:hover{
    transition: all 1s;
    scale: 1.2;
}


.projectdetails{
    margin: 10px;
}

.project.webdev{
    display: flex;
    flex-direction: column;
    border: 5px solid grey;
    height: 700px;
    border-radius: 30px;
    color: white;
    background-color: rgb(0, 0, 0);
    line-height: 2rem;
}



.projecticon.jacklogo{
    width: 417px;
    margin-top: 21px;
    height: auto;
    border-radius: 25px;
}



.projecticon.pokemonsurvivor{
    width: 371px;
    height: auto;
    margin-top: 20px;
    
}


.writing{
    display: flex;
    width: 500px;
    flex-direction: column;
    height: 700px;
    margin: auto;
    text-align: center;
    margin-top: 400px;
}

.writing.dragonball{
    display: flex;
    flex-direction: column;
    border: 5px solid white;
    height: 750px;
    border-radius: 30px;
    background-color: rgb(5, 6, 54);
    color: white;
    line-height: 2rem;
}

.writing.ukraine{
    display: flex;
    flex-direction: column;
    border: 5px solid rgb(255, 251, 0);
    height: 750px;
    border-radius: 30px;
    background-color: rgb(0, 4, 255);
    color: white;
    line-height: 2rem; 
}

.writingicon.dragonball{
    width: 270px;
    height: 350px;
    margin-left: auto;
    scale: .85;
}

.writingicon.dragonball:hover{
    transition: all 1s;
    scale: 1;
}

.writingicon.ukraine{
    width: 270px;
    height: 350px;
    margin-left: auto;
    scale: .85;
}

.writingicon.ukraine:hover{
    transition: all 1s;
    scale: 1;
}


.project.webdev{
    display: flex;
    flex-direction: column;
    border: 5px solid grey;
    height: 700px;
    border-radius: 30px;
    color: white;
    background-color: rgb(0, 0, 0);
    line-height: 2rem;
}

.video{
    display: flex;
    width: 500px;
    flex-direction: column;
    height: auto;
    margin: auto;
    margin-top: 850px;
    text-align: center;
}

.video video{
    margin: auto;
    border: 5px solid black;
    border-radius: 30px;
}

.video.nuprizm{
    border: 5px solid black;
    border-radius: 30px;
    background-color: purple;
}

.video.rundown{
    border: 3px solid black;
    background-color: red;
    border-radius: 30px;
}

.video p{
    margin: 10px;
    line-height: 2rem;
}

#education{
    display: flex;
    flex-direction: column;
    margin-top: 70px;
    margin: auto;
    width: 1300px;
}

.educationblock{
    width: 1300px;
    height: 300px;
    margin: auto;
    background-color: white;
    border-radius: 50px;
    display: flex;
    flex-direction: row;
    border: black 5px solid;
}



.educationlogo{
    margin-left: auto;
    display: flex;
    flex-direction: column;
}
.education.usclogo img{
    width: 200px;
    height: auto;
}

.education.graduation{
    text-align: center;
}

.educationblock div{
    margin: auto;
}
.workicon{
    width: 100px;
    height: 100px;
    border-radius: 50px;
}

#contact{
    margin-top: 70px;
}
.caption{
    color: white;
}

.caption.contact{
    text-align: center;
}

.imageblock{
    display: flex;
    flex-direction: column;
}

.imageblock img{
    width: 300px;
    height: 300px;
    margin: auto;
}

#contact{
    margin-top: 1200px;
}

.contactbuttons{
    display: flex;
    margin: auto;
    width: 215px;
    height: 150px;
}

.contactbuttons img{
    margin-top: 50px;
    width: 100px;
    height: 100px;
    margin: auto;
}

.imageblock img{
    border: 5px solid black;
    border-radius: 30px;
}

#name a{
    text-decoration: none;
    color: white;
    transition: all 1s;
}
.experiencedetails p{
    color: white;
    line-height: 2rem;
}

#resume{
    width: 400px;
    height: 100px;
    background-color: purple;
    margin: auto;
    text-align: center;
    display: flex;
    border-radius: 30px;
    text-decoration: none;

}

#button{
    margin: auto;
    text-decoration: none;
    color: white;

}



</style>

<body>
    <div id="menu">
        <div id="name">
            <a href=""><h1>Kenleonard Oparaji</h1></a>
        </div>
        <div id="navbar">
            <a class="tab summary" href="#summaryblock">Summary 📜</a>
            <a class="tab education" href="#education">Education 🎓</a>
            <a class="tab experiences" href="#experiences">Experiences 👨‍💼</a>
            <a class="tab projects" href="#work">Projects 📝</a>
            <a class="tab contact" href="#contact">Contact 📞</a>
        </div>
    </div>

    <div id="scrollingcontainer">
        <img class="sunset one" src="images/sunset one.jpg" alt="sunset one">
        <img class="sunset two" src="images/sunset two.jpg" alt="sunset two">
        <img class="sunset three" src="images/sunset three.jpg" alt="sunset three">
    </div>

    <div id="summaryblock">
        <div id="summary">
            <h1 data-aos="fade-up" id="intro">👋 Hey, y'all! My name is Ken:</h1>
            <p data-aos="fade-up" id="subtext">A creative and out-spoken storyteller in Public Relations and Web Development with experience 
                as a social media intern and student news anchor and always ready to learn more about the world. 
                Also loves sunsets and travel. DAL ✈️ LAX </p> 
        
        </div>
    </div>

    <a href="https://docs.google.com/document/d/1uwST_zYR0CIhfYjAZwUQaa29mDWTzDRJiou-ic80jZE/edit?usp=sharing" target="_blank">
        <div id="resume">
            <div id="button">
                <h2>Download Resume</h2>
            </div>
        </div>
    </a>
    
    <div id="education">
        <h2 data-aos="fade-up" class="caption education">Education</h2>
        <div data-aos="fade-up" data-aos-duration="500" class="educationblock">
            <div data-aos="fade-up" data-aos-duration="1000" class="education text">
                <h3>University of Southern California</h3>
                <h4>Bachelor of Arts in Public Relations and Minor in Web Development</h4>
                <p><strong>Relevant Coursework:</strong> Strategic Public Relations and Advertising, Writing: Globalization, Web Development, 
                    Spanish
                </p>
                <p><strong>Honors:</strong> Dean's List, Dean's Honors Student</p>
            </div>
            <div data-aos="fade-up" data-aos-duration="1500" class="education usclogo">
                <h4 class="education graduation">
                    Aug 2023 - May 2027
                </h4>
                <img src="images/usc.png" alt="usclogo">
            </div>
        </div>
    </div>

    <div id="experiences">
        <h2 data-aos="fade-up" class="caption experiences">Relevant Experiences</h2>
        <div id="experienceblocks">
            <div data-aos="fade-up" data-aos-duration="500" class="experienceblock nuprizm">
                <div class="experiencedetails">
                    <h3>Nuprizm</h3>
                    <img class="workicon nuprizm" src="images/nuprizm.jpg">
                    <h3>Social Media Intern</h3>
                    <h4>July 2024 - Present</h4>
                    <p>As a social media intern, I publish content to the company's new TikTok account. In addition 
                        to script writing, drafting and editing TikTok videos, I have also conducted research informing 
                        the company on body language, camera and editing techniques most suitable for Nuprizm to pull 
                        and retain engagement on TikTok.
                    </p>
                    <p><strong>Skills: </strong><em>Editing, Writing, Journalism, Social Media, Data Research</em></p>
                  
                </div>
            </div>
            <div data-aos="fade-up" data-aos-duration="1000" class="experienceblock addisonconsultinggroup">
                <div class="experiencedetails">
                    <h3>Addison Consulting Group</h3>
                    <img class="workicon acg" src="images/acg.png">
                    <h3>Fundraising Intern</h3>
                    <h4>May 2024 - June 2024</h4>
                    <p>As a fundraising intern, through marketing and fundraising principles and 
                         fundraising events, I raised over $30,000 for Heifer International. I was one of the top
                          performing interns for the month when my session at the company was over and able to 
                          help newer employees to help the company.
                    </p>
                    <p><strong>Skills: </strong><em>Pitching, Fundraising, Public Speaking, Team Building,
                        Donor Relations
                    </em></p>
                </div>
                
            </div>
            <div data-aos="fade-up" data-aos-duration="1500" class="experienceblock therundown">
                <div class="experiencedetails">
                    <h3>The Rundown</h3>
                    <img class="workicon rundown" src="images/therundown.JPG">
                    <h3>Student News Anchor</h3>
                    <h4>Aug 2023 - Dec 2023</h4>
                    <p>As a student news anchor, I was responsible for communicating the week's stories engagingly
                         while also respecting the subject matter of certain stories. As a freshman, I pulled 
                         in over 5,000 views, exposing the show to a new audience. Here, I learned about social 
                         media news shows and the production behind them.
                    </p>
                    <p><strong>Skills: </strong><em>Media Production, Social Media, Public Speaking</em></p>
                </div>
            </div>
        </div>
    </div>

    <div id="work">
        <h2 data-aos="fade-up" class="caption work">Projects and Works</h2>
        <div id="workblocks">
            <div class="workblock project">
                <div data-aos="fade-up" data-aos-duration="500" class="project publicrelations">
                    <a href="https://docs.google.com/presentation/d/1d56XehdffoVvcC1ejvVGTJL5jQ5pNh2ePheNqqLlQp8/edit?usp=sharing" target="_blank"><img class="projecticon jacklogo" src="images/jackinthebox.png"></a>
                    <div class="projectdetails">
                        <h3>#WhatsInYourBox</h3>
                        <p>My group was tasked to create a campaign for a publicly traded company. From a list 
                            of eight companies, my group chose Jack-in-the-Box. We each had titles that determined 
                            the part of the project we would work on, and I was in charge of the Strategy and Tactics 
                            for the Jack-in-the-Box campaign, using my out-of-the-box thinking, to create a cohesive 
                            project. In my strategy, I leveraged shared earned media and influencer marketing to create
                            a unique campaign designed to appeal to young college students on college campuses near
                            Jack-in-the-Box franchise stores.
                        </p>
                    </div>
                </div>
                <div data-aos="fade-up" data-aos-duration="1000" class="project webdev">
                    <a href="https://uscwebdev.github.io/itp104-submissions-KenleonardOparaji/final_project/homepage.html" target="_blank"><img class="projecticon pokemonsurvivor" src="images/pokemonsurvivor.PNG"></a>
                    <div class="projectdetails">
                        <h3>Pokemon Survivor</h3>
                        <p>For my Intro to Web Development's class, I was tasked with developing a website that 
                        demonstrated my knowledge 
                        of web development principles. My project was based on a passion project I had during 
                        the pandemic---
                        Pokémon Survivor. Using HTML, CSS, and JavaScript, 
                        I transformed my four-year old Survivor simulations into a website that hosts web stories.</p>
                    </div>
                </div>
            </div>
            <div class="workblock writing">
                <div data-aos="fade-up" data-aos-duration="500" class="writing dragonball">
                    <a href="https://docs.google.com/document/d/1f-71EhHZwcXZ8YwBLy3YWsioXPymKelAOnCbLUxl2aI/edit?usp=sharing" target="_blank"><img class="writingicon dragonball" src="images/dragonball.PNG"></a>
                    <div class="projectdetails">
                        <h3>From A to Dragon Ball Z: A Tale of Western Animation Culture on Anime</h3>
                        <p>For this piece, I chose to write about entertainment, specifically the impact of Western 
                            animation culture on Japanese animation, through the Dragon Ball series. I was challenge to think about America's powerful cultural hegemony 
                            before the turn of the millenia and how other countries, Japan in this instance, permeated it. 
                            Entertainment will always be an industry I am fascinated by simply because of 
                            how receptive the industry is to emerging changes brought about by cultural differences.
                        </p>
                    </div>
                </div>
                <div data-aos="fade-up" data-aos-duration="1000" class="writing ukraine">
                    <a href="https://docs.google.com/document/d/1f-71EhHZwcXZ8YwBLy3YWsioXPymKelAOnCbLUxl2aI/edit?usp=sharing" target="_blank"><img class="writingicon ukraine" src="images/ukraine.PNG"></a>
                    <div class="projectdetails">
                        <h3>Today's Story: Uncovering the Ukrainian People in the Rubble of War</h3>
                        <p>For this piece, I wrote about geopolitics, focusing on the Russo-Ukrainian 
                            war. I was inspired to write this by recent events at the time, including Israel's 
                            invasion into the Gaza strip. I was also inspired by The Rundown's covering a story about local  
                            Ukrainian using Etsy to financially support themselves throughout the war. I wanted to examine 
                            the local side of geopolitics, illuminate the story and uncover why mainstream outlets have 
                            yet to cover these type of stories, despite the strong show of resilience.
                        </p>
                    </div>
                </div>
            </div>
            <div class="workblock video">
                <div data-aos="fade-up" data-aos-duration="500" class="video nuprizm">
                    <video width="215" height="380" controls>
                        <source src="videos/nuprizm.mp4" type="video/mp4">
                    </video>
                    <h3>Nuprizm</h3>
                    <p>This is a sample TikTok I made for Nuprizm of how I could promote Nuprizm's app features while 
                        presenting an article about a political event. If you want to watch more news content from 
                        Nuprizm, follow their Instagram or TikTok.
                    </p>
                </div>
                <div data-aos="fade-up" data-aos-duration="1000" class="video rundown">
                    <video width="215" height="380" controls>
                        <source src="videos/therundown.mp4" type="video/mp4">
                    </video>
                    <h3>The Rundown</h3>
                    <p>Here is a segment of mine as student news anchor at TheRundown. We cover a significant 
                        amount of stories, no matter how small, large or controversial they may be. To watch more 
                        segments, check us out on <a href="">Instagram.</a>
                    </p>
                </div>
            </div>
        </div>
    </div>

   

    <div id="contact">
        <h2 data-aos="fade-up" class="caption contact">Contact Me</h2>
            <div class="imageblock">
                <img src="images/portrait.jpg">
                <div class="contactbuttons">
                    <a href="mailto:oparajikenleonard.6145@gmail.com" target="_blank"><img data-aos="fade-up" data-aos-duration="1000" src="images/gmail.1024x1024.png"></a>
                    <a href="https://www.linkedin.com/in/kenleonard-oparaji/" target="_blank"><img data-aos="fade-up" data-aos-duration="1500" src="images/linkedin-original.1024x1024.png"></a>
                </div>
            </div>
    </div>


    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.js"></script>
    <script>
        $(document).ready(function(){
            $('#scrollingcontainer').slick({ 
            accessibility: true,
            autoplay: true,
            slidesToShow: 1,
            autoplaySpeed: 3000,
            slidesToScroll: 1,
        });
        });

    </script>
      <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
      <script>
        AOS.init();
      </script>
</body>

</html>
