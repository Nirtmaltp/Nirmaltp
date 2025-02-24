import React from "react";
import { FaGithub, FaLinkedin, FaEnvelope } from "react-icons/fa";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gray-900 text-white flex flex-col items-center p-6">
      <header className="text-center mt-10">
        <h1 className="text-4xl font-bold">Your Name</h1>
        <p className="text-gray-400 mt-2">Web Developer | Designer | Freelancer</p>
      </header>

      <section className="mt-10 max-w-3xl text-center">
        <h2 className="text-2xl font-semibold">About Me</h2>
        <p className="text-gray-300 mt-4">
          Hi! I'm a passionate developer who loves creating stunning web applications. I have experience in frontend and backend technologies.
        </p>
      </section>

      <section className="mt-10 max-w-3xl">
        <h2 className="text-2xl font-semibold text-center">Portfolio</h2>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-6 mt-6">
          <div className="bg-gray-800 p-4 rounded-xl">
            <h3 className="text-lg font-semibold">Project 1</h3>
            <p className="text-gray-400">Description of your awesome project.</p>
          </div>
          <div className="bg-gray-800 p-4 rounded-xl">
            <h3 className="text-lg font-semibold">Project 2</h3>
            <p className="text-gray-400">Another great project you built.</p>
          </div>
        </div>
      </section>

      <section className="mt-10 text-center">
        <h2 className="text-2xl font-semibold">Contact</h2>
        <div className="flex gap-6 justify-center mt-4">
          <a href="https://github.com" className="text-gray-400 hover:text-white text-2xl">
            <FaGithub />
          </a>
          <a href="https://linkedin.com" className="text-gray-400 hover:text-white text-2xl">
            <FaLinkedin />
          </a>
          <a href="mailto:your.email@example.com" className="text-gray-400 hover:text-white text-2xl">
            <FaEnvelope />
          </a>
        </div>
      </section>
    </div>
  );
}
