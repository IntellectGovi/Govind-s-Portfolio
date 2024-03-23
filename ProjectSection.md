 <section id="projects" class="projects">
      <h2 class="page-header">Projects</h2>
      <div class="project-container">
        <div class="project-card" id="project1">
          <div class="project-number project-number-left">01</div>
          <div class="project-content project-content-left">
            <div class="project-skill-container">
              <img class="project-skill" src="./images/stack/HTML.png" alt="" />
              <img class="project-skill" src="./images/stack/CSS.png" alt="" />
              <img
                class="project-skill"
                src="./images/stack/Javascript.svg"
                alt=""
              />
              <img
                class="project-skill"
                src="./images/stack/Tailwind.png"
                alt=""
              />
            </div>
            <h2 class="project-heading">Study Notion</h2>
            <p class="project-sub-heading">
              A Ed-Tech WebSite created with the help of MERN STACK
            </p>
            <div class="btn-group">
              <a href="https://github.com/IntellectGovi/router-project-studyNotation" target="_blank"><button class="btn-pink">Read More</button></a>
              <a href="https://studynotion-frontend.vercel.app/" target="_blank">
                <i title="Live Link" class="fa-solid fa-link icon"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="project-card" id="project2">
          <div class="project-number project-number-right">02</div>
          <div class="project-content project-content-right" style="margin-left: 150px;">
            <div class="project-skill-container">
              <img class="project-skill" src="./images/stack/HTML.png" alt="" />
              <img class="project-skill" src="./images/stack/CSS.png" alt="" />
              <img
                class="project-skill"
                src="./images/stack/Javascript.svg"
                alt=""
              />
              <img
                class="project-skill"
                src="./images/stack/Tailwind.png"
                alt=""
              />
            </div>
            <h2 class="project-heading">Modern Chair Shop</h2>
            <p class="project-sub-heading">
              Improved the Experience of buying the chairs online with beautiful animation.
            </p>
            <div class="btn-group">
              <a href="https://github.com/IntellectGovi/Modern-chair-store" target="_blank"><button class="btn-pink">Read More</button></a>
              <a href="https://intellectgovi.github.io/Modern-chair-store/" target="_blank">
                <i title="Live Link" class="fa-solid fa-link icon"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="project-card" id="project3">
          <div class="project-number project-number-left">03</div>
          <div class="project-content project-content-left">
            <div class="project-skill-container">
              <img class="project-skill" src="./images/stack/HTML.png" alt="" />
              <img class="project-skill" src="./images/stack/CSS.png" alt="" />
              <img
                class="project-skill"
                src="./images/stack/Javascript.svg"
                alt=""
              />
              <!-- <img class="project-skill" src="./images/stack/NextJsCircle.png" alt="" /> -->
              <img
                class="project-skill"
                src="./images/stack/Tailwind.png"
                alt=""
              />
              <!-- <img class="project-skill" src="./images/stack/Vercel.svg" alt="" /> -->
            </div>
            <h2 class="project-heading">Shopping App</h2>
            <p class="project-sub-heading">
              A Shopping app with beautiful animation created using Redux.
            </p>
            <div class="btn-group">
              <a href="https://github.com/IntellectGovi/ShopApp-Redux" target="_blank"><button class="btn-pink">Read More</button></a>
              <a href="https://shop-app-redux-phi.vercel.app/" target="_blank">
                <i title="Live Link" class="fa-solid fa-link icon"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="project-card" id="project4">
          <div class="project-number project-number-right">04</div>
          <div class="project-content project-content-right">
            <div class="project-skill-container">
              <img
                class="project-skill"
                src="./images/stack/NextJsCircle.png"
                alt=""
              />
              <img
                class="project-skill"
                src="./images/stack/Tailwind.png"
                alt=""
              />
              <img
                class="project-skill"
                src="./images/stack/Vercel.svg"
                alt=""
              />
            </div>
            <h2 class="project-heading">Tin-Dog</h2>
            <p class="project-sub-heading">A Website for pet owners to find a perfect match for their pets.</p>
            <div class="btn-group">
              <a href="https://github.com/IntellectGovi/router-project-studyNotation" target="_blank"><button class="btn-pink">Read More</button></a>
              <a href="https://intellectgovi.github.io/ting-dog-udemy/" target="_blank">
                <i title="Live Link" class="fa-solid fa-link icon" ></i>
              </a>
            </div>
          </div>
        </div>
      </div>

      <a href="https://github.com/IntellectGovi" target="_blank" class="repoLink"><button class="btn-pink">Want to See more ?</button></a>
    </section>



    <!----------------- PROJECT SECTION CSS ------------>

    .projects {
  margin-top: 4rem;
  background-color: #171616;
}
.project-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 3rem 0;
}
.page-header {
  padding-top: 30px;
  color:var(--bgOrange);
  text-align: center;
  font-size: 90px;
  font-family: hithere;
  letter-spacing: 8px;
}

.project-container {
  display: flex;
  flex-direction: column;
  gap: 120px;
}

.project-card {
  width: 80%;
  height: 510px;
  background-image: url(./projects/project1.png);
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  box-shadow: 0px 0px 40px #1f1f1f;
}
.project-card::after {
  content: "";
  color: #fff;
  position: absolute;
  background: #1f1f1f9a;
  z-index: 0;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  transform: scaleX(1);
}
.project-card::before {
  content: "";
  color: #fff;
  position: absolute;
  background: linear-gradient(45deg, #343d68, #343d68be, #343d687c);
  z-index: 1;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  transform: scaleX(0);
  transform-origin: left;
  transition: all 0.4s;
}
.project-card:hover::before {
  transform: scaleX(1);
}
.project-content {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  color: white;
  padding: 2em;
  bottom: 20%;
  position: absolute;
  z-index: 5;
  transition: all 0.4s;
}
.project-content-left {
  left: 10%;
}
.project-content-right {
  right: 10%;
}
.project-card:hover .project-content {
  scale: 1.1;
}
.project-heading {
  font-size: 50px;
  font-weight: bold;
  line-height: 3rem;
  font-family: landingFont;
  letter-spacing: 6px;
}
.project-sub-heading {
  font-size: 16px;
  width: 70%;
  font-family: landingFont;
  letter-spacing: 4px;
}

.btn-project {
  border: none;
  font-weight: 500;
}
.btn-project:hover {
  border: none;
}
.btn-group {
  display: flex;
  gap: 0.9rem;
  align-items: center;
}
.icon {
  cursor: pointer;
  font-size: 35px;
  transition: all 0.4s;
  color: #fff;
}
.icon:hover {
  color: #e84949;
}
.project-number {
  position: absolute;
  font-family: myfont;
  font-size: 200px;
  font-weight: 600;
  color: rgb(255, 255, 255);
  display: none;
  z-index: 10;
  transition-delay: 1s;
  transition: transform 2s;
}
.project-number-left {
  right: -40px;
  top: -45px;
}
.project-number-right {
  left: -40px;
  top: -45px;
}
.project-card:hover .project-number {
  display: block;
  color: rgb(255, 255, 255);
}
.project-skill-container {
  max-width: 60%;
  width: fit-content;
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  transition: all 0.2s;
  border-radius: 5px;
}

.project-skill {
  width: 40px;
}

#project1 {
  background-image: url(./images/projects/Project1.png);
}
#project2 {
  background-image: url(./images/projects/Project2.png);
  margin-left: 120px;
}
#project3 {
  background-image: url(./images/projects/Project3.png);
}
#project4 {
  background-image: url(./images//projects//Project4.png);
  margin-left: 120px;
}

.repoLink{
  display: flex;
  align-items: center;
  justify-content: center;
}

@media (max-width:1300px) {
  .page-header {
    padding-top: 30px;
    color: var(--bgOrange);
    text-align: center;
    font-size: 40px;
  }
  .project-container {
    padding: 5px;
    margin: 10px;
    gap: 60px;
  }
  .project-card {
    width: 100%;
    height: 300px;
  }
  .project-card {
    background-size: cover;
    background-position: center;
  }
  .project-content {
    scale: 0.5;
    bottom: 0;
    left: 0;
    right: 0;
    top: 0;
  }
  .project-content-left {
    left: 0;
  }
  .project-heading {
    font-size: 40px;
    width: 100%;
  }
  .project-sub-heading {
    width: 100%;
  }
  #project2 {
    margin-left: 0;
  }
  #project4 {
    margin-left: 0;
  }
  .project-skill-container {
    width: 100%;
  }
  .project-skill {
    width: 35px;
  }
  .project-card:hover .project-number {
    display: none;
  }
  .project-card:hover .project-content {
    scale: 0.55;
  }
}
/* Project Section End */