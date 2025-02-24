// src/App.js
import React from "react";
import { FaGithub, FaLinkedin, FaEnvelope } from "react-icons/fa";
import "./App.css";

export default function App() {
  return (
    <div className="container">
      <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer | Freelancer</p>
      </header>

      <section className="about">
        <h2>About Me</h2>
        <p>
          Hi! I'm a passionate developer who loves creating stunning web applications. I have experience in frontend and backend technologies.
        </p>
      </section>

      <section className="portfolio">
        <h2>Portfolio</h2>
        <div className="project">
          <h3>Project 1</h3>
          <p>Description of your awesome project.</p>
        </div>
        <div className="project">
          <h3>Project 2</h3>
          <p>Another great project you built.</p>
        </div>
      </section>

      <section className="contact">
        <h2>Contact</h2>
        <div className="social-links">
          <a href="https://github.com" className="icon">
            <FaGithub />
          </a>
          <a href="https://linkedin.com" className="icon">
            <FaLinkedin />
          </a>
          <a href="mailto:your.email@example.com" className="icon">
            <FaEnvelope />
          </a>
        </div>
      </section>
    </div>
  );
}

// src/App.css
.container {
  text-align: center;
  font-family: Arial, sans-serif;
  background-color: #1a1a1a;
  color: white;
  padding: 20px;
}

header {
  margin-top: 20px;
}

.about, .portfolio, .contact {
  margin-top: 40px;
}

.project {
  background: #333;
  padding: 10px;
  margin: 10px;
  border-radius: 8px;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 15px;
  font-size: 24px;
}

.icon {
  color: white;
  transition: color 0.3s;
}

.icon:hover {
  color: #00aced;
}
