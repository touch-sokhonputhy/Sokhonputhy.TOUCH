# Sokhonputhy.TOUCH
My_Portfolio
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!--==================== UNICONS ====================-->
    <link
      rel="stylesheet"
      href="https://unicons.iconscout.com/release/v4.0.8/css/line.css"
    />

    <!--==================== SWIPER CSS ====================-->
    <link rel="stylesheet" href="assets/css/swiper-bundle.min.css" />

    <!--==================== CSS ====================-->
    <link rel="stylesheet" href="assets/css/styles.css" />

    <title>Responsive Portfolio Website</title>
  </head>
  <body>
    <!--==================== HEADER ====================-->
    <header class="header" id="header">
      <nav class="nav container">
        <a
          href="https://www.canva.com/design/DAGUdl3hSEI/vQ4z7dKbC0wb7eMVVdtGxg/edit"
          class="nav__logo"
          >Puthy TouchSokhon</a
        >
        <div class="nav__menu" id="nav-menu">
          <ul class="nav__list grid">
            <li class="nav__item">
              <a href="#home" class="nav__link active__link"
                ><i class="uil uil-house-user nav__icon"></i>Home</a
              >
            </li>
            <li class="nav__item">
              <a href="#user" class="nav__link"
                ><i class="uil uil-user-location nav__icon"></i>User</a
              >
            </li>
            <li class="nav__item">
              <a href="#skills" class="nav__link"
                ><i class="uil uil-file-heart nav__icon"></i>Skills</a
              >
            </li>

            <li class="nav__item">
              <a href="#services" class="nav__link"
                ><i class="uil uil-servers nav__icon"></i>Services</a
              >
            </li>
            <li class="nav__item">
              <a href="#portfolio" class="nav__link"
                ><i class="uil uil-briefcase-alt nav__icon"></i>Portfolio</a
              >
            </li>
            <li class="nav__item">
              <a href="#contact" class="nav__link"
                ><i class="uil uil-comment-alt-medical nav__icon"></i>Contact</a
              >
            </li>
          </ul>
          <i class="uil uil-multiply nav__close" id="nav-close"></i>
        </div>
        <div class="nav__btns">
          <!-- Theme change button -->
          <i class="uil uil-moon change-theme" id="theme-button"> </i>
          <div class="nav__toggle" id="nav__toggle">
            <i class="uil uil-app"></i>
          </div>
        </div>
      </nav>
    </header>

    <!--==================== MAIN ====================-->
    <main class="main">
      <!--==================== HOME ====================-->
      <section class="home section" id="home">
        <div class="hopmr__container container grid">
          <div class="home__container grid">
            <div class="home__social">
              <a
                href="https://www.facebook.com/share/1BGGJ8E1eq/?mibextid=wwXIfr"
                class="home__social-icon"
                target="_blank"
                ><i class="uil uil-facebook-f"></i
              ></a>
              <a
                href="https://www.tiktok.com/@puthy1306?is_from_webapp=1&sender_device=pc"
                class="home__social-icon"
                target="_blank"
                ><i class="uil uil-atom"></i
              ></a>
              <a
                href="https://www.instagram.com/puthyyy_thyy_thy/profilecard"
                class="home__social-icon"
                target="_blank"
                ><i class="uil uil-instagram"></i
              ></a>
              <a
                href="https://t.me/PUTHY_13"
                class="home__social-icon"
                target="_blank"
                ><i class="uil uil-telegram"></i
              ></a>
            </div>
            <div class="loader"></div>
            <div class="home__img">
              <svg
                class="home__blob"
                viewBox="0 0 200 187"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
              >
                <mask id="mask0" mask-type="alpha">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547 
                    130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775 
                    97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666 
                    0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />
                </mask>
                <g mask="url(#mask0)">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 
                    165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 
                    129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 
                    -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />

                  <image
                    class="home__blob-img"
                    x="20"
                    y="0.1"
                    xlink:href="assets/img/perfil.png"
                  />
                </g>
              </svg>
            </div>
            <div class="home_data">
              <h1 class="home_title">Hi I'm Puthy</h1>
              <h3 class="home__subtitle">
                IT Service Administrator & Frontend Developer
              </h3>
              <p class="home__description">
                Flexible ,Open Mind ,Never Give up And Love Communication
              </p>
              <a href="#contact" class="button button--flex">
                CONTACT ME <i class="uil uil-message buttom__icon"></i>
              </a>
            </div>
          </div>
          <div class="home__scroll">
            <a href="#about" class="home__scroll-button button--flex">
              <i class="uil uil-mouse-alt home__scroll-mouse"></i>
              <span class="home__scroll-name">Scroll Down</span>
              <i class="uil uil-arrow-down home__scroll-arrow"></i>
            </a>
          </div>
        </div>
      </section>

      <!--==================== ABOUT ====================-->
      <section class="about section" id="about">
        <h2 class="section__titles">About Me</h2>
        <span class="section__subtitle">My Introduction</span>
        <div class="about__container container grid">
          <img src="assets/img/about.jpg" alt="" class="about__img" />

          <div class="about__data">
            <p class="about__description">
              I am a flexible, reliable, self-motivated, and hardworking college
              student seeking employment. Adept at working independently and
              collaboratively on projects, and committed to achieving visual
              innovation.
            </p>

            <div class="about__info">
              <div>
                <span class="about__info-title">06+</span>
                <span class="about__info-name"
                  >Months <br />
                  experience</span
                >
              </div>
              <div>
                <span class="about__info-title">13+</span>
                <span class="about__info-name"
                  >Completed<br />
                  project</span
                >
              </div>
              <div>
                <span class="about__info-title">02+</span>
                <span class="about__info-name"
                  >Companies <br />
                  worked</span
                >
              </div>
            </div>

            <div class="about__button">
              <a href="assets/pdf/Alexa-Cv.pdf" class="button button--flex">
                Download My CV<i class="uil uil-download-alt buttom__icon"></i>
              </a>
            </div>
          </div>
        </div>
      </section>

      <!--==================== SKILLS ====================-->
      <section class="skills section" id="skills">
        <h2 class="section__titles">Skills</h2>
        <span class="section__subtitle">My Technical Level</span>

        <div class="skills__container container grid">
          <div>
            <!--==================== SKILLS 1====================-->
            <div class="skills__content skills__open">
              <div class="skills__header">
                <i class="uil uil-brackets-curly skills__icon"></i>
                <div>
                  <h1 class="skills__titles">Fronted Developer</h1>
                  <span class="skills__subtitle">More than 2years</span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>
              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills title">
                    <h3 class="skills__names">HTML</h3>
                    <span class="skills__number">90%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__html"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills titles">
                    <h3 class="skills__name">CAPCUT</h3>
                    <span class="skills__number">60%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__capcut"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills titles">
                    <h3 class="skills__name">CSS</h3>
                    <span class="skills__number">70%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__css"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills titles">
                    <h3 class="skills__name">CANVA</h3>
                    <span class="skills__number">80%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__canva"></span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!--==================== SKILLS 2====================-->
          <div class="skills__content skills__close">
            <div class="skills__header">
              <i class="uil uil-server-network skills__icon"></i>
              <div>
                <h1 class="skills__titles">Software Developer</h1>
                <span class="skills__subtitle">More than 3months</span>
              </div>

              <i class="uil uil-angle-down skills__arrow"></i>
            </div>
            <div class="skills__list grid">
              <div class="skills__data">
                <div class="skills titles">
                  <h3 class="skills__name">Fixing DeBug</h3>
                  <span class="skills__number">80%</span>
                </div>
                <div class="skills__bar">
                  <span class="skills__percentage skills__fixing-debug"></span>
                </div>
              </div>

              <div class="skills__data">
                <div class="skills titles">
                  <h3 class="skills__name">C++</h3>
                  <span class="skills__number">75%</span>
                </div>
                <div class="skills__bar">
                  <span class="skills__percentage skills__cpp"></span>
                </div>
              </div>

              <div class="skills__data">
                <div class="skills titles">
                  <h3 class="skills__name">C</h3>
                  <span class="skills__number">70%</span>
                </div>
                <div class="skills__bar">
                  <span class="skills__percentage skills__c"></span>
                </div>
              </div>

              <div class="skills__data">
                <div class="skills titles">
                  <h3 class="skills__name">Java</h3>
                  <span class="skills__number">30%</span>
                </div>
                <div class="skills__bar">
                  <span class="skills__percentage skills__java"></span>
                </div>
              </div>
            </div>
          </div>

          <div>
            <!--==================== SKILLS 3===================-->
            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="uil uil-swatchbook skills__icon"></i>
                <div>
                  <h1 class="skills__titles">Designer</h1>
                  <span class="skills__subtitle">More than 6months</span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>
              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills titles">
                    <h3 class="skills__name">Creative-Idea</h3>
                    <span class="skills__number">80%</span>
                  </div>
                  <div class="skills__bar">
                    <span
                      class="skills__percentage skills__creative-idea"
                    ></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills titles">
                    <h3 class="skills__name">Picsart</h3>
                    <span class="skills__number">70%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__picsart"></span>
                  </div>
                </div>

                <div class="skills__data">
                  <div class="skills titles">
                    <h3 class="skills__name">Bootstrap</h3>
                    <span class="skills__number">80%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__bootstrap"></span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--==================== QUALIFICATION ====================-->
      <section class="qualification section">
        <h2 class="section__titles">Qualification</h2>
        <span class="section__subtitle">My Personal Journey</span>
        <div class="qulificatio__container container">
          <div class="qualification__tabs">
            <div
              class="qualification__button button--flex qualification__active"
              data-target="#education"
            >
              <i class="uil uil-graduation-cap qualification__icon"></i>
              Education
            </div>

            <div class="qualification__button button--flex" data-target="#work">
              <i class="uil uil-briefcase-alt qualification__icon"></i>
              Work
            </div>
          </div>

          <div class="qualification__section">
            <!--==================== QUALIFICATION CONTENT I====================-->
            <div
              class="qualification__content qualification__active"
              data-content
              id="education"
            >
              <!--==================== QUALIFICATION 1====================-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">Information Technology</h3>
                  <span class="qulification__subtitle">RUPP-UNIVERSITY</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    Feb 2023 - Present
                  </div>

                  <div>
                    <span class="qualification__rounder"></span>
                    <span class="qualification__line"></span>
                  </div>
                </div>
              </div>

              <!--==================== QUALIFICATION 2====================-->
              <div class="qualification__data">
                <div></div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>

                <div>
                  <h3 class="qualification__title">Web Designer</h3>
                  <span class="qulification__subtitle">Self-Learning</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    2021 - Present
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>

              <!--==================== QUALIFICATION 3====================-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">IT Support</h3>
                  <span class="qulification__subtitle"
                    >Work - Comin_Khmere</span
                  >
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    Dec 2024 - Present
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>

              <!--==================== QUALIFICATION 4====================-->
              <div class="qualification__data">
                <div></div>

                <div>
                  <span class="qualification__rounder"></span>
                  <!-- <span class="qualification__line"></span> -->
                </div>

                <div>
                  <h3 class="qualification__title">EV Making Project</h3>
                  <span class="qulification__subtitle">Join the Academic</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    Dec 2024 - Present
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>
            </div>
            <!--==================== QUALIFICATION CONTENT II====================-->
            <div class="qualification__content" data-content id="work">
              <!--==================== QUALIFICATION 1====================-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">Intern Sale</h3>
                  <span class="qulification__subtitle"
                    >At Spring Education Center</span
                  >
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    Feb 2023 - 2024
                  </div>

                  <div>
                    <span class="qualification__rounder"></span>
                    <span class="qualification__line"></span>
                  </div>
                </div>
              </div>

              <!--==================== QUALIFICATION 2====================-->
              <div class="qualification__data">
                <div></div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>

                <div>
                  <h3 class="qualification__title">Call Center(Vouluteer)</h3>
                  <span class="qulification__subtitle"
                    >At Spring Education Center</span
                  >
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    2021 - 24
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>

              <!--==================== QUALIFICATION 3====================-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">Pubilc Speaking</h3>
                  <span class="qulification__subtitle">Competition at SEC</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    June 2024 - July 2024
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--==================== SERVICES ====================-->
      <section class="services section" id="services">
        <h2 class="section__titles">Services</h2>
        <span class="section__subtitle">What I Offer</span>
        <div class="services__container container grid">
          <!--==================== SERVICES 1====================-->
          <div class="services__content">
            <div>
              <i class="uil uil-web-grid services__icon"></i>
              <h3 class="services__titles">
                UI/UX <br />
                Designer
              </h3>
            </div>
            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__model">
              <div class="services__model-content">
                <h4 class="services__model-title">
                  UI/UX <br />
                  Designer
                </h4>
                <i class="uil uil-time services__modal-close"></i>

                <ul class="services__modal-services grid"></ul>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I had develop the user interface.</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>Web Page Development</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I can solve problem issue in technology</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I have creative idea!!</p>
                </li>
              </div>
            </div>
          </div>

          <!--==================== SERVICES 2====================-->
          <div class="services__content">
            <div>
              <i class="uil uil-arrow services__icon"></i>
              <h3 class="services__titles">
                Frontend <br />
                Developer
              </h3>
            </div>
            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__model">
              <div class="services__model-content">
                <h4 class="services__model-title">
                  Frontend <br />
                  Developer
                </h4>
                <i class="uil uil-time services__modal-close"></i>

                <ul class="services__modal-services grid"></ul>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I had develop the user interface.</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>Web Page Development</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I can solve problem issue in technology</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I have creative idea!!</p>
                </li>
              </div>
            </div>
          </div>

          <!--==================== SERVICES 3====================-->
          <div class="services__content">
            <div>
              <i class="uil uil-pen services__icon"></i>
              <h3 class="services__titles">
                Branding <br />
                Designer
              </h3>
            </div>
            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__model">
              <div class="services__model-content">
                <h4 class="services__model-title">
                  Branding <br />
                  Designer
                </h4>
                <i class="uil uil-time services__modal-close"></i>

                <ul class="services__modal-services grid"></ul>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I had develop the user interface.</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>Web Page Development</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I can solve problem issue in technology</p>
                </li>
                <li class="services__modal-services">
                  <i class="uil uil-check-circle services__modal-icon"></i>
                  <p>I have creative idea!!</p>
                </li>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--==================== PORTFOLIO ====================-->
      <section class="portfolio section" id="portfolio">
        <h2 class="section__titles">Portfolio</h2>
        <span class="section__subtitle">Some of My Work</span>

        <div class="portfolio__container container swiper-container">
          <div class="swiper-wrapper">
            <!--==================== PORTFOLIO 1 =====================-->
            <div class="portfolio__content grid swiper-slide">
              <img
                src="assets/img/portfolio1.jpg"
                alt="Portfolio 1"
                class="portfolio__img"
              />
              <div class="portfolio__data">
                <h3 class="portfolio__title">Portfolio Website</h3>
                <p class="portfolio__description">
                  Web Design For MySelf To Hosting In My Social
                </p>
                <a
                  href="#"
                  class="button button--flex button--small portfolio__button"
                >
                  Demo
                  <i class="uil uil-arrow-right button__icon"></i>
                </a>
              </div>
            </div>

            <!--==================== PORTFOLIO 2 =====================-->
            <div class="portfolio__content grid swiper-slide">
              <img
                src="assets/img/portfolio2.jpg"
                alt="Portfolio 2"
                class="portfolio__img"
              />
              <div class="portfolio__data">
                <h3 class="portfolio__title">Calculate Bacii Result</h3>
                <p class="portfolio__description">
                  I design this for science student that they want to calculate
                  about the score to get the result.
                </p>
                <a
                  href="#"
                  class="button button--flex button--small portfolio__button"
                >
                  Demo
                  <i class="uil uil-arrow-right button__icon"></i>
                </a>
              </div>
            </div>

            <!--==================== PORTFOLIO 3 =====================-->
            <div class="portfolio__content grid swiper-slide">
              <img
                src="assets/img/portfolio3.jpg"
                alt="Portfolio 3"
                class="portfolio__img"
              />
              <div class="portfolio__data">
                <h3 class="portfolio__title">Creative-Idea</h3>
                <p class="portfolio__description">
                  I always open-mind to sharing my idea to my teammate and
                  everywhere need concept to do something.
                </p>
                <a
                  href="#"
                  class="button button--flex button--small portfolio__button"
                >
                  Demo
                  <i class="uil uil-arrow-right button__icon"></i>
                </a>
              </div>
            </div>
          </div>

          <!-- Add Arrow -->
          <div class="swiper-button-next">
            <i class="uil uil-angle-right-b swiper-portfolio-icon"></i>
          </div>
          <div class="swiper-button-prev">
            <i class="uil uil-angle-left-b swiper-portfolio-icon"></i>
          </div>

          <!-- Add Pagination -->
          <div class="swiper-pagination"></div>
        </div>
      </section>

      <!--==================== PROJECT IN MIND ====================-->
      <section class="project section">
        <div class="project__bg">
          <div class="project__container container grid">
            <div class="project__data">
              <h2 class="project__title">You have a new project</h2>
              <p class="project__description">
                Contact me now and get a 10% discount on your new project!
              </p>
              <a href="#contact" class="button button--flex button--white">
                Contact Me
                <i class="uil uil-message project__icon button__icon"></i>
              </a>
            </div>

            <img src="assets/img/project.png" alt="" class="project__img" />
          </div>
        </div>
      </section>

      <!--==================== TESTIMONIAL ====================-->
      <!-- <section class="testimonial section">
        <h2 class="section__title">TESTIMONIAL</h2>
        <span class="section__subtitle">My Client Saying</span>

        <div class="testimonial__container container">
          <div class="swiper-wrapper">
    TESTIMONIAL 
            <div class="testimonial__content swiper-slide">
              <div class="testimonial__data">
                <div class="testimonial__header">
                  <img
                    src="assets/img/testimonial1.jpg"
                    alt=""
                    class="testimonial__img"
                  />

                  <div>
                    <h3 class="testimonial__name">Puthy TouchSokhon</h3>
                    <span class="testimonial__client">Client</span>
                  </div>
                </div>

                <div>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                </div>
              </div>

              <p class="testimonial__description">
                I get a good impression, I carry out my project with all the
                possible quality and attention and support 24hours a day.
              </p>
            </div>
TESTIMONIAL 2 
            <div class="testimonial__content swiper-slide">
              <div class="testimonial__data">
                <div class="testimonial__header">
                  <img
                    src="assets/img/testimonial2.jpg"
                    alt=""
                    class="testimonial__img"
                  />

                  <div>
                    <h3 class="testimonial__name">Thy</h3>
                    <span class="testimonial__client">Client</span>
                  </div>
                </div>

                <div>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                </div>
              </div>

              <p class="testimonial__description">
                I get a good impression, I carry out my project with all the
                possible quality and attention and support 24hours a day.
              </p>
            </div>

 TESTIMONIAL 3 
            <div class="testimonial__content swiper-slide">
              <div class="testimonial__data">
                <div class="testimonial__header">
                  <img
                    src="assets/img/testimonial3.jpg"
                    alt=""
                    class="testimonial__img"
                  />

                  <div>
                    <h3 class="testimonial__name">Vuthy</h3>
                    <span class="testimonial__client">Client</span>
                  </div>
                </div>

                <div>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                  <i class="uil uil-star testmonial__icon-star"></i>
                </div>
              </div>

              <p class="testimonial__description">
                I get a good impression, I carry out my project with all the
                possible quality and attention and support 24hours a day.
              </p>
            </div>
          </div>
           Add Pagination 
          <div class="swiper-pagination swiper-pagination-testimonial"></div>
        </div>
      </section> -->

      <!--==================== CONTACT ME 1====================-->
      <section class="contact section" id="contact">
        <h2 class="section__titles">Contact Me</h2>
        <span class="section__subtitle">Get in touch</span>
    
        <div class="contact__container container grid">
            <div>
                <div class="contact__information">
                    <i class="uil uil-phone contact__icon"></i>
                    <div>
                        <h3 class="contact__title">Call ME</h3>
                        <span class="contact__subtitle">0-123-456-789</span>
                    </div>
                </div>
    
                <div class="contact__information">
                    <i class="uil uil-envelope contact__icon"></i>
                    <div>
                        <h3 class="contact__title">Email</h3>
                        <span class="contact__subtitle">touch.sokhonputhy.1223@rupp.edu.kh sokhonputhy.touch@comin.com.kh touchputhy13@gmail.com</span>
                    </div>
                </div>
    
                <div class="contact__information">
                    <i class="uil uil-map-marker contact__icon"></i>
                    <div>
                        <h3 class="contact__title">Location</h3>
                        <span class="contact__subtitle">Phnom Penh - Cambodia</span>
                    </div>
                </div>
            </div>
            <form action="" class="contact__form grid">
                <div class="contact__inputs grid">
                    <div class="contact__content">
                        <label for="" class="contact__label">Name</label>
                        <input type="text" class="contac__input" />
                    </div>
    
                    <div class="contact__content">
                        <label for="" class="contact__label">Email</label>
                        <input type="email" class="contac__input" />
                    </div>
                </div>
    
                <div class="contact__content">
                    <label for="" class="contact__label">Project</label>
                    <input type="project" class="contac__input" />
                </div>
    
                <div class="contact__content">
                    <label for="" class="contact__label">Message</label>
                    <textarea name="" id="" cols="0" rows="7" class="comtact__input"></textarea>
                </div>
                <div>
                    <a href="https://path-to-chatbotfather-sdk.js" class="button button--flex">
                        Send Message
                        <i class="uil uil-message button__icon"></i>
                    </a>
                </div>
            </form>
        </div>
    
        <!-- Chatbot container -->
        <div id="chatbot-container"></div>
    </section>
    
    <script src="https://path-to-chatbotfather-sdk.js"></script>
    <script>
        // Initialize Chatbotfather
        const chatbot = new Chatbotfather({
            token: '7933422788:AAG4IgndtD7Ho0P5abIOBzIJFbLtpZywX7k',
            container: document.getElementById('chatbot-container')
        });
    
        chatbot.init();
    </script>
    <!--==================== FOOTER ====================-->
    <footer class="footer">
      <div class="footer bg">
        <div class="footer__container container grid">
          <div>
            <h1 class="footer__title">Puthy TouchSokhon</h1>
            <span class="footer__subtitle"
              >IT Service Administrator <br />
              & Frontend Developer
            </span>
          </div>
          <ul class="footer__links">
            <li>
              <a href="#service" class="footer__link">Service</a>
            </li>
            <li>
              <a href="#portfolio" class="footer__link">Portfolio</a>
            </li>
            <li>
              <a href="#contact" class="footer__link">Contact Me!</a>
            </li>
          </ul>
          <div class="footer__social">
            <a href="#" class="footer__social" target="_blank">
              <li class="uil uil-facebook-f"></li>
            </a>
            <a href="#" class="footer__social" target="_blank">
              <li class="uil uil uil-instagram"></li>
            </a>
            <a href="#" class="footer__social" target="_blank">
              <li class="uil uil-twitter"></li>
            </a>
          </div>
        </div>

        <p class="footer__copy">&#169; Puthy. All right reserved</p>
      </div>
    </footer>

    <!--==================== SCROLL TOP ====================-->
    <a href="" class="scrollup" id="scrollup">
      <i class="uil uil-arrow-up scrollup__icon"></i>
    </a>
    <!--==================== SWIPER JS ====================-->
    <script src="assets/js/swiper-bundle.min.js"></script>

    <!--==================== MAIN JS ====================-->
    <script src="assets/js/main.js"></script>
  </body>
</html>
