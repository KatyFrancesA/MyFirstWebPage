# MyFirstWebPage
Created using Career Foundry tutorial 

<!DOCTYPE html>
<html>
<head>
<title>First webpage</title>
<link rel="stylesheet" href="styles.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://fonts.googleapis.com/css?family=Noto+Sans|Roboto+Mono&display=swap" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="intro">
        <img class="profile-picture" src="images/profile-picture.jpg" />
        <h1>John Doe</h1>
        <h3>Aspiring web developer</h3>
        <p class="quote">
            "In a noisy world sometimes it pays to be quiet"
        </p> 
    </div>

   <hr/>

  <div class="about-grid">
    <div class="i-am">
        <h3> I am</h3>
        <ul>
            <li>An artist</li>
            <li>A aspiring web developer</li>
            <li>And a hobby cook</li>
        </ul> 
    </div>
    <div class="i-like">
        <h3>I like to</h3>
        <ul class="about-list">
            <li>Try new things</li>
            <li>Spend time with my boyfriend</li>
            <li>Watch comedies</li>
        </ul>
    </div>
  </div>

  <hr/>

    <div>
        <h3 class="projects-headings">My projects</h3>
     <div class="projects-grid">
      <div class="project-image-wrapper">
        <h4>Project 1</h4>
        <img class="project-image" src="images/project-1.jpg"/>
      </div>
      <div class="project-image-wrapper">
        <h4>Project 2</h4>
        <img class="project-image" src="images/project-2.jpg"/>
      </div>
      <div class="project-image-wrapper">
        <h4>Project 3</h4>
        <img class="project-image" src="images/project-3.jpg"/>
      </div>
      <div class="project-image-wrapper">
        <h4>Project 4</h4>
        <img class="project-image" src="images/project-4.jpg"/>
      </div>
     </div>
    </div>
    <div class="links-and-contact">
     <div class="links">
        <h3>Links</h3>
        <ul class="links-list">
            <li>
                <a href="https://github.com/<user>">Github</a>
            </li>
            <li>
                <a href="https://twitter.com/<user>">Twitter</a>
            </li>
            <li>
                <a href="https://linkedin.com/in/<user>">Linkedin</a>
            </li>
        </ul>
      </div>
    </div>
    <div>
        <form action="#">
            <label for="email">
                <h4>Email</h4>
				<input type="email" id="email" placeholder="Enter your email" />
            </label>
            <label for="message">
                <h4>Message</h4>
				<textarea id="message">Your Message</textarea>
            </label>
          <div class="submit-button-wrapper"> 
            <input class="submit-button" type="submit" value="Send Message" id="submit-button" />
          </div>   
        </form>
    </div>
</div>
<script src="script.js"></script>
</body>
</html>

//Images

![project-4](https://user-images.githubusercontent.com/94460351/202764498-82473b4f-805d-448f-8770-448458184d21.jpg)
![profile-picture](https://user-images.githubusercontent.com/94460351/202764505-f6c53c8f-8633-4b21-a4f8-b746b83a2b42.jpg)
![project-1](https://user-images.githubusercontent.com/94460351/202764506-df910f69-3775-479e-9af0-91f44ab03cc5.jpg)
![project-2](https://user-images.githubusercontent.com/94460351/202764508-1cff9790-4ae5-48bc-b969-f78bb8c9377f.jpg)
![project-3](https://user-images.githubusercontent.com/94460351/202764512-9a24ab47-f4d8-476b-918b-e931532dd379.jpg)
