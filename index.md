



/* Project Section Start  */

/* Skills Section Start */

.skills{
  height: 100vh;
  width: 100%;
  padding-top: 3.3rem;
}

.skills h1{
  padding-top: 30px;
  color:var(--bgOrange);
  text-align: center;
  font-size: 90px;
  font-family: hithere;
  letter-spacing: 8px;
}

.stack{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 8rem;
  padding: 2rem 12rem;
}

.stack img{
  height: 100px;
  gap: 23px;
  cursor:pointer;
}

.stack img:hover{
  transform: scale(1.2,1.2);
  transition: all 0.5s ease;
}

.skills-logo {
  width: 90px;
  transition: all 0.5s;
}
.skills-logo:hover {
  scale: 1.2;
}


@media (max-width: 1300px) {
  .skills-container {
    margin: 0;
    padding: 2em;
    flex-direction: column;
  }
  .skill-heading {
    font-size: 40px;
    font: bold;
  }
  .caps {
    font-size: 60px;
  }
  .skill-container-left {
    width: 100%;
  }
  .skill-container-right {
    width: 100%;
  }
  .skills-logo {
    width: 50px;
  }
  .skill-fade-text {
    display: none;
  }
  .skill-subHeading {
    width: 100%;
  }
  .skill-heading::after {
    bottom: 9%;
  }
}
/* Skills Section End */

/* Contact Us Start */


.contactus-container {
  width: 100%;
  background-color: #171616;
  margin-top: -12px;
}
.contactus-heading {
  width: fit-content;
  font-family: hiThere;
  margin: 0 auto;
  padding-top: 2rem;
  font-size: 5em;
  text-align: center;
  color:white;
  letter-spacing: 4px;
}

.contactus-heading:hover{
  color: #FF00FF;
  transition: all 0.2s linear;
  cursor: pointer;
}
.submit-button{
  display: flex;
  align-items: center;
  justify-content: center;
}

@media (max-width: 1300px) {
  .contactus-heading {
    font-size: 40px;
    text-align: center;
    padding: 15px 10px;
  }
  .contactus-sub-heading {
    font-size: 20px;
    padding: 0 10px;
    text-align: center;
  }
  .form {
    width: 100%;
    margin: 0;
    align-items: center;
  }
  .formfield-container {
    display: flex;
    align-items: center;
    width: 90%;
  }
  .formfield {
    width: 90%;
  }
}
/* Contact Us End */

/* Footer Start */
footer {
  position: relative;
  margin-top: -1px;
  background: #171616;
  padding-top: 5rem;
  padding-bottom: 0rem;
  padding: 5rem;
}


.footer-wrapper {
  display: flex;
  gap: 1rem;
  padding: 1.2rem;
  align-items: center;
  justify-content: space-between;
}
.link-wrapper {
  display: flex;
  gap: 1.2rem;
}
.link-wrapper div a {
  font-family: landingFont;
  letter-spacing: 03px;
  color: white;
  text-decoration: none;
  transition: all 0.6s;
}

.link-wrapper div a:hover {
  color: #FF00FF;
  text-decoration: none;
}
.icon-wrapper {
  display: flex;
  gap: 1rem;
}

.icon-wrapper a:hover{
  color: #FF00FF;
}
@media (max-width: 1300px) {
  footer {
    padding: 0.5rem;
  }
  .footer-wrapper {
    flex-direction: column;
    gap: 1.5rem;
  }
  .footer-faded-text {
    display: none;
  }
}
/* Footer End */