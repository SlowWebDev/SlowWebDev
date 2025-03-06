<div align="center" style="display: flex; align-items: center; justify-content: center; gap: 20px;">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=35&duration=3000&pause=1000&color=6B4BFF&center=false&vCenter=true&multiline=true&repeat=false&width=800&height=140&lines=Full+Stack+Web+Developer;Backend+Specialist;Crafting+Digital+Experiences" alt="Typing SVG" />
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="250" alt="Coding Animation" style="border-radius: 10px;"/>
</div>

<br/>

<h2 align="center">
  <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="30" height="30">
  Tech Mastery
</h2>

<div align="center" style="margin: 30px 0">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="60" alt="JavaScript"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="60" alt="TypeScript"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="60" alt="Node.js"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="60" alt="React"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="60" alt="Express"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="60" alt="MySQL"/>
</div>

<h2 align="center">
  Development Philosophy
</h2>

```typescript
interface Developer {
  name: string;
  title: string;
  skills: string[];
  focus: string[];
  currentProject: string;
}

const profile: Developer = {
  name: "Slow ",
  title: "Full Stack Web Developer",
  skills: [
    "JavaScript",
    "TypeScript",
    "Node.js",
    "React.js",
    "Database "
  ],
  focus: [
    "Building Scalable APIs",
    "Backend Development",
    "Clean Code",
    "Performance Optimization"
  ],
  currentProject: "Building Modern Web Applications"
};
```

<h2 align="center">
  Project Analytics
</h2>

<div align="center">
  <img width="49%" height="200px" src="https://github-readme-stats.vercel.app/api?username=SlowWebDev&show_icons=true&count_private=true&hide_border=true&title_color=6B4BFF&icon_color=6B4BFF&text_color=c9d1d9&bg_color=0d1117&ring_color=6B4BFF" alt="GitHub Stats"/> 
  <img width="49%" height="200px" src="https://github-readme-streak-stats.herokuapp.com/?user=SlowWebDev&hide_border=true&stroke=6B4BFF&ring=6B4BFF&fire=6B4BFF&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=6B4BFF&sideLabels=6B4BFF&dates=c9d1d9&background=0d1117" alt="Contribution Stats"/>
</div>

<h2 align="center">
  Let's Connect
</h2>

<div align="center">
  <a href="https://discord.com/channels/@me/1334302822891520091" target="_blank">
    <img src="https://img.shields.io/badge/Discord-%231SLOW-6B4BFF?style=for-the-badge&logo=discord&logoColor=white&labelColor=0d1117"/>
  </a>
  <a href="https://github.com/SlowWebDev" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-SlowWebDev-6B4BFF?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
  </a>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=6B4BFF&center=true&vCenter=true&repeat=false&width=500&height=30&lines=Building+the+Future%2C+One+Line+at+a+Time+⚡" alt="Outro"/>
</div>

<div align="center">
  <canvas id="gameCanvas" width="600" height="400" style="border: 1px solid #6B4BFF; border-radius: 10px; margin-top: 20px;"></canvas>
  <script>
    const canvas = document.getElementById("gameCanvas");
    const ctx = canvas.getContext("2d");
    let snake = [{ x: 10, y: 10 }], 
        direction = { x: 10, y: 0 }, 
        food = { x: Math.floor(Math.random() * 60) * 10, y: Math.floor(Math.random() * 40) * 10 };

    function draw() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      ctx.fillStyle = "#6B4BFF";
      snake.forEach(({ x, y }) => ctx.fillRect(x, y, 10, 10));
      ctx.fillStyle = "#FF0000";
      ctx.fillRect(food.x, food.y, 10, 10);
      let head = { x: snake[0].x + direction.x, y: snake[0].y + direction.y };
      snake.unshift(head);
      if (head.x === food.x && head.y === food.y) {
        food = { x: Math.floor(Math.random() * 60) * 10, y: Math.floor(Math.random() * 40) * 10 };
      } else {
        snake.pop();
      }
    }
    setInterval(draw, 100);
  </script>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24&height=3&section=footer" width="100%" alt="Footer"/>
</div>
