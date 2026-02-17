<div style="max-width:900px;margin:auto;text-align:center;font-family:'JetBrains Mono', monospace;">

<!-- Intro -->
<div id="intro" style="opacity:0;transform:scale(0.8);transition:1.5s;">
  <img src="https://user-images.githubusercontent.com/74038190/212259265-6e8b4c49-66df-4c53-bb28-9c5c8f6b31a9.gif" width="400" style="border-radius:15px;box-shadow:0 8px 20px rgba(0,0,0,0.3)"/>
  <h1 style="color:#00FFCC;margin-top:20px;font-size:2rem;">👋 Hi, I'm Jaweid Moraadi</h1>
  <p style="color:#00FFCC;font-size:1.2rem;margin-top:10px;">
    AI Enthusiast | Machine Learning & Deep Learning | Network Engineer | Developer
  </p>
</div>

<!-- Skills -->
<div id="skills" style="opacity:0;transform:scale(0.9);transition:1s;margin-top:50px;">
  <h2 style="color:#2563EB;font-size:1.8rem;margin-bottom:20px;">💻 Skills & Tools</h2>
  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:20px;">
    <!-- Icons -->
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="60" title="Java"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="60" title="C++"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60" title="Python"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="60" title="JavaScript"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="60" title="PHP"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="60" title="HTML5"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="60" title="CSS3"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="60" title="React"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="60" title="MySQL"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" width="60" title="SQL Server"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="60" title="VS Code"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="60" title="GitHub"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="60" title="Git"/>
    <img class="skill" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="60" title="IntelliJ IDEA"/>
  </div>
</div>

</div>

<style>
.skill{
  opacity:0;
  transform:translateY(20px) scale(0.8);
  transition:0.5s;
}
.skill:hover{
  transform:translateY(-5px) scale(1.2);
  box-shadow:0 10px 20px rgba(0,255,204,0.5);
  filter:drop-shadow(0 0 8px #00FFCC);
}
</style>

<script>
// Intro Animation
setTimeout(()=>{
  const intro=document.getElementById('intro');
  intro.style.opacity=1;
  intro.style.transform='scale(1)';
},500);

// Skills staggered with bounce
setTimeout(()=>{
  const skills=document.getElementById('skills');
  skills.style.opacity=1;
  skills.style.transform='scale(1)';
  
  const skillIcons=document.querySelectorAll('.skill');
  skillIcons.forEach((s,i)=>{
    setTimeout(()=>{
      s.style.opacity=1;
      s.style.transform='translateY(0) scale(1.05)';
      setTimeout(()=>s.style.transform='translateY(0) scale(1)',300);
    }, i*150);
  });
},3500);
</script>
