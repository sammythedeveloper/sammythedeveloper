
keeping it simple😉
          <svg width="1200" height="500" viewBox="0 0 1200 500" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <linearGradient id="neon" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00FF88"/>
      <stop offset="50%" stop-color="#00D4FF"/>
      <stop offset="100%" stop-color="#7C4DFF"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur">
        <animate attributeName="stdDeviation" values="3;6;3" dur="3s" repeatCount="indefinite"/>
      </feGaussianBlur>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="#05060a"/>

  <!-- Animated grid -->
  <g stroke="#111827" stroke-width="1" opacity="0.6">
    <g>
      <animateTransform attributeName="transform"
                        type="translate"
                        from="0 0"
                        to="0 20"
                        dur="6s"
                        repeatCount="indefinite"/>
      <path d="M0 100 H1200"/>
      <path d="M0 200 H1200"/>
      <path d="M0 300 H1200"/>
      <path d="M0 400 H1200"/>
    </g>

    <g>
      <animateTransform attributeName="transform"
                        type="translate"
                        from="0 0"
                        to="20 0"
                        dur="8s"
                        repeatCount="indefinite"/>
      <path d="M200 0 V500"/>
      <path d="M400 0 V500"/>
      <path d="M600 0 V500"/>
      <path d="M800 0 V500"/>
      <path d="M1000 0 V500"/>
    </g>
  </g>

  <!-- Rotating glow ring -->
  <circle cx="600" cy="250" r="180"
          fill="none"
          stroke="url(#neon)"
          stroke-width="2"
          opacity="0.7"
          filter="url(#glow)">
    <animateTransform attributeName="transform"
                      type="rotate"
                      from="0 600 250"
                      to="360 600 250"
                      dur="20s"
                      repeatCount="indefinite"/>
  </circle>

  <!-- Pulsing title -->
  <text x="50%" y="48%" text-anchor="middle"
        font-family="JetBrains Mono, monospace"
        font-size="72"
        font-weight="700"
        fill="url(#neon)"
        filter="url(#glow)">
    SAMSON D.
    <animate attributeName="opacity"
             values="0.7;1;0.7"
             dur="2.5s"
             repeatCount="indefinite"/>
  </text>

  <!-- Subtitle -->
  <text x="50%" y="58%" text-anchor="middle"
        font-family="JetBrains Mono, monospace"
        font-size="20"
        fill="#9CA3AF"
        letter-spacing="2">
    FULL STACK DEVELOPER • AI ENTHUSIAST • AWS BUILDER
  </text>

  <!-- Tagline floating -->
  <text x="50%" y="66%" text-anchor="middle"
        font-family="JetBrains Mono, monospace"
        font-size="16"
        fill="#4B5563">
    building systems that feel alive on the web
    <animate attributeName="y"
             values="66%;65.5%;66%"
             dur="4s"
             repeatCount="indefinite"/>
  </text>

</svg>
---
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=00FF88&center=true&vCenter=true&width=600&lines=%24+whoami+%3E+SamtheDev;Full+stack+web+developer;Building+clean+web+application+and+modern+full+stack+software;he%2Fhim+%7C+open+to+collabs+%F0%9F%9F%A2+%F0%9F%98%8E+%F0%9F%8E%AF)](https://git.io/typing-svg)

</div>

I’m a Full Stack Developer and AI enthusiast who enjoys building and deploying web applications on AWS. I’m currently focused on working on my own projects while continuously learning new technologies. My main interest lies in creating clean, functional applications with strong attention to user interface and user experience design.
     

* 🌍  I'm based in Toronto
* ✉️  You can contact me at samsondev3@gmail.com
* 🤝  I'm open to collaborating on Projects 
* 🕸️  Checkout my Portfolio site here https://sam21.framer.ai/




# 💻 Tech Stack:
 ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)  ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)  ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/postgresql-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
 ![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-%23FF9900.svg?style=for-the-badge&logo=amazon-ec2&logoColor=white) ![Amazon S3](https://img.shields.io/badge/Amazon%20S3-%23569A31.svg?style=for-the-badge&logo=amazon-s3&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-%23FF9900.svg?style=for-the-badge&logo=aws-lambda&logoColor=white)![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-%236464FF.svg?style=for-the-badge&logo=stripe&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=jsonwebtokens&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Framer](https://img.shields.io/badge/Framer-black?style=for-the-badge&logo=framer&logoColor=blue)  ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-%23412991.svg?style=for-the-badge&logo=openai&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white) ![ChatGPT](https://img.shields.io/badge/ChatGPT-00A67E?style=for-the-badge&logo=openai&logoColor=white) 
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
 




