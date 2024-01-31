# readme

```
import React from "react";
import "./about.css";
import ME from "../../assets/me-about.jpg";
import { FaAward } from "react-icons/fa";
import { FiUser } from "react-icons/fi";
import { VscFolderLibrary } from "react-icons/vsc";
const About = () => {
  return (
    <section id="about">
      <h5>Get To Know</h5>
      <h2>About Me</h2>
      <div className="container about_container">
        <div className="about_me">
          <div className="about_me-image">
            <img src={ME} alt="about_me-image" />
          </div>
        </div>
        <div className="about_content">
          <div className="about_cards">
            <article className="about_card">
              <FaAward className="about_icon" />
              <h5>Experience</h5>
              <small>3+years working </small>
            </article>
            <article className="about_card">
              <FiUser className="about_icon" />
              <h5>Clients </h5>
              <small> 200+ worldwide </small>
            </article>
            <article className="about_card">
              <VscFolderLibrary className="about_icon" />
              <h5>Projects </h5>
              <small>80+ completed </small>
            </article>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt hic
            doloribus nesciunt dolor atque est assumenda vitae repudiandae
            perspiciatis quaerat dolorem perferendis necessitatibus odio quam,
            debitis voluptas ab quia officiis?
          </p>
          <a href="#contact" className="btn btn-primary">
            {" "}
            let's Talk{" "}
          </a>
        </div>
      </div>
    </section>
  );
};

export default About;

```
