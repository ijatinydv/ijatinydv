<div align="center">
  <div style="position: relative;">
    ```svg
    <svg fill="none" viewBox="0 0 850 400" width="850" height="400" xmlns="http://www.w3.org/2000/svg">
      <foreignObject width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml">
          <style>
            .container {
              width: 100%;
              height: 400px;
              background: linear-gradient(to bottom right, #1a1a1a, #2d2d2d);
              border-radius: 10px;
              display: flex;
              flex-direction: column;
              align-items: center;
              justify-content: center;
              font-family: system-ui;
              position: relative;
              overflow: hidden;
            }
            .name {
              font-size: 48px;
              color: #fff;
              text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
              margin-bottom: 10px;
              animation: glow 2s ease-in-out infinite alternate;
            }
            .title {
              font-size: 24px;
              color: #64ffda;
              margin-bottom: 20px;
            }
            .stats {
              display: flex;
              gap: 30px;
              color: #fff;
              font-size: 18px;
            }
            .grid {
              position: absolute;
              top: 0;
              left: 0;
              width: 100%;
              height: 100%;
              background: linear-gradient(
                90deg,
                rgba(255, 255, 255, 0.1) 1px,
                transparent 1px
              ),
              linear-gradient(
                rgba(255, 255, 255, 0.1) 1px,
                transparent 1px
              );
              background-size: 30px 30px;
              animation: grid 15s linear infinite;
            }
            @keyframes glow {
              from {
                text-shadow: 0 0 10px #64ffda;
              }
              to {
                text-shadow: 0 0 20px #64ffda, 0 0 30px #64ffda;
              }
            }
            @keyframes grid {
              0% {
                transform: translateY(0);
              }
              100% {
                transform: translateY(30px);
              }
            }
          </style>
          <div class="container">
            <div class="grid"></div>
            <div class="name">Jatin Kumar</div>
            <div class="title">Full Stack Developer • Tech Explorer</div>
            <div class="stats">
              <div>B.Tech 2nd Year</div>
              <div>•</div>
              <div>Web Developer</div>
              <div>•</div>
              <div>Creative Coder</div>
            </div>
          </div>
        </div>
      </foreignObject>
    </svg>
    ```
  </div>

  <br />

  ```typescript
  class Developer {
    name: string = 'Jatin Kumar';
    role: string = 'Full Stack Developer';
    location: string = 'India';
    education: string = 'B.Tech (2nd Year)';
    
    skills: Skills = {
      languages: ['JavaScript', 'HTML', 'CSS'],
      frameworks: ['React', 'Node.js', 'Express'],
      styling: ['Tailwind CSS', 'GSAP'],
      database: ['MongoDB'],
      currentlyLearning: ['Advanced React', 'System Design']
    };

    get contact(): Contact {
      return {
        linkedin: 'jatin-kumar-a5655b30a',
        portfolio: 'coming-soon...'
      };
    }
  }
  ```

  <div align="left">
    
  ## 🚀 Featured Projects
    
  <table>
    <tr>
      <td>
        <a href="#">
          <img src="https://img.shields.io/badge/Hindi_Sikhiye-Interactive_Learning-4d94ff?style=for-the-badge&logoColor=white" alt="Hindi Sikhiye"/>
        </a>
        <p>Learn Hindi through interactive lessons and quizzes.</p>
        <p><strong>Tech:</strong> React • Node.js • MongoDB</p>
      </td>
      <td>
        <a href="#">
          <img src="https://img.shields.io/badge/Capture_The_Flag-Gaming_Platform-ff4d4d?style=for-the-badge&logoColor=white" alt="CTF"/>
        </a>
        <p>Competitive coding challenges with real-time updates.</p>
        <p><strong>Tech:</strong> React • GSAP • Express</p>
      </td>
    </tr>
  </table>

  ## 💻 Tech Stack
  ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
  ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
  ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
  ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
  ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
  
  ## 📈 Stats
  <img src="https://streak-stats.demolab.com?user=ijatinydv&theme=tokyonight&hide_border=true&border_radius=10" height="150" alt="streak graph"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ijatinydv&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact" height="150" alt="languages graph"/>

</div>

<div align="center">
  
  ### 🤝 Let's Connect!
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jatin-kumar-a5655b30a/)
  
  ---
  <sub>Last Updated: 2024-07-27</sub>
</div>
