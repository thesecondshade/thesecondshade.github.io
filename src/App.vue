<template>
  <div class="main-wrapper">
    <html lang="en">
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <meta name="description" content="">
        <meta name="author" content="">

        <title>Resume - Start Bootstrap Theme</title>

        <!-- Bootstrap core CSS -->
        <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">

        <!-- Custom fonts for this template -->
        <link href="https://fonts.googleapis.com/css?family=Saira+Extra+Condensed:500,700" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Muli:400,400i,800,800i" rel="stylesheet">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">
        <link href="vendor/fontawesome-free/css/all.min.css" rel="stylesheet">

        <!-- Custom styles for this template -->
        <link href="css/resume.min.css" rel="stylesheet">
        link href="https://fonts.googleapis.com/css?family=Saira+Extra+Condensed:100,200,300,400,500,600,700,800,900" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i,800,800i" rel="stylesheet">

        <!-- DevIcons -->
        <link rel="stylesheet" href="https://cdn.rawgit.com/konpa/devicon/df6431e323547add1b4cf45992913f15286456d3/devicon.min.css">
      </head>

      <body id="page-top">

        <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top" id="sideNav">
          <a class="navbar-brand js-scroll-trigger" href="#page-top">
            <span class="d-block d-lg-none">Victoria Pierce</span>
            <span class="d-none d-lg-block">
              <img  :src="image" class="img-fluid img-profile rounded-circle mx-auto mb-2">

            </span>
          </a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#about">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#experience">Experience</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#education">Education</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#skills">Skills</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#interests">Interests</a>
              </li>
              <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#awards">Awards</a>
              </li>
            </ul>
          </div>
        </nav>

        <div class="container-fluid p-0">

          <section class="resume-section p-3 p-lg-5 d-flex d-column" id="about">
            <div class="my-auto">
              <h1 class="mb-0">Victoria
                <span class="text-primary">Pierce</span>
              </h1>
              <div class="subheading mb-5">(651) 757-0505 ·
                <a href="mailto:victoria@piercefamily.name">victoria@piercefamily.name</a>
              </div>
              <p class="lead mb-5">Hello there! I am a Site-Reliability Engineer at SPS Commerce who is passionate about building things and helping narrow the gender gap in tech. I am 18 years old and I have 2 years left on a degree in Computer Science with a minor in Arabic at the University of Minnesota Twin Cities. </p>
              <div class="subheading mb-4">
                <a href="./src/Resume_VictoriaPierce.docx" download="Resume_VictoriaPierce">DOWNLOAD RESUME</a>
              </div>
              <div class="social-icons">
                <a href="https://www.linkedin.com/in/victoria-p-005718136/">
                  <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://github.com/thesecondshade">
                  <i class="fab fa-github"></i>
                </a>
                <a href="https://twitter.com/thesecondshade">
                  <i class="fab fa-twitter"></i>
                </a>
              </div>
            </div>
          </section>

          <hr class="m-0">

          <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="experience">
            <div class="my-auto">
              <h2 class="mb-5">Experience</h2>

              <div class="resume-item d-flex flex-column flex-md-row mb-5">
                <div class="resume-content mr-auto">
                  <h3 class="mb-0">Site Reliability Engineer Intern</h3>
                  <div class="subheading mb-3">SPS Commerce, Minneapolis, MN</div>
                  <li>Programming in Python, Ruby, Perl</li>
                  <li>Experience designing, building and maintaining AWS architectures</li>
                  <li>Experience working on a team of engineers utilizing Agile Development & Scrum</li>
                  <li>Monitoring written automation using LogicMonitor, SumoLogic, PagerDuty, and Cloudwatch</li>
                  <li>Writing automation that queries the APIs of LogicMonitor, Atlassian Software and PagerDuty</li>
                  <li>Implementing a company specific Build-Deploy-Pipeline using Cloudformation, AWS CLI and Jenkins</li>
                </div>
                <div class="resume-date text-md-right">
                  <span class="text-primary">June 2017 - Present</span>
                </div>
              </div>

              <div class="resume-item d-flex flex-column flex-md-row mb-5">
                <div class="resume-content mr-auto">
                  <h3 class="mb-0">Personal Care Assistant</h3>
                  <div class="subheading mb-3">Custom Care, Edina, MN</div>
                  <li>Take care of a young man with physical and mental disabilities</li>
                  <li>This young man needs assistance with pretty much ever part of life. I'd cook for him, feed him, walk behind him for support, read to him, play music to him, etc.</li>
                  <li>Physical and Occupational Therapy</li>

                </div>
                <div class="resume-date text-md-right">
                  <span class="text-primary">June 2016 - May 2017</span>
                </div>
              </div>

              <div class="resume-item d-flex flex-column flex-md-row">
                <div class="resume-content mr-auto">
                  <h3 class="mb-0">Music Teacher</h3>
                  <div class="subheading mb-3">Self-Employed, Jinja, Uganda</div>
                  <li>Taught Guitar in individual and group setting</li>
                  <li>Taught Violin to individuals</li>
                  <li>Taught Music Theory in individual and group setting</li>
                  <li>Helped coach and supervise children from the ages of 4-13 as they developed experience with and a love for music</li>

                </div>
                <div class="resume-date text-md-right">
                  <span class="text-primary">January 2014 - May 2015</span>
                </div>
              </div>

            </div>

          </section>

          <hr class="m-0">

          <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="education">
            <div class="my-auto">
              <h2 class="mb-5">College Classes</h2>

              <div class="resume-item d-flex flex-column flex-md-row mb-5">
                <div class="resume-content mr-auto">
                  <h3 class="mb-0">First-Year</h3>
                  <div class="subheading mb-3">University of Minnesota</div>
                  <li>CSCI 2021: Machine Architecture and Organization</li>
                  <li>CSCI 2041: Advanced Programming Principles</li>
                  <li>MATH 4242: Applied Linear Algebra</li>
                </div>
                <div class="resume-date text-md-right">
                  <span class="text-primary">August 2018 - December 2018</span>
                </div>
              </div>
              <hr>
              <h2 class="mb-5">High School Classes</h2>

              <div class="resume-item d-flex flex-column flex-md-row mb-5">
                <div class="resume-content mr-auto">
                  <h3 class="mb-0">Advanced Placement</h3>
                  <div class="subheading mb-3">Rosemount High School</div>
                  <li>Computer Science A (9th grade)</li>
                  <li>Calculus BC (11th grade)</li>
                  <li>Physics C: Mechanics (11th grade)</li>
                </div>
                <div class="resume-date text-md-right">
                  <span class="text-primary">August 2014 - May 2017</span>
                </div>
              </div>

              <div class="resume-item d-flex flex-column flex-md-row mb-5">
                <div class="resume-content mr-auto">
                  <h3 class="mb-0">College in Schools</h3>
                  <div class="subheading mb-3"><a href="https://www.inverhills.edu/DegreesAndPrograms/CollegeForHSStudents/InCollege.aspx">Inver Hill Community College</a></div>
                  <li>Data Structures and Algorithms (11th grade)</li>
                </div>
                <div class="resume-date text-md-right">
                  <span class="text-primary">August 2016 - May 2017</span>
                </div>
              </div>

              <div class="resume-item d-flex flex-column flex-md-row">
                <div class="resume-content mr-auto">
                  <h3 class="mb-0">Post-Secondary Enrollment Options</h3>
                  <div class="subheading mb-3"><a href="https://ccaps.umn.edu/post-secondary-enrollment-options-pseo">University of Minnesota</a></div>
                  <li>CSCI 2011: Discrete Structures of Computer Science (12th grade)</li>
                  <li>MATH 2243: Linear Algebra and Differential Equations (12th grade)</li>
                  <li>MATH 2263: Multivariable Calculus (12th grade)</li>
                </div>
                <div class="resume-date text-md-right">
                  <span class="text-primary">August 2017 - May 2018</span>
                </div>
              </div>

            </div>
          </section>

          <hr class="m-0">

          <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="skills">
            <div class="my-auto">
              <h2 class="mb-5">Skills</h2>

              <div class="subheading mb-3">Programming Languages &amp; Tools</div>
              <ul class="list-inline dev-icons">
                <li class="list-inline-item">
                  <i class="fab fa-npm"></i>
                </li>
                <li class="list-inline-item">
                  <i class="fab fa-python"></i>
                </li>
                <li class="list-inline-item">
                  <i class="fab fa-java"></i>
                </li>
                <li class="list-inline-item">
                  <i class="fab fa-js"></i>
                </li>
                <li class="list-inline-item">
                  <i class="devicon-c-plain"></i>
                </li>
                <li class="list-inline-item">
                  <i class="devicon-ruby-plain"></i>
                </li>
                <li class="list-inline-item">
                  <i class="fab fa-jenkins"></i>
                </li>
                <li class="list-inline-item">
                  <i class="fab fa-aws"></i>
                </li>
                <li class="list-inline-item">
                  <i class="fab fa-docker"></i>
                </li>
                <li class="list-inline-item">
                  <i class="fab fa-github"></i>
                </li>
                <li class="list-inline-item">
                  <i class="devicon-confluence-plain"></i>
                </li>
              </ul>
              <div class="subheading mb-2">Monitoring Tools</div>
              <ul class="fa-ul mb-0">
                <li>
                  PagerDuty</li>
                <li>
                  LogicMonitor</li>
                <li>
                  SumoLogic</li>
                <li>
                  AWS Cloudwatch Metrics</li>
              </ul>
            </div>
          </section>

          <hr class="m-0">

          <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="interests">
            <div class="my-auto">
              <h2 class="mb-5">Interests</h2>
              <p></p>
            </div>
          </section>

          <hr class="m-0">

          <section class="resume-section p-3 p-lg-5 d-flex flex-column" id="awards">
            <div class="my-auto">
              <h2 class="mb-5">Awards &amp; Achievements</h2>
              <ul class="fa-ul mb-0">
                <li>
                  <i class="fa-li fa fa-trophy text-warning"></i>
                  <a href="https://www.devopsdays.org/events/2017-madison/speakers/victoria-pierce/">DevOps Days Madison 2017</a> Speaker</li>
                <li>
                  <i class="fa-li fa fa-trophy text-warning"></i>
                  <a href="https://www.aspirations.org/">NCWIT Aspirations in Computing</a> 2017 Minnesota Affiliate Winner</li>
                <li>
                  <i class="fa-li fa fa-trophy text-warning"></i>
                  <a href="https://www.aspirations.org/">NCWIT Aspirations in Computing</a> 2018 National Runner Up</li>
              </ul>
            </div>
          </section>
        </div>

      </body>

    </html>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'My portfolio'
    }
  },
  mounted () {
    this.$nextTick(() => {
      // our custom jQuery code goes here
    })
  }
}
</script>

<script>
import LM from "./assets/LM.png"
export default {
    data: function () {
        return {
            LM: LM
        }
    }
}
</script>
<script>
import image from "./assets/img.jpg"
export default {
    data: function () {
        return {
            image: image
        }
    }
}
</script>

<style>
/*!
 * Start Bootstrap - Resume v5.0.1 (https://startbootstrap.com/template-overviews/resume)
 * Copyright 2013-2018 Start Bootstrap
 * Licensed under MIT (https://github.com/BlackrockDigital/startbootstrap-resume/blob/master/LICENSE)
 */

body {
  font-family: 'Muli', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  padding-top: 54px;
  color: #868e96;
}

@media (min-width: 992px) {
  body {
    padding-top: 0;
    padding-left: 17rem;
  }
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Saira Extra Condensed', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  font-weight: 700;
  text-transform: uppercase;
  color: #343a40;
}

h1 {
  font-size: 6rem;
  line-height: 5.5rem;
}

h2 {
  font-size: 3.5rem;
}

h3 {
  font-size: 2rem;
}

p.lead {
  font-size: 1.15rem;
  font-weight: 400;
}

.subheading {
  text-transform: uppercase;
  font-weight: 500;
  font-family: 'Saira Extra Condensed', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  font-size: 1.5rem;
}

.social-icons a {
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: #495057;
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: #1f88a8;
}

.dev-icons {
  font-size: 3rem;
}

.dev-icons .list-inline-item i:hover {
  color: #1f88a8;
}

#sideNav .navbar-nav .nav-item .nav-link {
  font-weight: 800;
  letter-spacing: 0.05rem;
  text-transform: uppercase;
}

#sideNav .navbar-toggler:focus {
  outline-color: #d48a6e;
}

@media (min-width: 992px) {
  #sideNav {
    text-align: center;
    position: fixed;
    top: 0;
    left: 0;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 17rem;
    height: 100vh;
  }
  #sideNav .navbar-brand {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin: auto auto 0;
    padding: 0.5rem;
  }
  #sideNav .navbar-brand .img-profile {
    max-width: 10rem;
    max-height: 10rem;
    border: 0.5rem solid rgba(255, 255, 255, 0.2);
  }
  #sideNav .navbar-collapse {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: start;
    -ms-flex-align: start;
    align-items: flex-start;
    -webkit-box-flex: 0;
    -ms-flex-positive: 0;
    flex-grow: 0;
    width: 100%;
    margin-bottom: auto;
  }
  #sideNav .navbar-collapse .navbar-nav {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 100%;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item {
    display: block;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item .nav-link {
    display: block;
  }
}

section.resume-section {
  padding-top: 5rem !important;
  padding-bottom: 5rem !important;
  max-width: 75rem;
}

section.resume-section .resume-item .resume-date {
  min-width: none;
}

@media (min-width: 768px) {
  section.resume-section {
    min-height: 100vh;
  }
  section.resume-section .resume-item .resume-date {
    min-width: 18rem;
  }
}

@media (min-width: 992px) {
  section.resume-section {
    padding-top: 3rem !important;
    padding-bottom: 3rem !important;
  }
}

.bg-primary {
  background-color: #1f88a8 !important;
}

.text-primary {
  color: #1f88a8 !important;
}

.text-location {
  color: #1f88a8 !important;
}

a {
  color: #1f88a8;
}

a:hover, a:focus, a:active {
  color: #824027;
}
</style>
