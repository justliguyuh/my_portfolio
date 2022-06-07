# responsive-web-design
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta charset="utf-8" />
    <title>Personal Portfolio Webpage</title>
    <link
      rel="stylesheet"
      type="text/css"
      href="./PersonalPortfolioWebpageStyles.css"
    />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"
    />
  </head>
  <body>
    <header id="navbar">
      <nav id="nav-bar">
        <a href="#welcome-section">About</a>
        <a href="#projects">Work</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>
    <section id="welcome-section">
      <h1>Hey! I am Joy</h1>
      <p>an aspiring web developer</p>
    </section>
    <section id="projects">
      <h2>These are some of my projects</h2>
      <div class="divider"></div>
      <div class="project-tile">
        <a href="./Product Landing.html">
          <img src="./PICS/Product Landing.PNG" alt="Product Landing Page" />
          <p>Product Landing Page</p>
        </a>
        <a href="./Technical Documentation Page.html">
          <img
            src="./PICS/Technical Documentation Page.PNG"
            alt="Product Landing Page"
          />
          <p>Technical Documentation Page</p>
        </a>
        <a href="./Survey Form.html">
          <img src="./PICS/Survey Form.PNG" alt="Product Landing Page" />
          <p>Survey Form</p>
        </a>
        <a href="./Tribute.html">
          <img src="./PICS/Tribute Page.PNG" alt="Product Landing Page" />
          <p>Tribute Page</p>
        </a>
        <a href="./Magazine.html">
          <img src="./PICS/Magazine.PNG" alt="Product Landing Page" />
          <p>Magazine</p>
        </a>
        <a href="./City Skyline.html">
          <img src="./PICS/City Skyline.PNG" alt="Product Landing Page" />
          <p>City Skyline</p>
        </a>
      </div>
      <a class="show-all" href="./Cafe Menu.html"><button type="button">Show All ></button></a>
    </section>
    <section id="contact">
      <h1>Let's work together...</h1>
      <p id="contact-caption">How do you take your coffee?</p>
      <div id="my-contacts">
        <a id="profile-link" target="_blank" href="https://www.facebook.com/justliguyuh/">
          <i class="fab fa-facebook-square"></i>
          <p>Facebook</p>
        </a>
        <a id="profile-link" target="_blank" href="https://github.com/justliguyuh">
          <i class="fab fa-github"></i>
          <p>GitHub</p>
        </a>
        <a id="profile-link" target="_blank" href="https://twitter.com/justliguyuh">
          <i class="fab fa-twitter"></i>
          <p>Twitter</p>
        </a>
        <a id="profile-link" target="_blank" href="https://www.linkedin.com/in/joy-alecha-0b53b91aa/">
          <i class="fab fa-linkedin-in"></i>
          <p>LinkedIn</p>
        </a>
        <a id="profile-link" target="_blank" href="mailto: joy.alecha15@gmail.com">
          <i class="fa fa-at"></i>
          <p>Send an email</p>
        </a>
        <a id="profile-link" target="_blank" href="tel: 09294098863">
          <i class="fa fa-mobile"></i>
          <p>Call me</p>
        </a>
      </div>
      <hr />
      <footer>
        <p>**All the projects are lessons from freeCodeCamp I have taken.</p>
        <p>
          <i class="fa fa-copyright"></i> Created for freeCodeCamp (<i
            class="fa fa-fire"
          ></i
          >)
        </p>
      </footer>
    </section>
  </body>
</html>
