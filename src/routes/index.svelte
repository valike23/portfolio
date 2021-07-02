<script>
  import successkid from "images/successkid.jpg";
</script>

<svelte:head>
  <link href="css/style.css" rel="stylesheet" />

  <script defer src="js/custom.js"></script>
  <title>Valentine Emmanuel Portfolio App</title>
</svelte:head>

<div id="preloader">
  <div id="status">
    <div
      class="preloader"
      aria-busy="true"
      aria-label="Loading, please wait."
      role="progressbar"
    />
  </div>
</div>
<!-- ./Preloader -->

<!-- header -->
<!-- <header> -->
<header>
  <nav class="navbar-fixed-top navbar navbar-expand-lg navbar-light fixed-top">
    <a class="navbar-brand" href="#"
      ><img src="img/favicon.ico" class="logo" alt="logo" /></a
    >

 <a class="text-truncate" href="tel:07040206876">call: 07040206876</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#nav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav m-0 ml-lg-auto p-3 p-lg-0">
        <li class="d-inline d-lg-none">
          <button
            data-toggle="collapse"
            data-target="#nav"
            class="close float-right">&times;</button
          >
        </li>
        <li class="nav-item">
          <a class="nav-link text-truncate" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-truncate" href="#experience">experience</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-truncate" href="#notable_projects">projects</a
          >
        </li>
        <li class="nav-item">
          <a class="nav-link text-truncate" href="#contact">contact</a>
        </li>
        <!-- <li class="nav-item">
					<a class="nav-link text-truncate" href="##">Link</a>
				</li> -->
      </ul>
    </div>
  </nav>
</header>
<!-- ./header -->

<div orientation="left" class="sideElement inTouch">
  <ul class="social__StyledSocialList-anu6nt-0 sList fade-enter-done">
    <li>
      <a href="https://github.com/valike23" aria-label="GitHub">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          role="img"
          viewBox="0 0 438.549 438.549"
        >
          <title>GitHub</title>
          <path
            d="M409.132,114.573c-19.608-33.596-46.205-60.194-79.798-79.8C295.736,15.166,259.057,5.365,219.271,5.365 c-39.781,0-76.472,9.804-110.063,29.408c-33.596,19.605-60.192,46.204-79.8,79.8C9.803,148.168,0,184.854,0,224.63 c0,47.78,13.94,90.745,41.827,128.906c27.884,38.164,63.906,64.572,108.063,79.227c5.14,0.954,8.945,0.283,11.419-1.996 c2.475-2.282,3.711-5.14,3.711-8.562c0-0.571-0.049-5.708-0.144-15.417c-0.098-9.709-0.144-18.179-0.144-25.406l-6.567,1.136 c-4.187,0.767-9.469,1.092-15.846,1c-6.374-0.089-12.991-0.757-19.842-1.999c-6.854-1.231-13.229-4.086-19.13-8.559 c-5.898-4.473-10.085-10.328-12.56-17.556l-2.855-6.57c-1.903-4.374-4.899-9.233-8.992-14.559 c-4.093-5.331-8.232-8.945-12.419-10.848l-1.999-1.431c-1.332-0.951-2.568-2.098-3.711-3.429c-1.142-1.331-1.997-2.663-2.568-3.997 c-0.572-1.335-0.098-2.43,1.427-3.289c1.525-0.859,4.281-1.276,8.28-1.276l5.708,0.853c3.807,0.763,8.516,3.042,14.133,6.851 c5.614,3.806,10.229,8.754,13.846,14.842c4.38,7.806,9.657,13.754,15.846,17.847c6.184,4.093,12.419,6.136,18.699,6.136 c6.28,0,11.704-0.476,16.274-1.423c4.565-0.952,8.848-2.383,12.847-4.285c1.713-12.758,6.377-22.559,13.988-29.41 c-10.848-1.14-20.601-2.857-29.264-5.14c-8.658-2.286-17.605-5.996-26.835-11.14c-9.235-5.137-16.896-11.516-22.985-19.126 c-6.09-7.614-11.088-17.61-14.987-29.979c-3.901-12.374-5.852-26.648-5.852-42.826c0-23.035,7.52-42.637,22.557-58.817 c-7.044-17.318-6.379-36.732,1.997-58.24c5.52-1.715,13.706-0.428,24.554,3.853c10.85,4.283,18.794,7.952,23.84,10.994 c5.046,3.041,9.089,5.618,12.135,7.708c17.705-4.947,35.976-7.421,54.818-7.421s37.117,2.474,54.823,7.421l10.849-6.849 c7.419-4.57,16.18-8.758,26.262-12.565c10.088-3.805,17.802-4.853,23.134-3.138c8.562,21.509,9.325,40.922,2.279,58.24 c15.036,16.18,22.559,35.787,22.559,58.817c0,16.178-1.958,30.497-5.853,42.966c-3.9,12.471-8.941,22.457-15.125,29.979 c-6.191,7.521-13.901,13.85-23.131,18.986c-9.232,5.14-18.182,8.85-26.84,11.136c-8.662,2.286-18.415,4.004-29.263,5.146 c9.894,8.562,14.842,22.077,14.842,40.539v60.237c0,3.422,1.19,6.279,3.572,8.562c2.379,2.279,6.136,2.95,11.276,1.995 c44.163-14.653,80.185-41.062,108.068-79.226c27.88-38.161,41.825-81.126,41.825-128.906 C438.536,184.851,428.728,148.168,409.132,114.573z"
          />
        </svg>
      </a>
    </li>
    <li>
      <a
        href="https://www.linkedin.com/in/valentine-emmanuel-a40a40167/"
        aria-label="Linkedin"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          role="img"
          viewBox="0 0 430.117 430.117"
        >
          <title>LinkedIn</title>
          <path
            d="M430.117,261.543V420.56h-92.188V272.193c0-37.271-13.334-62.707-46.703-62.707 c-25.473,0-40.632,17.142-47.301,33.724c-2.432,5.928-3.058,14.179-3.058,22.477V420.56h-92.219c0,0,1.242-251.285,0-277.32h92.21 v39.309c-0.187,0.294-0.43,0.611-0.606,0.896h0.606v-0.896c12.251-18.869,34.13-45.824,83.102-45.824 C384.633,136.724,430.117,176.361,430.117,261.543z M52.183,9.558C20.635,9.558,0,30.251,0,57.463 c0,26.619,20.038,47.94,50.959,47.94h0.616c32.159,0,52.159-21.317,52.159-47.94C103.128,30.251,83.734,9.558,52.183,9.558z M5.477,420.56h92.184v-277.32H5.477V420.56z"
          />
        </svg></a
      >
    </li>

    <li>
      <a href="https://twitter.com/Mind_Init" aria-label="Twitter"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          role="img"
          viewBox="0 0 612 612"
        >
          <title>Twitter</title>
          <path
            d="M612,116.258c-22.525,9.981-46.694,16.75-72.088,19.772c25.929-15.527,45.777-40.155,55.184-69.411 c-24.322,14.379-51.169,24.82-79.775,30.48c-22.907-24.437-55.49-39.658-91.63-39.658c-69.334,0-125.551,56.217-125.551,125.513 c0,9.828,1.109,19.427,3.251,28.606C197.065,206.32,104.556,156.337,42.641,80.386c-10.823,18.51-16.98,40.078-16.98,63.101 c0,43.559,22.181,81.993,55.835,104.479c-20.575-0.688-39.926-6.348-56.867-15.756v1.568c0,60.806,43.291,111.554,100.693,123.104 c-10.517,2.83-21.607,4.398-33.08,4.398c-8.107,0-15.947-0.803-23.634-2.333c15.985,49.907,62.336,86.199,117.253,87.194 c-42.947,33.654-97.099,53.655-155.916,53.655c-10.134,0-20.116-0.612-29.944-1.721c55.567,35.681,121.536,56.485,192.438,56.485 c230.948,0,357.188-191.291,357.188-357.188l-0.421-16.253C573.872,163.526,595.211,141.422,612,116.258z"
          />
        </svg>
      </a>
    </li>
  </ul>
</div>

<!-- home -->
<div class="section" id="home" data-stellar-background-ratio="0.5">
  <div class="container">
    <div class="disply-table">
      <div class="table-cell" data-aos="fade-up" data-aos-delay="0">
        <h1>Valentine<br />Emmanuel</h1>
        <h4>MESN Stack Developer</h4>
        <h4>Mobile Developer</h4>
        <h4>.Net Developer</h4>
      </div>
    </div>
  </div>
</div>
<!-- ./home -->

<!-- about -->
<div class="section" id="about">
  <div class="container">
    <div class="row">
      <div class="col-lg-6 col-md-4 col-sm-6" data-aos="fade-up">
        <h4>01</h4>
        <h1 class="size-50">Know <br /> About me</h1>
        <div class="h-10" />
        <p>
         I am a full stack developer with over 6 years exprience using over 6 programming
		 languages and over 20 frameworks. I graduated from the university of Benin in
      2017 where is studied computer science,
     since then I have worked in multiple companies where my roles revolves around
     development of .NET application to developement of MESN stack application.
     <br>
      I love innovative solution and rigged highly functional
		 applications.I also adhere to SOLID principles while developing
      and also developing solutions in a decoupled manner , I love learning new technologies,
     solving challenging problems and working with a team. Also love teaching young people 
     how to code.
        </p>
       
        <div class="h-20" />
        <img src="img/Signature.svg" width="230" alt="" />
        <div class="h-50" />
      </div>
      <div class="col-lg-6 col-md-4 col-sm-6 about-img-div">
        <div class="has-overlay">
          <div
            class="team-member-photo css-image-object"
            align="right"
            data-aos="fade-right"
            data-aos-delay="0"
            style="background-image: url(./img/user.jpg); width: 400px; height: 500px;"
          />
          <div class="the-overlay __gradient-team-member" />
          <div class="about-border" data-aos="fade-up" data-aos-delay=".5" />
        </div>
      </div>
    </div>
  </div>
</div>
<!-- ./about -->

<!-- experience  -->
<div class="section" id="experience">
  <div class="container">
    <div class="col-md-12">
      <h4>02</h4>
      <h1 class="size-50">My <br /> Experience</h1>
      <div class="h-50" />
    </div>
    <div class="col-md-12">
      <ul class="timeline">
        <li class="timeline-event" data-aos="fade-up">
          <label class="timeline-event-icon" />
          <div class="timeline-event-copy">
            <p class="timeline-event-thumbnail">December 2018 - Present</p>
            <h3>Full Stack Developer / .NET Developer</h3>
            <h4>Full Time</h4>
            <p>
              <strong>Telnet Nigeria Limited</strong>
              <br />Telnet is a digital transformation company. Telnet is driven
              by the desire to provide technological solutions that accelerate
              national development, leveraging it for commercial advantage.
            </p>
            <button data-toggle="collapse" class="moreBtn" data-target="#telnet"
              >View more</button
            >
            <div id="telnet" class="collapse">
              <ul class="work">
                <li class="justify-content-between align-items-center">
                 Analysis system requiremnet document and construct system design diagrams such as
                 sequence diagram, use case diagram etc.
                </li>
                <li class="justify-content-between align-items-center">
                 Design of windows services to automate system processes of some of our top solution such as
                 autoswift, JTB integration etc.
                </li>
                <li class="justify-content-between align-items-center">
                  Developing .NET based Applications integrating Ado.net framework to work with SQL Server databases
                </li>
                <li class="justify-content-between align-items-center">
                  Work with a variety of different languages, platforms,
                  frameworks, and content management systems such as JavaScript,
                  TypeScript, Angular, svelte, and Heroku
                </li>
                <li class="justify-content-between align-items-center">
                  Write modern, performant, maintainable code for a diverse
                  array of client and internal projects
                </li>
             
              </ul>
            </div>
          </div>
        </li>
        <li class="timeline-event" data-aos="fade-up" data-aos-delay=".2">
          <label class="timeline-event-icon" />
          <div class="timeline-event-copy">
            <p class="timeline-event-thumbnail">May 2020 – Present</p>
            <h3>CTO</h3>
            <h4>Part Time</h4>
            <p>
              <strong>Trigga Technologies</strong>
              <br />We are a team of trendy tech enthusiasts
               and brand strategists seeking to influence your life by offering you ‘SOLUTIONS THAT EMPOWER’.
            </p>
            <button
              data-toggle="collapse"
              class="moreBtn"
              data-target="#relearn">View more</button
            >
            <div id="relearn" class="collapse">
              <ul class="work">
                <li class="justify-content-between align-items-center">
                  Created, Oversaw and Delivered Science Factory on- and
                  off-site educational programming, hands-on activities, and
                  STEM resources for grades Pre-K through 8
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="timeline-event" data-aos="fade-up" data-aos-delay=".4">
          <label class="timeline-event-icon" />
          <div class="timeline-event-copy">
            <p class="timeline-event-thumbnail">December 2018 – Present</p>
            <h3>Software Developer</h3>
            <h4>Freelance</h4>
            <p>
              <strong>Mind Initiatives</strong>
              <br />Mind Initiatives is an Information technology Consulting
              Services startup that specializes in delivering technological
              solutions to meet the needs of their clients by providing holistic
              business solutions for improved overall business performance.
            </p>
            <button data-toggle="collapse" class="moreBtn" data-target="#mind"
              >View more</button
            >
            <div id="mind" class="collapse">
              <ul class="work">
                <li class="justify-content-between align-items-center">
                  Engineered and maintained major features of SoftEntry Visitors
                  and Guest Management web app using Angular, Node, Express,
                  MongoDB and SCSS
                </li>
                <li class="justify-content-between align-items-center">
                  Architected and Implemented the Front end of the CourierStack
                  Mobile App for Automation of Courier Services
                </li>
                <li class="justify-content-between align-items-center">
                  implemented the front-end of TAPPS Agent Web App, which lets
                  tax payers be able to pay tax at their convenience with an
                  Agent Close to them
                </li>
                <li class="justify-content-between align-items-center">
                  built a marketing website and e-commerce platform for
                  Olamstech, an ambitious tech startup originating from Lee,
                  United Kingdom
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="timeline-event" data-aos="fade-up" data-aos-delay=".6">
          <label class="timeline-event-icon" />
          <div class="timeline-event-copy">
            <p class="timeline-event-thumbnail">February 2018</p>
            <h3>Code tutor</h3>
            <h4>Freelance</h4>
            <p>
              <strong>Orbit Digital Learning Centre</strong>
              <br />Orbit Digital Learning Centre is a training centre that
              offers quality training, serving students across Lagos, Nigeria.
            </p>
            <button data-toggle="collapse" class="moreBtn" data-target="#orbit"
              >View more</button
            >
            <div id="orbit" class="collapse">
              <ul class="work">
                <li class="justify-content-between align-items-center">
                  Developed and taught specific computer science curriculum to
                  students with various classes that entailed game programming,
                  app programming, logic and critical thinking. While making the
                  Courses developmentally appropriate and engaging.
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="timeline-event" data-aos="fade-up" data-aos-delay=".8">
          <label class="timeline-event-icon" />
          <div class="timeline-event-copy">
            <p class="timeline-event-thumbnail">April 2016 - December 2017</p>
            <h3>Assistant IT Support Analyst</h3>
            <h4>Volunteer</h4>
            <p>
              <strong>Lasena Water</strong>
              <br />Lasena Water is a Water Producing Company which offers the
              first Artesian water in Nigeria.
            </p>
            <button data-toggle="collapse" class="moreBtn" data-target="#lasena"
              >View more</button
            >
            <div id="lasena" class="collapse">
              <ul class="work">
                <li class="justify-content-between align-items-center">
                  Installed and configured computer software, hardware,
                  operating system, Applications and networks to suit the
                  company’s unique needs
                </li>
                <li class="justify-content-between align-items-center">
                  Set up peripherals like printers, keyboards, routers, modems,
                  and smart devices and ensure that they are functional and
                  secure.
                </li>
                <li class="justify-content-between align-items-center">
                  Maintained and Managed the Company’s website.
                </li>
              </ul>
            </div>
          </div>
        </li>
        <li class="timeline-event" data-aos="fade-up" data-aos-delay=".10">
          <label class="timeline-event-icon" />
          <div class="timeline-event-copy">
            <p class="timeline-event-thumbnail">March 2012 - February 2017</p>
            <h3>Systems Engineer</h3>
            <h4>Contract</h4>
            <p>
              <strong>Skynet InfoTech & Engineering system</strong>
              <br />Skynet InfoTech is a group of security professionals with
              over fifteen (15) years of combined experience.
            </p>
            <button data-toggle="collapse" class="moreBtn" data-target="#skynet"
              >View more</button
            >
            <div id="skynet" class="collapse">
              <ul class="work">
                <li class="justify-content-between align-items-center">
                  Managed and monitored all installed systems and infrastructure
                  of clients
                </li>
                <li class="justify-content-between align-items-center">
                  Installed, configured, tested and maintained operating
                  systems, application software and system management tools for
                  client
                </li>
              </ul>
            </div>
          </div>
        </li>

        <li class="timeline-event" data-aos="fade-up" data-aos-delay=".12">
          <label class="timeline-event-icon" />
          <div class="timeline-event-copy">
            <p class="timeline-event-thumbnail">July 2012 - June 2013</p>
            <h3>Computer Operator</h3>
            <h4>Full Time</h4>
            <p>
              <strong
                >Celline Services Nigeria Limited (Celline Café Plus)</strong
              >
              <br />Celline Café Plus is a cyber cafe and Business centre in
              Mainland, Lagos offering computer training and cyber café
              services.
            </p>
            <button
              data-toggle="collapse"
              class="moreBtn"
              data-target="#celline">View more</button
            >
            <div id="celline" class="collapse">
              <ul class="work">
                <li class="justify-content-between align-items-center">
                  Operated spreadsheet programs and other types of software to
                  load and manipulate data and to produce reports.
                </li>
                <li class="justify-content-between align-items-center">
                  Read job set-up instructions to determine equipment to be
                  used, order of use, material such as disks and paper to be
                  loaded, and control settings.
                </li>
                <li class="justify-content-between align-items-center">
                  Oversaw the operation of computer hardware systems, including
                  coordinating and scheduling the use of computer terminals and
                  networks to ensure efficient use.
                </li>
              </ul>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</div>
<!-- ./experience -->

<!--notable projects-->
<div class="section" id="notable_projects">
  <div class="container">
    <div class="col-md-12">
      <h4>03</h4>
      <h1 class="size-50">Some Things i've Built</h1>
      <div class="h-50" />
    </div>
    <div class="col-md-12">
      <div
        class="main-project"
        style="visibility: visible; opacity: 1; transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transition: opacity 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0s, transform 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0s;"
      >
        <div class="project-content">
          <p class="project-overline">Featured Project</p>
          <h3 class="project-title">Lexerati</h3>
          <div class="project-description">
            <p>
              An Easy directory system for global law related matters. Find law
              cases, statuses, and news across te legal world.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Node.js</li>
            <li>ejs</li>
            <li>MySQL</li>
            <li>Express.js</li>
            <li>MongoDB</li>
            <li>Angularjs</li>
          </ul>
          <div class="project-links">
            <a
              href="https://github.com/valike23/lexerati"
              aria-label="GitHub Link"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                role="img"
                viewBox="0 0 438.549 438.549"
              >
                <title>GitHub</title>
                <path
                  d="M409.132,114.573c-19.608-33.596-46.205-60.194-79.798-79.8C295.736,15.166,259.057,5.365,219.271,5.365 c-39.781,0-76.472,9.804-110.063,29.408c-33.596,19.605-60.192,46.204-79.8,79.8C9.803,148.168,0,184.854,0,224.63 c0,47.78,13.94,90.745,41.827,128.906c27.884,38.164,63.906,64.572,108.063,79.227c5.14,0.954,8.945,0.283,11.419-1.996 c2.475-2.282,3.711-5.14,3.711-8.562c0-0.571-0.049-5.708-0.144-15.417c-0.098-9.709-0.144-18.179-0.144-25.406l-6.567,1.136 c-4.187,0.767-9.469,1.092-15.846,1c-6.374-0.089-12.991-0.757-19.842-1.999c-6.854-1.231-13.229-4.086-19.13-8.559 c-5.898-4.473-10.085-10.328-12.56-17.556l-2.855-6.57c-1.903-4.374-4.899-9.233-8.992-14.559 c-4.093-5.331-8.232-8.945-12.419-10.848l-1.999-1.431c-1.332-0.951-2.568-2.098-3.711-3.429c-1.142-1.331-1.997-2.663-2.568-3.997 c-0.572-1.335-0.098-2.43,1.427-3.289c1.525-0.859,4.281-1.276,8.28-1.276l5.708,0.853c3.807,0.763,8.516,3.042,14.133,6.851 c5.614,3.806,10.229,8.754,13.846,14.842c4.38,7.806,9.657,13.754,15.846,17.847c6.184,4.093,12.419,6.136,18.699,6.136 c6.28,0,11.704-0.476,16.274-1.423c4.565-0.952,8.848-2.383,12.847-4.285c1.713-12.758,6.377-22.559,13.988-29.41 c-10.848-1.14-20.601-2.857-29.264-5.14c-8.658-2.286-17.605-5.996-26.835-11.14c-9.235-5.137-16.896-11.516-22.985-19.126 c-6.09-7.614-11.088-17.61-14.987-29.979c-3.901-12.374-5.852-26.648-5.852-42.826c0-23.035,7.52-42.637,22.557-58.817 c-7.044-17.318-6.379-36.732,1.997-58.24c5.52-1.715,13.706-0.428,24.554,3.853c10.85,4.283,18.794,7.952,23.84,10.994 c5.046,3.041,9.089,5.618,12.135,7.708c17.705-4.947,35.976-7.421,54.818-7.421s37.117,2.474,54.823,7.421l10.849-6.849 c7.419-4.57,16.18-8.758,26.262-12.565c10.088-3.805,17.802-4.853,23.134-3.138c8.562,21.509,9.325,40.922,2.279,58.24 c15.036,16.18,22.559,35.787,22.559,58.817c0,16.178-1.958,30.497-5.853,42.966c-3.9,12.471-8.941,22.457-15.125,29.979 c-6.191,7.521-13.901,13.85-23.131,18.986c-9.232,5.14-18.182,8.85-26.84,11.136c-8.662,2.286-18.415,4.004-29.263,5.146 c9.894,8.562,14.842,22.077,14.842,40.539v60.237c0,3.422,1.19,6.279,3.572,8.562c2.379,2.279,6.136,2.95,11.276,1.995 c44.163-14.653,80.185-41.062,108.068-79.226c27.88-38.161,41.825-81.126,41.825-128.906 C438.536,184.851,428.728,148.168,409.132,114.573z"
                />
              </svg></a
            ><a
              href="https://lexerati.herokuapp.com/"
              aria-label="External Link"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                role="img"
                viewBox="0 0 194.818 194.818"
              >
                <title>External</title>
                <g>
                  <path
                    d="M185.818,2.161h-57.04c-4.971,0-9,4.029-9,9s4.029,9,9,9h35.312l-86.3,86.3c-3.515,3.515-3.515,9.213,0,12.728 c1.758,1.757,4.061,2.636,6.364,2.636s4.606-0.879,6.364-2.636l86.3-86.3v35.313c0,4.971,4.029,9,9,9s9-4.029,9-9v-57.04 C194.818,6.19,190.789,2.161,185.818,2.161z"
                  />
                  <path
                    d="M149,77.201c-4.971,0-9,4.029-9,9v88.456H18v-122h93.778c4.971,0,9-4.029,9-9s-4.029-9-9-9H9c-4.971,0-9,4.029-9,9v140 c0,4.971,4.029,9,9,9h140c4.971,0,9-4.029,9-9V86.201C158,81.23,153.971,77.201,149,77.201z"
                  />
                </g>
              </svg></a
            >
          </div>
        </div>
        <div class="project-image">
          <a href="https://lexerati.herokuapp.com/">
            <div
              class="img gatsby-image-wrapper"
              style="position: relative; overflow: hidden;"
            >
              <div
                aria-hidden="true"
                style="width: 100%; padding-bottom: 62.2857%;"
              />
              <img
                aria-hidden="true"
                src="data:image/svg+xml,%3csvg%20xmlns='http://www.w3.org/2000/svg'%20width='400'%20height='250'%20viewBox='0%200%20400%20250'%20preserveAspectRatio='none'%3e%3cpath%20d='M0%2080v80h47c2%200%203%200%203-9l1-10h94v20h8v-10l1-10h93v10l1%2010h7v-10l1-10h94v9l1%2010h24l25-1%201-80V0H0v80m192-64c-8%204-11%2014-7%2022%202%204%201%204%207%200%205-4%205-4%205%203-1%207%200%207%204%207l4-1-1-7%201-7%201%202%203%204c5%201%205%201%206-2%207-14-10-29-23-21m95%20171c0%206%200%206%203%206%206%202%2010%209%208%2015l-1%203%205%203%205%203%201-2c2-3%202-13%201-17-3-9-10-15-19-16l-3-1v6m-222%202c-3%203-6%208-6%2010s21%207%2022%206l-13-18c0-1-2%200-3%202m13%2019c-12%2014-13%2016-4%2018%207%203%2015%202%2020-2l2-2-7-8-7-9-4%203'%20fill='%2364ffda'%20fill-rule='evenodd'/%3e%3c/svg%3e"
                alt=""
                style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; object-fit: cover; object-position: center center; opacity: 0; transition-delay: 500ms;"
              />
              <img
                src="img/lexerati.png"
                alt="SoftEntry"
                loading="lazy"
                style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; object-fit: cover; object-position: center center; opacity: 1; transition: opacity 500ms ease 0s;"
              />
            </div>
          </a>
        </div>
      </div>
      <div
        class="main-project"
        style="visibility: visible; opacity: 1; transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transition: opacity 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0s, transform 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0s;"
      >
        <div class="project-content">
          <p class="project-overline">Featured Project</p>
          <h3 class="project-title">CourierStack UI</h3>
          <div class="project-description">
            <p>
              A mobile application for Automating Couriers' Logisitics
              processes. with Features including Selection of a preferred
              Courier, Delivery, Rate Courier, Track Orders and others.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Adobe XD</li>
            <li>Java</li>
            <li>Android SDK</li>
          </ul>
          <div class="project-links">
            <a
              href="https://dribbble.com/Mo_Init/courier-stack"
              aria-label="Dribbble Link"
            >
              <svg
                version="1.1"
                id="Capa_1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                x="0px"
                y="0px"
                viewBox="0 0 300 300"
                style="enable-background:new 0 0 300 300;"
                xml:space="preserve"
              >
                <path
                  d="M261.579,49.864l-2.106-2.294C232.082,18.315,193.143,0,150,0c-17.166,0-33.664,2.907-49.038,8.24L99.4,8.791
C49.188,26.839,11.303,70.949,2.14,124.729c-0.011,0.051-0.027,0.1-0.037,0.151c-0.033,0.171-0.046,0.341-0.073,0.512
C0.702,133.402,0,141.62,0,150c0,35.76,12.586,68.632,33.551,94.435c0.01,0.015,1.746,2.109,1.746,2.109
C62.835,279.208,104.032,300,150,300c17.371,0,34.058-2.978,49.588-8.434c0.409-0.126,0.811-0.266,1.204-0.425
c49.269-17.785,86.632-60.673,96.577-113.148c0.026-0.128,0.052-0.255,0.074-0.383C299.115,168.657,300,159.431,300,150
C300,111.55,285.452,76.438,261.579,49.864z M150,30c30.85,0,59.016,11.705,80.297,30.903
c-14.903,20.417-35.74,33.843-58.563,42.503c-3.805-8.884-7.605-16.936-11.248-24.113c-10.561-20.802-20.929-36.741-29.015-47.862
C137.513,30.491,143.699,30,150,30z M100.736,40.584c8.947,11.182,25.92,34.926,41.948,71.28
c-42.085,9.028-85.24,6.035-107.548,3.387C45.228,81.96,69.419,54.74,100.736,40.584z M30,150c0-1.705,0.045-3.399,0.115-5.087
c11.955,1.495,29.682,3.118,50.351,3.118c10.008,0,20.708-0.381,31.766-1.341c14.739-1.28,28.634-3.492,41.664-6.579
c2.865,8.065,5.62,16.579,8.2,25.56c-13.517,3.932-27.477,8.844-41.867,14.745c-31.025,12.72-56.322,26.958-70.444,35.512
C37.287,196.993,30,174.333,30,150z M150,270c-30.873,0-59.058-11.722-80.345-30.946c20.018-11.762,57.599-31.811,99.783-44.21
c4.703,21.642,8.265,45.477,10.066,71.482C170.063,268.722,160.178,270,150,270z M208.678,254.641
c-2.107-24.185-5.666-46.483-10.127-66.84c22.086-4.117,44.601-5.342,65.867-1.608C255.15,215.425,234.968,239.841,208.678,254.641z
 M269.811,156.67c-23.811-4.235-50.07-3.583-78.585,1.922c-2.736-9.632-5.644-18.711-8.64-27.251
c28.155-10.772,50.939-26.637,67.658-47.223C262.725,103.042,270,125.686,270,150C270,152.238,269.934,154.461,269.811,156.67z"
                />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
                <g />
              </svg>
              <!-- <svg xmlns="http://www.w3.org/2000/svg" role="img"
							viewBox="0 0 438.549 438.549">
							<title>GitHub</title>
							<path
								d="M409.132,114.573c-19.608-33.596-46.205-60.194-79.798-79.8C295.736,15.166,259.057,5.365,219.271,5.365 c-39.781,0-76.472,9.804-110.063,29.408c-33.596,19.605-60.192,46.204-79.8,79.8C9.803,148.168,0,184.854,0,224.63 c0,47.78,13.94,90.745,41.827,128.906c27.884,38.164,63.906,64.572,108.063,79.227c5.14,0.954,8.945,0.283,11.419-1.996 c2.475-2.282,3.711-5.14,3.711-8.562c0-0.571-0.049-5.708-0.144-15.417c-0.098-9.709-0.144-18.179-0.144-25.406l-6.567,1.136 c-4.187,0.767-9.469,1.092-15.846,1c-6.374-0.089-12.991-0.757-19.842-1.999c-6.854-1.231-13.229-4.086-19.13-8.559 c-5.898-4.473-10.085-10.328-12.56-17.556l-2.855-6.57c-1.903-4.374-4.899-9.233-8.992-14.559 c-4.093-5.331-8.232-8.945-12.419-10.848l-1.999-1.431c-1.332-0.951-2.568-2.098-3.711-3.429c-1.142-1.331-1.997-2.663-2.568-3.997 c-0.572-1.335-0.098-2.43,1.427-3.289c1.525-0.859,4.281-1.276,8.28-1.276l5.708,0.853c3.807,0.763,8.516,3.042,14.133,6.851 c5.614,3.806,10.229,8.754,13.846,14.842c4.38,7.806,9.657,13.754,15.846,17.847c6.184,4.093,12.419,6.136,18.699,6.136 c6.28,0,11.704-0.476,16.274-1.423c4.565-0.952,8.848-2.383,12.847-4.285c1.713-12.758,6.377-22.559,13.988-29.41 c-10.848-1.14-20.601-2.857-29.264-5.14c-8.658-2.286-17.605-5.996-26.835-11.14c-9.235-5.137-16.896-11.516-22.985-19.126 c-6.09-7.614-11.088-17.61-14.987-29.979c-3.901-12.374-5.852-26.648-5.852-42.826c0-23.035,7.52-42.637,22.557-58.817 c-7.044-17.318-6.379-36.732,1.997-58.24c5.52-1.715,13.706-0.428,24.554,3.853c10.85,4.283,18.794,7.952,23.84,10.994 c5.046,3.041,9.089,5.618,12.135,7.708c17.705-4.947,35.976-7.421,54.818-7.421s37.117,2.474,54.823,7.421l10.849-6.849 c7.419-4.57,16.18-8.758,26.262-12.565c10.088-3.805,17.802-4.853,23.134-3.138c8.562,21.509,9.325,40.922,2.279,58.24 c15.036,16.18,22.559,35.787,22.559,58.817c0,16.178-1.958,30.497-5.853,42.966c-3.9,12.471-8.941,22.457-15.125,29.979 c-6.191,7.521-13.901,13.85-23.131,18.986c-9.232,5.14-18.182,8.85-26.84,11.136c-8.662,2.286-18.415,4.004-29.263,5.146 c9.894,8.562,14.842,22.077,14.842,40.539v60.237c0,3.422,1.19,6.279,3.572,8.562c2.379,2.279,6.136,2.95,11.276,1.995 c44.163-14.653,80.185-41.062,108.068-79.226c27.88-38.161,41.825-81.126,41.825-128.906 C438.536,184.851,428.728,148.168,409.132,114.573z">
							</path>
						</svg> -->
            </a>
          </div>
        </div>
        <div class="project-image">
          <a href="#">
            <div
              class="img gatsby-image-wrapper"
              style="position: relative; overflow: hidden;"
            >
              <div
                aria-hidden="true"
                style="width: 100%; padding-bottom: 62.2857%;"
              />
              <img
                aria-hidden="true"
                src="data:image/svg+xml,%3csvg%20xmlns='http://www.w3.org/2000/svg'%20width='400'%20height='250'%20viewBox='0%200%20400%20250'%20preserveAspectRatio='none'%3e%3cpath%20d='M0%2080v80h47c2%200%203%200%203-9l1-10h94v20h8v-10l1-10h93v10l1%2010h7v-10l1-10h94v9l1%2010h24l25-1%201-80V0H0v80m192-64c-8%204-11%2014-7%2022%202%204%201%204%207%200%205-4%205-4%205%203-1%207%200%207%204%207l4-1-1-7%201-7%201%202%203%204c5%201%205%201%206-2%207-14-10-29-23-21m95%20171c0%206%200%206%203%206%206%202%2010%209%208%2015l-1%203%205%203%205%203%201-2c2-3%202-13%201-17-3-9-10-15-19-16l-3-1v6m-222%202c-3%203-6%208-6%2010s21%207%2022%206l-13-18c0-1-2%200-3%202m13%2019c-12%2014-13%2016-4%2018%207%203%2015%202%2020-2l2-2-7-8-7-9-4%203'%20fill='%2364ffda'%20fill-rule='evenodd'/%3e%3c/svg%3e"
                alt=""
                style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; object-fit: cover; object-position: center center; opacity: 0; transition-delay: 500ms;"
              />
              <img
                src="img/portfolio/courierStack-ui.png"
                alt="CourierStack"
                loading="lazy"
                style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; object-fit: cover; object-position: center center; opacity: 1; transition: opacity 500ms ease 0s;"
              />
            </div>
          </a>
        </div>
      </div>
      <div
        class="main-project"
        style="visibility: visible; opacity: 1; transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transition: opacity 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0s, transform 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0s;"
      >
        <div class="project-content">
          <p class="project-overline">Featured Project</p>
          <h3 class="project-title">Olamstech.com</h3>
          <div class="project-description">
            <p>
              A Marketing website and e-commerce platform for Olamstech, an
              ambitious tech startup and computer repair company based in the
              UK.
            </p>
          </div>
          <ul class="project-tech-list">
            <li>Wordpress</li>
            <li>HTML5</li>
            <li>CSS3</li>
          </ul>
          <div class="project-links">
            <a
              href="https://github.com/MindInitiatives/Olamstech-Website"
              aria-label="GitHub Link"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                role="img"
                viewBox="0 0 438.549 438.549"
              >
                <title>GitHub</title>
                <path
                  d="M409.132,114.573c-19.608-33.596-46.205-60.194-79.798-79.8C295.736,15.166,259.057,5.365,219.271,5.365 c-39.781,0-76.472,9.804-110.063,29.408c-33.596,19.605-60.192,46.204-79.8,79.8C9.803,148.168,0,184.854,0,224.63 c0,47.78,13.94,90.745,41.827,128.906c27.884,38.164,63.906,64.572,108.063,79.227c5.14,0.954,8.945,0.283,11.419-1.996 c2.475-2.282,3.711-5.14,3.711-8.562c0-0.571-0.049-5.708-0.144-15.417c-0.098-9.709-0.144-18.179-0.144-25.406l-6.567,1.136 c-4.187,0.767-9.469,1.092-15.846,1c-6.374-0.089-12.991-0.757-19.842-1.999c-6.854-1.231-13.229-4.086-19.13-8.559 c-5.898-4.473-10.085-10.328-12.56-17.556l-2.855-6.57c-1.903-4.374-4.899-9.233-8.992-14.559 c-4.093-5.331-8.232-8.945-12.419-10.848l-1.999-1.431c-1.332-0.951-2.568-2.098-3.711-3.429c-1.142-1.331-1.997-2.663-2.568-3.997 c-0.572-1.335-0.098-2.43,1.427-3.289c1.525-0.859,4.281-1.276,8.28-1.276l5.708,0.853c3.807,0.763,8.516,3.042,14.133,6.851 c5.614,3.806,10.229,8.754,13.846,14.842c4.38,7.806,9.657,13.754,15.846,17.847c6.184,4.093,12.419,6.136,18.699,6.136 c6.28,0,11.704-0.476,16.274-1.423c4.565-0.952,8.848-2.383,12.847-4.285c1.713-12.758,6.377-22.559,13.988-29.41 c-10.848-1.14-20.601-2.857-29.264-5.14c-8.658-2.286-17.605-5.996-26.835-11.14c-9.235-5.137-16.896-11.516-22.985-19.126 c-6.09-7.614-11.088-17.61-14.987-29.979c-3.901-12.374-5.852-26.648-5.852-42.826c0-23.035,7.52-42.637,22.557-58.817 c-7.044-17.318-6.379-36.732,1.997-58.24c5.52-1.715,13.706-0.428,24.554,3.853c10.85,4.283,18.794,7.952,23.84,10.994 c5.046,3.041,9.089,5.618,12.135,7.708c17.705-4.947,35.976-7.421,54.818-7.421s37.117,2.474,54.823,7.421l10.849-6.849 c7.419-4.57,16.18-8.758,26.262-12.565c10.088-3.805,17.802-4.853,23.134-3.138c8.562,21.509,9.325,40.922,2.279,58.24 c15.036,16.18,22.559,35.787,22.559,58.817c0,16.178-1.958,30.497-5.853,42.966c-3.9,12.471-8.941,22.457-15.125,29.979 c-6.191,7.521-13.901,13.85-23.131,18.986c-9.232,5.14-18.182,8.85-26.84,11.136c-8.662,2.286-18.415,4.004-29.263,5.146 c9.894,8.562,14.842,22.077,14.842,40.539v60.237c0,3.422,1.19,6.279,3.572,8.562c2.379,2.279,6.136,2.95,11.276,1.995 c44.163-14.653,80.185-41.062,108.068-79.226c27.88-38.161,41.825-81.126,41.825-128.906 C438.536,184.851,428.728,148.168,409.132,114.573z"
                />
              </svg></a
            ><a href="https://https://olamstech.com/" aria-label="External Link"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                role="img"
                viewBox="0 0 194.818 194.818"
              >
                <title>External</title>
                <g>
                  <path
                    d="M185.818,2.161h-57.04c-4.971,0-9,4.029-9,9s4.029,9,9,9h35.312l-86.3,86.3c-3.515,3.515-3.515,9.213,0,12.728 c1.758,1.757,4.061,2.636,6.364,2.636s4.606-0.879,6.364-2.636l86.3-86.3v35.313c0,4.971,4.029,9,9,9s9-4.029,9-9v-57.04 C194.818,6.19,190.789,2.161,185.818,2.161z"
                  />
                  <path
                    d="M149,77.201c-4.971,0-9,4.029-9,9v88.456H18v-122h93.778c4.971,0,9-4.029,9-9s-4.029-9-9-9H9c-4.971,0-9,4.029-9,9v140 c0,4.971,4.029,9,9,9h140c4.971,0,9-4.029,9-9V86.201C158,81.23,153.971,77.201,149,77.201z"
                  />
                </g>
              </svg></a
            >
          </div>
        </div>
        <div class="project-image">
          <a href="https://olamstech.com/">
            <div
              class="img gatsby-image-wrapper"
              style="position: relative; overflow: hidden;"
            >
              <div
                aria-hidden="true"
                style="width: 100%; padding-bottom: 62.2857%;"
              />
              <img
                aria-hidden="true"
                src="data:image/svg+xml,%3csvg%20xmlns='http://www.w3.org/2000/svg'%20width='400'%20height='250'%20viewBox='0%200%20400%20250'%20preserveAspectRatio='none'%3e%3cpath%20d='M0%2080v80h47c2%200%203%200%203-9l1-10h94v20h8v-10l1-10h93v10l1%2010h7v-10l1-10h94v9l1%2010h24l25-1%201-80V0H0v80m192-64c-8%204-11%2014-7%2022%202%204%201%204%207%200%205-4%205-4%205%203-1%207%200%207%204%207l4-1-1-7%201-7%201%202%203%204c5%201%205%201%206-2%207-14-10-29-23-21m95%20171c0%206%200%206%203%206%206%202%2010%209%208%2015l-1%203%205%203%205%203%201-2c2-3%202-13%201-17-3-9-10-15-19-16l-3-1v6m-222%202c-3%203-6%208-6%2010s21%207%2022%206l-13-18c0-1-2%200-3%202m13%2019c-12%2014-13%2016-4%2018%207%203%2015%202%2020-2l2-2-7-8-7-9-4%203'%20fill='%2364ffda'%20fill-rule='evenodd'/%3e%3c/svg%3e"
                alt=""
                style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; object-fit: cover; object-position: center center; opacity: 0; transition-delay: 500ms;"
              />
              <img
                src="img/portfolio/olamstech.jpg"
                alt="Olamstech"
                loading="lazy"
                style="position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; object-fit: cover; object-position: center center; opacity: 1; transition: opacity 500ms ease 0s;"
              />
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- </div> -->
<!-- projects -->
<div class="section" id="projects">
  <div class="container">
    <div class="col-md-12">
      <h4>04</h4>
      <h1 class="size-50">Other <br /> Projects</h1>
    </div>
    <!-- main container -->
    <div class="main-container portfolio-inner clearfix">
      <!-- portfolio div -->
      <div class="portfolio-div">
        <div class="portfolio">
          <!-- portfolio_filter -->
          <div class="categories-grid wow fadeInLeft">
            <nav class="categories">
              <ul class="portfolio_filter">
                <li><a href="#" class="active" data-filter="*">All</a></li>
                <li><a href="#" data-filter=".angular">Angular</a></li>
                <li><a href="#" data-filter=".mobileApps">Mobile Apps</a></li>
                <li><a href="#" data-filter=".graphics">User Interfaces</a></li>
                <li><a href="#" data-filter=".wordpress">Wordpress</a></li>
                <li><a href="#" data-filter=".webApps">Web Apps</a></li>
              </ul>
            </nav>
          </div>
          <!-- portfolio_filter -->

          <!-- portfolio_container -->
          <div
            class="no-padding portfolio_container clearfix"
            data-aos="fade-up"
          >
            <!-- single work -->
            <div
              class="col-lg-6 col-md-4 col-sm-6  angular"
              style="position: inherit;"
            >
              <a id="demo01" class="portfolio_item">
                <img
                  src="img/portfolio/angularAdmin.png"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <!-- <div class="project-top">
												<div class="folder">
													<svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 60 60"><title>Folder</title><path d="M57.49,21.5H54v-6.268c0-1.507-1.226-2.732-2.732-2.732H26.515l-5-7H2.732C1.226,5.5,0,6.726,0,8.232v43.687l0.006,0 c-0.005,0.563,0.17,1.114,0.522,1.575C1.018,54.134,1.76,54.5,2.565,54.5h44.759c1.156,0,2.174-0.779,2.45-1.813L60,24.649v-0.177 C60,22.75,58.944,21.5,57.49,21.5z M2,8.232C2,7.828,2.329,7.5,2.732,7.5h17.753l5,7h25.782c0.404,0,0.732,0.328,0.732,0.732V21.5 H12.731c-0.144,0-0.287,0.012-0.426,0.036c-0.973,0.163-1.782,0.873-2.023,1.776L2,45.899V8.232z M47.869,52.083 c-0.066,0.245-0.291,0.417-0.545,0.417H2.565c-0.243,0-0.385-0.139-0.448-0.222c-0.063-0.082-0.16-0.256-0.123-0.408l10.191-27.953 c0.066-0.245,0.291-0.417,0.545-0.417H54h3.49c0.38,0,0.477,0.546,0.502,0.819L47.869,52.083z"></path></svg>
												</div>
												<div class="myProject-links">
													<a href="https://github.com/bchiang7/time-to-have-more-fun" aria-label="GitHub Link">
													<svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 438.549 438.549"><title>GitHub</title><path d="M409.132,114.573c-19.608-33.596-46.205-60.194-79.798-79.8C295.736,15.166,259.057,5.365,219.271,5.365 c-39.781,0-76.472,9.804-110.063,29.408c-33.596,19.605-60.192,46.204-79.8,79.8C9.803,148.168,0,184.854,0,224.63 c0,47.78,13.94,90.745,41.827,128.906c27.884,38.164,63.906,64.572,108.063,79.227c5.14,0.954,8.945,0.283,11.419-1.996 c2.475-2.282,3.711-5.14,3.711-8.562c0-0.571-0.049-5.708-0.144-15.417c-0.098-9.709-0.144-18.179-0.144-25.406l-6.567,1.136 c-4.187,0.767-9.469,1.092-15.846,1c-6.374-0.089-12.991-0.757-19.842-1.999c-6.854-1.231-13.229-4.086-19.13-8.559 c-5.898-4.473-10.085-10.328-12.56-17.556l-2.855-6.57c-1.903-4.374-4.899-9.233-8.992-14.559 c-4.093-5.331-8.232-8.945-12.419-10.848l-1.999-1.431c-1.332-0.951-2.568-2.098-3.711-3.429c-1.142-1.331-1.997-2.663-2.568-3.997 c-0.572-1.335-0.098-2.43,1.427-3.289c1.525-0.859,4.281-1.276,8.28-1.276l5.708,0.853c3.807,0.763,8.516,3.042,14.133,6.851 c5.614,3.806,10.229,8.754,13.846,14.842c4.38,7.806,9.657,13.754,15.846,17.847c6.184,4.093,12.419,6.136,18.699,6.136 c6.28,0,11.704-0.476,16.274-1.423c4.565-0.952,8.848-2.383,12.847-4.285c1.713-12.758,6.377-22.559,13.988-29.41 c-10.848-1.14-20.601-2.857-29.264-5.14c-8.658-2.286-17.605-5.996-26.835-11.14c-9.235-5.137-16.896-11.516-22.985-19.126 c-6.09-7.614-11.088-17.61-14.987-29.979c-3.901-12.374-5.852-26.648-5.852-42.826c0-23.035,7.52-42.637,22.557-58.817 c-7.044-17.318-6.379-36.732,1.997-58.24c5.52-1.715,13.706-0.428,24.554,3.853c10.85,4.283,18.794,7.952,23.84,10.994 c5.046,3.041,9.089,5.618,12.135,7.708c17.705-4.947,35.976-7.421,54.818-7.421s37.117,2.474,54.823,7.421l10.849-6.849 c7.419-4.57,16.18-8.758,26.262-12.565c10.088-3.805,17.802-4.853,23.134-3.138c8.562,21.509,9.325,40.922,2.279,58.24 c15.036,16.18,22.559,35.787,22.559,58.817c0,16.178-1.958,30.497-5.853,42.966c-3.9,12.471-8.941,22.457-15.125,29.979 c-6.191,7.521-13.901,13.85-23.131,18.986c-9.232,5.14-18.182,8.85-26.84,11.136c-8.662,2.286-18.415,4.004-29.263,5.146 c9.894,8.562,14.842,22.077,14.842,40.539v60.237c0,3.422,1.19,6.279,3.572,8.562c2.379,2.279,6.136,2.95,11.276,1.995 c44.163-14.653,80.185-41.062,108.068-79.226c27.88-38.161,41.825-81.126,41.825-128.906 C438.536,184.851,428.728,148.168,409.132,114.573z"></path></svg>
													</a>
													<a href="https://time-to-have-more-fun.now.sh/" aria-label="External Link">
													<svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 194.818 194.818"><title>External</title><g><path d="M185.818,2.161h-57.04c-4.971,0-9,4.029-9,9s4.029,9,9,9h35.312l-86.3,86.3c-3.515,3.515-3.515,9.213,0,12.728 c1.758,1.757,4.061,2.636,6.364,2.636s4.606-0.879,6.364-2.636l86.3-86.3v35.313c0,4.971,4.029,9,9,9s9-4.029,9-9v-57.04 C194.818,6.19,190.789,2.161,185.818,2.161z"></path><path d="M149,77.201c-4.971,0-9,4.029-9,9v88.456H18v-122h93.778c4.971,0,9-4.029,9-9s-4.029-9-9-9H9c-4.971,0-9,4.029-9,9v140 c0,4.971,4.029,9,9,9h140c4.971,0,9-4.029,9-9V86.201C158,81.23,153.971,77.201,149,77.201z"></path></g></svg>
													</a>
												</div>
											</div> -->
                      <span>Angular10 Admin Dashboard Panel from scratch</span>
                      <em
                        >Angular Material Designs, Highcharts and Flex-layout</em
                      >
                      <ul class="project-tech-list">
                        <li>Angular</li>
                        <li>TypeScript</li>
                        <li>HighChart.js</li>
                      </ul>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div
              class="col-lg-6 col-md-4 col-sm-6  angular"
              style="position: inherit;"
            >
              <a id="demo01" class="portfolio_item">
                <img
                  src="img/portfolio/courierStack-Admin.png"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>CourierStack Responsive Admin Dashboard</span>
                      <em>Angular DataTables, Highcharts and ng-Bootstraps</em>
                      <ul class="project-tech-list">
                        <li>Angular</li>
                        <li>TypeScript</li>
                        <li>HighChart.js</li>
                        <li>ASP.NET</li>
                      </ul>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6 graphics">
              <a id="demo02" class="portfolio_item">
                <img
                  src="img/portfolio/foodieng-ui.png"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>Foodieng UI</span>
                      <em>A Mobile Platform for Food Lovers</em>
                      <ul class="project-tech-list">
                        <li>Adobe-XD</li>
                        <li>Mockups</li>
                        <li>Prototype</li>
                      </ul>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6  mobileApps">
              <a id="demo03" class="portfolio_item">
                <img
                  src="img/portfolio/medNg.png"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>A Covid-19 Tracker Mobile App</span>
                      <em
                        >Live Feeds, Monitors Outbreak rate, Death rate and
                        Recovery rate in the countries of the World and Nigeria
                        at Large</em
                      >
                      <ul class="project-tech-list">
                        <li>Android Java</li>
                        <li>Retrofit</li>
                        <li>SVG.js</li>
                      </ul>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6  mobileApps">
              <a id="demo04" class="portfolio_item">
                <img
                  src="img/portfolio/courierStack.png"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>Official CourierStack Mobile App</span>
                      <em>Couriers Logisitics Order Tracking</em>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6  mobileApps">
              <a id="demo05" class="portfolio_item">
                <img
                  src="img/portfolio/shopLasena.png"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>ShopLasena</span>
                      <em>Lasena water mobile ap</em>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6 wordpress">
              <a id="demo06" class="portfolio_item">
                <img
                  src="img/portfolio/olamstech.jpg"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>Olamstech Official Website</span>
                      <em>Wordpress</em>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6 webApps">
              <a id="demo07" class="portfolio_item">
                <img
                  src="img/portfolio/softEntry.jpg"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>SoftEntry</span>
                      <em>Visitors and Guest Mnagement</em>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6 webApps">
              <a id="demo07" class="portfolio_item">
                <img
                  src="img/portfolio/courierStack-Web%20Portal.jpg"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>Courier Stack</span>
                      <em>Administrator's Web Portal</em>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <div class="col-lg-6 col-md-4 col-sm-6 graphics">
              <a id="demo08" class="portfolio_item">
                <img
                  src="img/portfolio/courierStack-ui.png"
                  alt="image"
                  class="img-responsive"
                />
                <div class="portfolio_item_hover">
                  <div class="portfolio-border clearfix">
                    <div class="item_info">
                      <span>Courier Stack</span>
                      <em>User Interfaces and User Experience</em>
                    </div>
                  </div>
                </div>
              </a>
            </div>
            <!-- end single work -->

            <!-- single work -->
            <!-- <div class="col-lg-6 col-md-4 col-sm-6 graphics wordpress">
							<a id="demo09" href="#animatedModal" class="portfolio_item"> <img
									src="img/portfolio/08.jpg" alt="image" class="img-responsive" />
								<div class="portfolio_item_hover">
									<div class="portfolio-border clearfix">
										<div class="item_info"> <span>Mobile devices</span> <em>Graphics / Ads</em>
										</div>
									</div>
								</div>
							</a>
						</div> -->
            <!-- end single work -->
          </div>
          <!-- end portfolio_container -->
        </div>
        <!-- portfolio -->
      </div>
      <!-- end portfolio div -->
    </div>
    <!-- end main container -->
  </div>
</div>
<!-- ./projects -->

<!-- contact -->
<div
  id="contact"
  class="section hello"
  style="visibility: visible; opacity: 1; transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1); transition: opacity 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0.2s, transform 0.5s cubic-bezier(0.645, 0.045, 0.355, 1) 0.2s;"
>
  <div class="container c-section">
    <div class="col-md-12">
      <h4>05</h4>
      <h2 class="numbered-heading overline">What’s Next?</h2>
      <h2 class="title">Get In Touch</h2>
      <p>
        I am currently looking for any new opportunities, Kindly reach out to me
        if there are job opportunities you'd love me to know about. If it is
        just to say hi, my inbox is always open. Feel free to drop me a
        message.!
      </p>
      <a class="email-link" href="mailto:steevyn51@gmail.com">Say Hello</a>
      <a class="email-link" href="tel:07040206876">Or Call</a>
    </div>
  </div>
</div>

<footer class="footer footerStyle">
  <div class="footerCredit flink">
    <a href="https://github.com/valike23">
      <div>Designed &amp; Built by Valentine Emmanuel</div>
    </a>
  </div>
</footer>
