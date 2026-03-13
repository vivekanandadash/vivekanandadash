<div align="center">

<!-- Animated Venom/Glitch-style Header -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d1117,30:0f2027,60:1a3a4a,100:0ea5e9&height=250&section=header&text=Vivekananda%20Dash&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=45&stroke=0ea5e9&strokeWidth=2&desc=☕%20Java%20Full-Stack%20%7C%20%F0%9F%90%B3%20DevOps%20%7C%20%E2%98%81%EF%B8%8F%20Cloud%20Engineer&descSize=20&descAlignY=68&descAlign=50&descColor=94d2f5" />

<br/>

<!-- Typing SVG -->
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=24&pause=1200&color=38BDF8&center=true&vCenter=true&random=false&width=700&height=60&lines=Building+production-grade+Java+backends+%F0%9F%9A%80;Microservices+%7C+Spring+Boot+%7C+Hibernate;Docker+%7C+Kubernetes+%7C+Jenkins+CI%2FCD;AWS+%7C+Kafka+%7C+Redis+%7C+ELK+Stack;Grafana+%7C+Prometheus+%7C+Spring+Security;Learning+by+doing+always+shipping+%E2%9C%85" alt="Typing SVG" />

<br/><br/>

<!-- Profile Views + Followers -->
<img src="https://komarev.com/ghpvc/?username=vivekanandadash&label=Profile+Views&color=0ea5e9&style=for-the-badge" alt="profile views" />
&nbsp;
<a href="https://github.com/vivekanandadash?tab=followers">
  <img src="https://img.shields.io/github/followers/vivekanandadash?label=Followers&style=for-the-badge&color=0ea5e9&labelColor=1e293b" />
</a>

<br/><br/>

<!-- 🐳 Whale Jump Animation (SVG - replaces heatmap) -->
<svg width="800" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Ocean gradient -->
    <linearGradient id="oceanGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0ea5e9;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#0369a1;stop-opacity:0.35"/>
    </linearGradient>
    <!-- Wave gradient -->
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0ea5e9;stop-opacity:0.6"/>
      <stop offset="50%" style="stop-color:#38bdf8;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#0ea5e9;stop-opacity:0.6"/>
    </linearGradient>
    <!-- Glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Splash filter -->
    <filter id="splashGlow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Ocean background -->
  <rect x="0" y="110" width="800" height="70" fill="url(#oceanGrad)" rx="4"/>

  <!-- Animated wave 1 -->
  <path d="M0,118 Q100,108 200,118 Q300,128 400,118 Q500,108 600,118 Q700,128 800,118 L800,180 L0,180 Z" fill="url(#waveGrad)" opacity="0.5">
    <animateTransform attributeName="transform" type="translate" values="0,0;-200,0;0,0" dur="6s" repeatCount="indefinite"/>
  </path>

  <!-- Animated wave 2 (offset) -->
  <path d="M0,122 Q150,112 300,122 Q450,132 600,122 Q700,115 800,122 L800,180 L0,180 Z" fill="#38bdf8" opacity="0.25">
    <animateTransform attributeName="transform" type="translate" values="200,0;0,0;200,0" dur="5s" repeatCount="indefinite"/>
  </path>

  <!-- === WHALE GROUP (jumps, rotates, splashes, disappears) === -->
  <g id="whale">
    <!-- Jump: move from water up into air and back, with opacity fade out/in -->
    <animateTransform
      attributeName="transform"
      type="translate"
      values="370,108; 370,108; 330,30; 295,-10; 275,20; 270,100; 270,108; 270,108; 270,108; 370,108"
      keyTimes="0; 0.05; 0.2; 0.35; 0.48; 0.58; 0.62; 0.75; 0.95; 1"
      dur="4s"
      repeatCount="indefinite"
      calcMode="spline"
      keySplines="0 0 1 1; .4 0 .6 1; .4 0 .2 1; .4 0 .6 1; .4 0 .6 1; .4 0 .6 1; 0 0 1 1; 0 0 1 1; 0 0 1 1"
    />

    <!-- Whale body -->
    <ellipse cx="0" cy="0" rx="38" ry="20" fill="#0ea5e9" filter="url(#glow)">
      <animate attributeName="opacity" values="0;0;1;1;1;1;0;0;0;0" keyTimes="0;0.04;0.06;0.35;0.6;0.63;0.66;0.75;0.95;1" dur="4s" repeatCount="indefinite"/>
    </ellipse>

    <!-- Whale belly -->
    <ellipse cx="8" cy="6" rx="22" ry="11" fill="#bae6fd" opacity="0.7">
      <animate attributeName="opacity" values="0;0;0.7;0.7;0.7;0.7;0;0;0;0" keyTimes="0;0.04;0.06;0.35;0.6;0.63;0.66;0.75;0.95;1" dur="4s" repeatCount="indefinite"/>
    </ellipse>

    <!-- Whale tail -->
    <path d="M-32,-6 L-50,-18 L-44,-2 L-50,14 L-32,6 Z" fill="#0369a1">
      <animate attributeName="opacity" values="0;0;1;1;1;1;0;0;0;0" keyTimes="0;0.04;0.06;0.35;0.6;0.63;0.66;0.75;0.95;1" dur="4s" repeatCount="indefinite"/>
    </path>

    <!-- Whale dorsal fin -->
    <path d="M0,-20 L10,-38 L18,-20 Z" fill="#0284c7">
      <animate attributeName="opacity" values="0;0;1;1;1;1;0;0;0;0" keyTimes="0;0.04;0.06;0.35;0.6;0.63;0.66;0.75;0.95;1" dur="4s" repeatCount="indefinite"/>
    </path>

    <!-- Whale eye -->
    <circle cx="22" cy="-5" r="3.5" fill="white">
      <animate attributeName="opacity" values="0;0;1;1;1;1;0;0;0;0" keyTimes="0;0.04;0.06;0.35;0.6;0.63;0.66;0.75;0.95;1" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="23" cy="-5.5" r="1.8" fill="#0f172a">
      <animate attributeName="opacity" values="0;0;1;1;1;1;0;0;0;0" keyTimes="0;0.04;0.06;0.35;0.6;0.63;0.66;0.75;0.95;1" dur="4s" repeatCount="indefinite"/>
    </circle>

    <!-- Whale smile -->
    <path d="M18,2 Q22,7 28,4" stroke="white" stroke-width="1.5" fill="none" stroke-linecap="round">
      <animate attributeName="opacity" values="0;0;1;1;1;1;0;0;0;0" keyTimes="0;0.04;0.06;0.35;0.6;0.63;0.66;0.75;0.95;1" dur="4s" repeatCount="indefinite"/>
    </path>

    <!-- Blowhole water spout (active at peak of jump) -->
    <g>
      <animate attributeName="opacity" values="0;0;0;1;0;0;0;0;0;0" keyTimes="0;0.1;0.25;0.35;0.42;0.5;0.6;0.7;0.9;1" dur="4s" repeatCount="indefinite"/>
      <path d="M5,-22 Q0,-40 -5,-22" stroke="#7dd3fc" stroke-width="2.5" fill="none" stroke-linecap="round"/>
      <path d="M5,-22 Q8,-44 2,-26" stroke="#bae6fd" stroke-width="1.5" fill="none" stroke-linecap="round"/>
      <circle cx="0" cy="-44" r="2" fill="#7dd3fc"/>
      <circle cx="-6" cy="-40" r="1.5" fill="#bae6fd"/>
      <circle cx="7" cy="-46" r="1" fill="#e0f2fe"/>
    </g>
  </g>

  <!-- === SPLASH EFFECT (when whale re-enters water) === -->
  <g transform="translate(270, 112)" filter="url(#splashGlow)">
    <!-- Left splash drops -->
    <line x1="0" y1="0" x2="-22" y2="-18" stroke="#38bdf8" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="-22;-22;-22;-22;-22;-22;-22;-28;-28;-22" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </line>
    <line x1="0" y1="0" x2="-14" y2="-24" stroke="#7dd3fc" stroke-width="2" stroke-linecap="round">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </line>
    <!-- Right splash drops -->
    <line x1="0" y1="0" x2="22" y2="-18" stroke="#38bdf8" stroke-width="2.5" stroke-linecap="round">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="22;22;22;22;22;22;22;28;28;22" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </line>
    <line x1="0" y1="0" x2="14" y2="-24" stroke="#7dd3fc" stroke-width="2" stroke-linecap="round">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </line>
    <!-- Center splash arc -->
    <path d="M-10,0 Q0,-28 10,0" stroke="#bae6fd" stroke-width="2" fill="none" stroke-linecap="round">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </path>
    <!-- Splash droplets -->
    <circle cx="-26" cy="-20" r="2.5" fill="#38bdf8">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="26" cy="-20" r="2.5" fill="#38bdf8">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-18" cy="-28" r="1.8" fill="#7dd3fc">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="18" cy="-28" r="1.8" fill="#7dd3fc">
      <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0" keyTimes="0;0.05;0.2;0.35;0.5;0.58;0.62;0.66;0.72;1" dur="4s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Small floating bubbles in ocean -->
  <circle cx="150" cy="140" r="3" fill="#38bdf8" opacity="0.4">
    <animate attributeName="cy" values="145;125;145" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="155" r="2" fill="#38bdf8" opacity="0.3">
    <animate attributeName="cy" values="155;132;155" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.05;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="720" cy="145" r="2.5" fill="#7dd3fc" opacity="0.35">
    <animate attributeName="cy" values="148;128;148" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.35;0.08;0.35" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="80" cy="158" r="1.8" fill="#bae6fd" opacity="0.3">
    <animate attributeName="cy" values="158;138;158" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.05;0.3" dur="2.8s" repeatCount="indefinite"/>
  </circle>

  <!-- Stars/sparkles in sky area -->
  <circle cx="100" cy="40" r="1.5" fill="#e0f2fe" opacity="0">
    <animate attributeName="opacity" values="0;0.7;0;0.5;0" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="25" r="1.2" fill="#bae6fd" opacity="0">
    <animate attributeName="opacity" values="0;0.6;0;0;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="680" cy="55" r="1" fill="#e0f2fe" opacity="0">
    <animate attributeName="opacity" values="0.5;0;0.7;0;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="70" r="1.3" fill="#7dd3fc" opacity="0">
    <animate attributeName="opacity" values="0;0;0.8;0;0.4" dur="3.2s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

---

## 🧑‍💻 About Me

```java
@Developer
public class VivekanandaDash {

    String[] currentlyBuilding = {"Employee Management System (REST API + Docker + AWS + CI/CD)"};
    String[] learning          = {"Microservice Design Patterns", "AWS", "Docker", "Kubernetes",
                                   "TypeScript", "Angular 21"};
    String[] expertise         = {"Java", "Spring Boot", "Design Patterns",
                                   "Security", "DevOps"};
    String   email             = "vivekanandadash245@gmail.com";
    String   motto             = "Learn by doing. Ship it. Iterate.";
}
```

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vivekananda%20Dash-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vivekananda-dash)
[![Twitter](https://img.shields.io/badge/Twitter-@vivekanand85051-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/@vivekanand85051)
[![Email](https://img.shields.io/badge/Email-vivekanandadash245@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vivekanandadash245@gmail.com)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=vivekanandadash&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=vivekanandadash&theme=tokyonight&hide_border=true" />

<br/>

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vivekanandadash&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=vivekanandadash&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" />

</div>

---

## 🛠️ Tech Stack

### ☕ Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-1572B6?style=for-the-badge&logo=spring&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### 🌐 Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### ☁️ DevOps & Cloud
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### 📊 Observability & Monitoring
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?style=for-the-badge&logo=logstash&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white)

### 📨 Messaging & Caching
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 🗄️ Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

### 🧪 Testing & Code Quality
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge&logo=java&logoColor=white)
![JaCoCo](https://img.shields.io/badge/JaCoCo-C21325?style=for-the-badge&logo=java&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

### 🧰 Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![Babel](https://img.shields.io/badge/Babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=black)

---

## 🚀 Current Project

> **Employee Management System** — A production-grade REST API built with Spring Boot, containerized with Docker, deployed on AWS, and automated with a full CI/CD pipeline using Jenkins.

```
📦 Employee Management System
 ┣ 🔧 Spring Boot REST API
 ┣ 🐳 Dockerized & Container-ready
 ┣ ☁️  Deployed on AWS (EC2 / ECS)
 ┣ 🔄 CI/CD Pipeline with Jenkins
 ┗ 🔐 Spring Security integrated
```

---

## 📈 Contribution Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=vivekanandadash&theme=tokyo-night&hide_border=true&area=true" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" />

*"The best way to learn is to build something real."* ☕

</div>
