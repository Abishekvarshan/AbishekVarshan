<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Tech Stack</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background-color: #0d1117;
      color: #fff;
      margin: 0;
      padding: 40px 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    h2 {
      font-size: 2rem;
      color: #58a6ff;
      margin-bottom: 20px;
    }

    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      max-width: 800px;
      background: #161b22;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 0 20px rgba(88, 166, 255, 0.2);
    }

    .tech-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .tech-item img {
      width: 70px;
      height: 70px;
      object-fit: contain;
      filter: drop-shadow(0 0 5px rgba(255, 255, 255, 0.2));
    }

    .tech-item span {
      margin-top: 10px;
      font-size: 0.9rem;
      color: #c9d1d9;
    }

    .tech-item:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 20px rgba(88, 166, 255, 0.3);
    }

    @media (max-width: 600px) {
      .tech-stack {
        padding: 20px;
      }
      .tech-item img {
        width: 60px;
        height: 60px;
      }
    }
  </style>
</head>
<body>
  <h2>🚀 My Tech Stack</h2>
  <div class="tech-stack">
    <div class="tech-item">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" />
      <span>GitHub</span>
    </div>
    <div class="tech-item">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="NodeJS" />
      <span>Node.js</span>
    </div>
    <div class="tech-item">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" />
      <span>Docker</span>
    </div>
    <div class="tech-item">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" alt="Kubernetes" />
      <span>Kubernetes</span>
    </div>
    <div class="tech-item">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" />
      <span>HTML5</span>
    </div>
    <div class="tech-item">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" />
      <span>CSS3</span>
    </div>
    <div class="tech-item">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" />
      <span>JavaScript</span>
    </div>
  </div>
</body>
</html>
