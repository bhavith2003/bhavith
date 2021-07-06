<template>
  <body>
  <nav>
    <div class="header inner">

      <h1>RESUME</h1>


    </div>

  </nav>
  <div class="image" style="margin: 2.5rem">


    <img src="../resume/res.jpeg" height="154" width="138" alt="photo"/></div>
  <main class="container">
    <section class="profile">
      <div class="left">
        <ul style="list-style-type: none">
          <li>{{ profile.first_name }} {{ profile.last_name }}</li>
          <li>{{ profile.profession }}</li>

        </ul>
      </div>
      <div class="right">
        <ul class="contact" style="list-style-type: none">
          <li>
            <svg viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg" width="15" height="15">
              <path
                  d="M4.72.5H2.5a2 2 0 00-2 2v2c0 5.523 4.477 10 10 10h2a2 2 0 002-2v-1.382a1 1 0 00-.553-.894l-2.416-1.208a1 1 0 00-1.396.578l-.297.893a1.21 1.21 0 01-1.385.804A6.047 6.047 0 013.71 6.547a1.21 1.21 0 01.804-1.385l1.108-.37a1 1 0 00.654-1.19L5.69 1.257A1 1 0 004.72.5z"
                  stroke="currentColor"></path>
            </svg>
            :{{ profile.phone }}
          </li>

          <li>
            <svg viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg" width="15" height="15">
              <path
                  d="M5.5 11.493l.416-.278a.5.5 0 00-.416-.222v.5zm2 2.998l-.416.277a.5.5 0 00.832 0l-.416-.277zm2-2.998v-.5a.5.5 0 00-.416.222l.416.278zm-4.416.277l2 2.998.832-.555-2-2.998-.832.555zm2.832 2.998l2-2.998-.832-.555-2 2.998.832.555zM9.5 11.993h4v-1h-4v1zm4 0c.829 0 1.5-.67 1.5-1.5h-1c0 .277-.223.5-.5.5v1zm1.5-1.5V1.5h-1v8.994h1zM15 1.5c0-.83-.671-1.5-1.5-1.5v1c.277 0 .5.223.5.5h1zM13.5 0h-12v1h12V0zm-12 0C.671 0 0 .67 0 1.5h1c0-.277.223-.5.5-.5V0zM0 1.5v8.993h1V1.5H0zm0 8.993c0 .83.671 1.5 1.5 1.5v-1a.499.499 0 01-.5-.5H0zm1.5 1.5h4v-1h-4v1zM5 8h5V7H5v1zM4 5h7V4H4v1z"
                  fill="currentColor"></path>
            </svg>
            :{{ profile.email }}
          </li>
        </ul>
        <ul class="socials" style="list-style-type: none">
          <li class="facebook">
            <a href="https://www.facebook.com/bhavith.gonuguntla.5/">
              <i>
                <svg viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg" width="15" height="15">
                  <path d="M7.5 14.5a7 7 0 110-14 7 7 0 010 14zm0 0v-8a2 2 0 012-2h.5m-5 4h5"
                        stroke="currentColor"></path>
                </svg>
              </i>
            </a>
          </li>
          <li class="ig">
            <a href="https://www.instagram.com/">
              <i>
                <svg viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg" width="15" height="15">
                  <path
                      d="M11 3.5h1M4.5.5h6a4 4 0 014 4v6a4 4 0 01-4 4h-6a4 4 0 01-4-4v-6a4 4 0 014-4zm3 10a3 3 0 110-6 3 3 0 010 6z"
                      stroke="currentColor"></path>
                </svg>
              </i>
            </a>
          </li>
          <li class="linkedin">
            <a href="https://www.linkedin.com/in/bhavith-g-85394180/">
              <i>
                <svg viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg" width="15" height="15">
                  <path
                      d="M4.5 6v5m6 0V8.5a2 2 0 10-4 0V11 6M4 4.5h1M1.5.5h12a1 1 0 011 1v12a1 1 0 01-1 1h-12a1 1 0 01-1-1v-12a1 1 0 011-1z"
                      stroke="currentColor"></path>
                </svg>
              </i>
            </a>

          </li>
        </ul>

      </div>
    </section>

  </main>
  <section class="about">
    <h2 class="section__heading">About Me !</h2>
    <div class="content">
      <div id="left">
        <p>Myself Bhavith.<br>I am currently taking Undergarduate degree in Computer science<br>I have some skills on
          HTML,Python,Java Development<br>Aspiring to become a Data scientist Oneday.</p>
      </div>
    </div>
    <div id="right">
      <p>
        <span style="font-weight: bold">Name: </span>
        <span>
            {{ profile.first_name }}
          </span>
      </p>
      <p>
        <span style="font-weight: bold">Date of birth </span>
        <span>{{ profile.DOB }}</span>
      </p>
      <p>
        <span style="font-weight: bold">Langages Known </span>
        <span>{{ profile.Languages }}</span>
      </p>
      <p>
        <span style="font-weight: bold">Nationality </span>
        <span>{{ profile.Nationality }}</span>
      </p>
      <p>
        <span style="font-weight: bold">Intrests </span>
        <span>{{ profile.Intrests }}</span>
      </p>
    </div>


  </section>
  <section class="skills" style="background-color: #DCE1E3">
    <h1 class="section__heading"></h1>
    <div class="content">


      <div class="heading">
        <h5>Education</h5>
      </div>
      <div id="timeline">
        <p>
          <span style="font-weight: bold">Secondary Education:  </span>
          <span>{{ profile.Secondary_school }},{{ profile.ss_year }}</span>
        </p>
        <p>
          <span style="font-weight: bold">Higher Secondary:  </span>
          <span>{{ profile.Higher_secondary }},{{ profile.hh_year }}</span>
        </p>
        <p>
          <span style="font-weight: bold">Degree:  </span>
          <span>{{ profile.Degree }},{{ profile.dd_year }}</span>
        </p>
      </div>
    </div>


  </section>
  <section class="skills">
    <div class="headings">
      <h5>Skills</h5>
    </div>
    <ul class="skills" style="list-style-type: none">
      <li>Html And Css</li>
      <li>Python</li>
      <li>Java</li>
      <li>Sql Server</li>
    </ul>

  </section>
  <section class="achievements">
    <div class="heading">
      <h5>Achievements</h5>
    </div>
    <ul class="my_achievements">
      <li>{{ achievements.ac1 }}</li>
      <li>{{ achievements.ac2 }}</li>
      <li>{{ achievements.ac3 }}</li>
      <li>{{ achievements.ac4 }}</li>

    </ul>
  </section>
  <section class="Capabilities">
    <div class="heading">
      <h5>Capabilities</h5>
    </div>
    <ul class="my_Capabilities">
      <li>{{ Capabilities.c1 }}</li>
      <li>{{ Capabilities.c2 }}</li>
      <li>{{ Capabilities.c3 }}</li>
      <li>{{ Capabilities.c4 }}</li>
    </ul>
  </section>
  <section class="certifications">
    <div class="heading">
      <h5>Certifications</h5>
    </div>
    <ul class="my_certifications">
      <li>
        <a href="https://coursera.org/share/b4c87323d0aeab97b20b119f32da0300">Getting Started with Python</a>
      </li>
      <li>
        <a href="https://www.udemy.com/certificate/UC-cf42a923-439e-4d4f-9f55-f6d37dc29da2/">Complete Python
          Bootcamp</a>
      </li>
      <li>
        <a href="https://courses.edx.org/certificates/95d69930c8e54a29894e5e86b0a6cf00">Human-Computer Interaction</a>

      </li>
      <li>
        <a href="https://coursera.org/share/3cecdec32daa47f018825ee3bd9c7211">Introduction to Relational Database and
          SQL</a>
      </li>
      <li>
        <a href="https://coursera.org/share/2cabb26bcad0d2a56bcf0b41ae132e9d">Performing Data Definition and
          Manipulation in SQL</a>
      </li>
      <li>
        <a href="https://coursera.org/share/04e23f90fbe422e23483d68fe9cff259">Excel Skills for Business: Essentials</a>
      </li>

    </ul>
  </section>

  </body>
</template>


<script>

export default {
  data() {
    return {
      profile: {
        first_name: 'Bhavith',
        last_name: 'chowdary',
        profession: 'Junior Developer',
        phone: 7893487626,
        email: 'Bhavithchowdary975@gmail.com',
        About: 'Junior Developer and Javascript Enthusiast, Who Likes Building Things In Javascript',
        DOB: '09 February 2000',
        Languages: 'English - Telugu-Hindi',
        Nationality: 'Indian',
        Intrests: 'Games,Travel',
        Secondary_school: 'Westberry International School',
        ss_year: '2017',
        Higher_secondary: 'Sri chaitaya Junior college',
        hh_year: '2017 - 2019',
        Degree: 'Bachelor of Computer science-Hindus#DCE1E3 Unviersity',
        dd_year: '2019 - 2023'


      },
      achievements: {
        ac1: 'Football Interschool championship winner',
        ac2: '2nd place at an technical competetion',
        ac3: 'Department Representative at University',
        ac4: 'Co-ordinater for our college Fest'


      },
      Capabilities: {
        c1: 'Adapt to Situations',
        c2: 'Versatile',
        c3: 'Self-motivated',
        c4: 'Responsibility'
      }
    }
  }

}
</script>


<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-align: left;
}

h1, h2, h3 {
  margin: 0;
  line-height: 1;
}

body {
  font-family: Calibri;
  background: #DCE1E3;
  -webkit-font-smoothing: antialiased;
  padding-bottom: 4rem;

}

nav {
  background: #9fa8a3;
  padding: 1.6rem 0;

}

nav.inner {
  text-align: center;
}

section.profile {
  background: #DCE1E3;
  display: flex;
  align-items: center;
  padding: 1.6rem;
}

section.profile .left {
  font-weight: bold;
  font-size: x-large;
  flex: 2;
  display: flex;
  margin: 1rem;
}

section.profile .right {
  flex: 1;
}

section.profile .right ul.contact li i {

  padding: 2px;
  font-size: 18px;
  margin-right: 0.3rem;
  font-weight: bold;
}

section.profile .right ul.socials {
  display: flex;
  align-items: center;
  list-style-type: none;
}

section.profile .right ul.socials li {
  margin-right: 0.8rem;
}

section.profile .right ul.socials li a {
  display: inline-block;
  width: 36px;
  height: 36px;
  border-radius: 50%;
  color: darkblue;
  line-height: 36px;
  text-align: center;
}

section.profile .right ul.socials li a:hover {
  box-shadow: 10px 5px 3px black;
  transform: translateY(-0.25em);
}

.content #left p {

  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 16rem;

}


.about .section__heading {
  font-size: 16px;
  font-weight: 500;
  color: grey;
  margin-bottom: 3rem;
  text-shadow: 0 0 1px rgba(40, 54, 95, 0.1);
  position: relative;


}

section {
  padding: 3rem;
}

#right p span {
  line-height: 1.6;
  font-size: 14px;
  color: black;
  letter-spacing: 0.1px;
  margin-bottom: 1rem;

}

#right p span:nth-child(1) {
  width: 130px;
  float: left;
  font-weight: 500;
  padding-right: 10px;
  display: block;
  position: relative;
}

#right p span:nth-child(2) {
  padding-left: 150px;
  display: block;
}

#right p span:nth-child(1):after {
  content: ":";
  position: absolute;
  right: 0;
  top: 0;
}


.about {
  background-color: #DCE1E3;
}


section.skills .content .heading {
  margin-bottom: 2rem;
}

section.skills #timeline p span {
  text-align: left;
}


section.skills .content .heading h5 {
  font-size: 16px;
  margin-top: 0.5rem;
  color: grey;
}


section.skills .headings h5 {
  font-size: 16px;
  margin-top: 0.5rem;
  color: grey;
  background-color: #DCE1E3;
}

section.skills .skills {
  background-color: #DCE1E3;
}

section.skills {
  background-color: #DCE1E3;
}

section.achievements {
  background-color: #DCE1E3;
}

section.achievements .heading h5 {
  font-size: 16px;
  margin-top: 0.5rem;
  color: grey;
  background-color: #DCE1E3;
}

section.achievements .my_achievements {
  background-color: #DCE1E3;
  list-style-type: none;
}

section.Capabilities {
  background-color: #DCE1E3;
}

section.Capabilities .heading h5 {
  font-size: 16px;
  margin-top: 0.5rem;
  color: grey;
  background-color: #DCE1E3;

}

section.Capabilities .my_Capabilities {
  background-color: #DCE1E3;
  list-style-type: none;
}

section.certifications {
  background-color: #DCE1E3;
}

section.certifications .heading h5 {
  font-size: 16px;
  margin-top: 0.5rem;
  color: grey;
  background-color: #DCE1E3;

}

section.certifications .my_certifications {
  background-color: #DCE1E3;
  list-style-type: none;

}

section.certifications .my_certifications a {
  color: blue;

}

section.certifications .my_certifications a:hover {
  color: darkmagenta;
}


</style>
