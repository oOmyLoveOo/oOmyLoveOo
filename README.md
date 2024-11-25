import React from 'react';

const GitHubProfile = () => {
  return (
    <div className="markdown-body max-w-4xl mx-auto p-4">
      <div className="text-center mb-8">
        <h1 className="text-3xl font-bold flex items-center justify-center gap-2">
          Hi, I'm Wuke Zhang
          <img 
            src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" 
            alt="wave" 
            className="w-8 h-8"
          />
        </h1>
        
        <p className="text-lg text-gray-600 mt-4">
          Front-End Developer in Training | Aspiring MERN Full-Stack Developer | 
          Passionate about Continuous Learning | Solving Problems Creatively
        </p>
      </div>

      <section className="mb-8">
        <h2 className="text-2xl font-bold flex items-center gap-2 mb-4">
          <img 
            src="https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" 
            alt="about me" 
            className="w-8 h-8"
          />
          About Me
        </h2>
        <ul className="list-disc pl-6 space-y-2">
          <li>🌱 <strong>In training</strong> as a Full-Stack Developer specializing in the <strong>MERN stack</strong></li>
          <li>🛠️ Working on <strong>personal projects</strong> to strengthen technical skills</li>
          <li>🎓 Passionate about <strong>continuous learning</strong> and problem-solving</li>
          <li>💼 Seeking opportunities as an <strong>intern</strong> or in a professional environment</li>
          <li>🌟 Focused on creating functional and attractive applications</li>
        </ul>
      </section>

      <section className="mb-8">
        <h2 className="text-2xl font-bold flex items-center gap-2 mb-4">
          <img 
            src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" 
            alt="skills" 
            className="w-8 h-8"
          />
          Technical Skills
        </h2>
        
        <div className="space-y-6">
          <div>
            <h3 className="text-xl font-semibold mb-2">Languages</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-yellow-100 text-yellow-800 rounded">JavaScript</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">C++ (In Progress)</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">TypeScript (In Progress)</span>
              <span className="px-3 py-1 bg-orange-100 text-orange-800 rounded">Rust (Desired)</span>
            </div>
          </div>

          <div>
            <h3 className="text-xl font-semibold mb-2">Front-End Development</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-red-100 text-red-800 rounded">HTML5</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">CSS3</span>
              <span className="px-3 py-1 bg-cyan-100 text-cyan-800 rounded">React</span>
              <span className="px-3 py-1 bg-teal-100 text-teal-800 rounded">TailwindCSS</span>
            </div>
          </div>

          <div>
            <h3 className="text-xl font-semibold mb-2">Back-End Development</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">Node.js (In Progress)</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">Express.js (In Progress)</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">MongoDB (In Progress)</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">MySQL</span>
            </div>
          </div>

          <div>
            <h3 className="text-xl font-semibold mb-2">Software & Tools</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-orange-100 text-orange-800 rounded">Git</span>
              <span className="px-3 py-1 bg-gray-100 text-gray-800 rounded">GitHub</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">VS Code</span>
              <span className="px-3 py-1 bg-cyan-100 text-cyan-800 rounded">Docker</span>
              <span className="px-3 py-1 bg-gray-100 text-gray-800 rounded">WordPress</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">Cisco</span>
            </div>
          </div>

          <div>
            <h3 className="text-xl font-semibold mb-2">Operating Systems</h3>
            <div className="flex flex-wrap gap-2">
              <span className="px-3 py-1 bg-yellow-100 text-yellow-800 rounded">Linux</span>
              <span className="px-3 py-1 bg-orange-100 text-orange-800 rounded">Ubuntu</span>
              <span className="px-3 py-1 bg-blue-100 text-blue-800 rounded">Windows</span>
            </div>
          </div>
        </div>
      </section>

      <section className="mb-8">
        <h2 className="text-2xl font-bold flex items-center gap-2 mb-4">
          <img 
            src="https://github.com/0xAbdulKhalid/0xAbdulKhalid/raw/main/assets/mdImages/handshake.gif" 
            alt="connect" 
            className="w-8 h-8"
          />
          Connect with me
        </h2>
        <div className="flex flex-wrap gap-4">
          <a href="mailto:wuke.zhang@example.com" className="text-red-600 hover:text-red-800">
            <img src="https://img.shields.io/badge/gmail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
          </a>
          <a href="https://github.com/WukeZhang" className="text-gray-800 hover:text-gray-600">
            <img src="https://img.shields.io/badge/github-%23181717.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
          </a>
          <a href="https://www.linkedin.com/in/WukeZhang/" className="text-blue-600 hover:text-blue-800">
            <img src="https://img.shields.io/badge/linkedin-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
          </a>
          <a href="https://wa.me/1234567890" className="text-green-600 hover:text-green-800">
            <img src="https://img.shields.io/badge/WhatsApp-%2325D366.svg?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
          </a>
        </div>
      </section>

      <footer className="text-center mt-8">
        <h2 className="text-2xl font-bold">Thank you for visiting my profile! 🌟</h2>
      </footer>
    </div>
  );
};

export default GitHubProfile;
