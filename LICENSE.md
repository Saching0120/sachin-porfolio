import React from "react";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-100 via-white to-blue-50 p-6 font-sans">
      <header className="text-center py-12">
        <img 
          src="/mnt/data/WhatsApp Image 2024-12-07 at 12.02.06 PM.jpeg" 
          alt="Sachin Sharma" 
          className="w-40 h-40 rounded-full mx-auto shadow-lg border-4 border-white"
        />
        <h1 className="text-5xl font-extrabold text-blue-900 drop-shadow-sm mt-4">Sachin Sharma</h1>
        <p className="text-xl text-blue-700 mt-2">Teacher | IoT Developer | Designer | Content Creator | Video Editor | YouTuber</p>
        <p className="mt-4">
          <a href="https://www.linkedin.com/in/sachin0120" target="_blank" rel="noopener noreferrer" className="text-blue-600 hover:underline">LinkedIn Profile</a>
        </p>
      </header>

      <section className="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl p-8 mb-10">
        <h2 className="text-3xl font-bold text-blue-800 mb-4">About Me</h2>
        <p className="text-gray-700 leading-relaxed">
          I am a dedicated educator with a deep interest in technology and innovation. Currently teaching Computer Applications and IT to undergraduate students at Jammu University, I have been shaping young minds with practical knowledge and hands-on skills. After completing my MCA from Jammu University in 2021, I took on the role of a guest lecturer at GDC Pouni, where I continue to share my passion for computing.
          <br /><br />
          I believe in continuous learning and keep myself updated with emerging trends in information technology. My teaching approach focuses on blending theory with practical implementation, enabling students to better understand concepts and apply them in real-world scenarios.
          <br /><br />
          Outside the classroom, I engage in tech-driven projects and content creation. I design digital content, edit educational and promotional videos, and manage a YouTube channel that shares insights on technology, IoT, and academic topics. I'm passionate about inspiring students and viewers to explore new technological frontiers.
          <br /><br />
          My creative side finds expression in visual design, combining aesthetics with purpose. As a multi-disciplinary creator, I aim to merge my skills in education, engineering, and media to make technology more accessible and impactful.
        </p>
      </section>

      <section className="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl p-8 mb-10">
        <h2 className="text-3xl font-bold text-blue-800 mb-4">Skills</h2>
        <ul className="list-disc list-inside text-gray-700 leading-loose">
          <li>Teaching Computer Applications & IT (UG level)</li>
          <li>IoT Systems Design & Development</li>
          <li>Educational & Technical Content Creation</li>
          <li>Professional Video Editing</li>
          <li>Creative Graphic Designing</li>
          <li>YouTube Channel Management & Engagement</li>
          <li>Workshop & Seminar Coordination</li>
          <li>Effective Communication & Presentation</li>
        </ul>
      </section>

      <section className="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl p-8 mb-10">
        <h2 className="text-3xl font-bold text-blue-800 mb-4">Projects</h2>
        <ul className="text-gray-700 space-y-4">
          <li>
            <strong>IoT-based Smart Agriculture System:</strong> A real-time monitoring solution that provides email and SMS notifications during anomalies in forest or farm areas, helping farmers stay informed and protected. This project is capable of detecting soil moisture, temperature, and unauthorized human presence, enhancing farm security and yield.
          </li>
          <li>
            <strong>IoT Environmental Monitoring Dashboard:</strong> A web-based dashboard that visualizes real-time environmental data such as air quality, humidity, and light intensity, sourced from Arduino and Raspberry Pi sensors, useful for urban and rural eco-surveillance.
          </li>
          <li>
            <strong>Interactive Python Tutorials:</strong> A YouTube-based series teaching fundamental and advanced Python concepts for students, featuring real-world applications and interactive coding demos.
          </li>
          <li>
            <strong>Smart Attendance System with RFID:</strong> A prototype system using RFID and IoT to automate attendance marking for students and faculty, reducing manual errors and time.
          </li>
        </ul>
      </section>

      <section className="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl p-8 mb-10">
        <h2 className="text-3xl font-bold text-blue-800 mb-4">Education</h2>
        <p className="text-gray-700">Master of Computer Applications (MCA), Jammu University – 2021</p>
      </section>

      <section className="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl p-8">
        <h2 className="text-3xl font-bold text-blue-800 mb-4">Contact</h2>
        <p className="text-gray-700 text-lg">
          Email: <a href="mailto:sachingud2000@gmail.com" className="text-blue-600 hover:underline">sachingud2000@gmail.com</a>
        </p>
      </section>

      <footer className="text-center text-gray-600 mt-12 text-sm">
        <p>&copy; {new Date().getFullYear()} Sachin Sharma. All rights reserved.</p>
      </footer>
    </div>
  );
}
