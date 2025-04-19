# 👨‍💻 Welcome to Zynthera

<div align="center" style="padding: 20px; border: 2px solid #FF5555; border-radius: 10px; box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);">
  <h1 style="color: #FF5555; font-family: 'JetBrains Mono', monospace;">⚛ Zynthera ⚛</h1>
  <h3 style="color: #8FF0FF; font-family: 'JetBrains Mono', monospace;">Building with Python, Next.js, and Rust</h3>
</div>

---

## 🏆 About Me

Hi there! I'm **zynthera**, a developer specializing in **Python**, **Next.js**, and **Rust**. I design scalable, secure, and high-performance systems hosted on platforms like **Vercel**, **Netlify**, and **Supabase**.

### 💡 Key Highlights
| **Category**             | **Details**                                                |
|--------------------------|-----------------------------------------------------------|
| **Languages & Frameworks** | Python, Next.js, Rust, TypeScript, JavaScript             |
| **Hosting Platforms**     | Vercel, Netlify, Supabase (Self-Hosted)                   |
| **Database**              | Supabase (PostgreSQL-based)                               |
| **Focus Areas**           | Web Development, Backend Systems, Animation, Cybersecurity |

---

## ⚙️ What I Do

### 🔗 Full-Stack Web Development
- **Frontend**: Building dynamic and responsive interfaces using **Next.js** and **React**.
- **Backend**: Developing secure APIs and scalable systems with **Python** and **Rust**.
- **Hosting**: Deploying projects using **Vercel**, **Netlify**, and **Supabase**.

### 💻 Programming Languages
| **Language**   | **Expertise Level** | **Usage**                                  |
|----------------|---------------------|--------------------------------------------|
| Python         | ⭐⭐              | Data analysis, backend development     |
| Next.js        | ⭐⭐⭐⭐               | Web development, UI/UX                     |
| Rust           | ⭐⭐⭐               | System-level programming, performance      |

### 🔒 Cybersecurity
- Designing secure APIs with advanced encryption techniques.
- Implementing **user authentication** and **multi-layered security**.

### 🎬 9D Animation with AnimeJS
Building cutting-edge web animations using the powerful AnimeJS library across nine dimensions:

```javascript
// Sample 9D Animation Framework with AnimeJS
const animation = anime({
  targets: '.element',
  // Dimension 1-3: Spatial (X, Y, Z)
  translateX: function(el) { return anime.random(-250, 250); },
  translateY: function(el) { return anime.random(-250, 250); },
  translateZ: function(el) { return anime.random(-250, 250); },
  // Dimension 4: Time
  duration: function() { return anime.random(1000, 3000); },
  delay: function() { return anime.random(0, 500); },
  // Dimension 5: Scale
  scale: function() { return anime.random(0.5, 2); },
  // Dimension 6: Rotation
  rotate: function() { return anime.random(-360, 360); },
  // Dimension 7: Color
  backgroundColor: function() {
    return `hsl(${anime.random(0, 360)}, 70%, 60%)`;
  },
  // Dimension 8: Opacity
  opacity: function() { return anime.random(0.3, 1); },
  // Dimension 9: Morphing
  borderRadius: function() { return `${anime.random(10, 50)}%`; },
  easing: 'cubicBezier(.5, .05, .1, .3)',
  direction: 'alternate',
  loop: true
});
```

#### Animation Projects
- **Interactive SVG Morphing** - Seamless shape transformations
- **Parallax Scrolling Effects** - Depth-based movement interactions
- **Staggered Motion Systems** - Choreographed sequential animations
- **Path Following Animations** - Objects following complex motion paths
- **Physics-Based Interactions** - Realistic momentum and collision effects

---

## 📦 Tools & Technologies

| **Category**       | **Tools/Technologies**               |
|--------------------|---------------------------------------|
| **Frontend**       | Next.js, React, TypeScript           |
| **Backend**        | Python, Django, Flask, Rust          |
| **System-Level**   | Rust, WebAssembly (WASM)             |
| **Database**       | Supabase (PostgreSQL-based)          |
| **Hosting**        | Vercel, Netlify, Self-Hosted         |
| **DevOps**         | Docker, Kubernetes, GitHub Actions   |
| **Animation**      | AnimeJS, GSAP, Three.js, WebGL       |

---

## 🎨 AnimeJS Animation Implementation

### Timeline Sequencing
```javascript
// Creating complex sequences with AnimeJS
const timelineSequence = anime.timeline({
  easing: 'easeOutExpo',
  duration: 750
});

// Add animations to the timeline
timelineSequence
  .add({
    targets: '.element-1',
    translateX: 250,
    rotate: 540
  })
  .add({
    targets: '.element-2',
    translateX: 250,
    scale: 2
  }, '-=600') // Relative offset
  .add({
    targets: '.element-3',
    translateX: 250,
    backgroundColor: '#FF5555'
  }, '-=800'); // Relative offset
```

### Staggered Animations
```javascript
// Creating staggered effects
anime({
  targets: '.staggered-element',
  translateX: 250,
  delay: anime.stagger(100, {from: 'center'}),
  easing: 'cubicBezier(0.225, 1, 0.915, 0.980)'
});
```

### SVG Morphing
```javascript
// SVG Path morphing
anime({
  targets: '.morphing-path',
  d: [
    {value: 'M0,0 C150,100 350,0 500,100'},
    {value: 'M0,100 C150,0 350,100 500,0'},
    {value: 'M0,0 C150,100 350,0 500,100'}
  ],
  easing: 'easeInOutQuad',
  duration: 2000,
  loop: true
});
```

### Performance Optimization
```javascript
// Optimized rendering using requestAnimationFrame
anime({
  targets: '.performance-element',
  translateX: 250,
  duration: 1000,
  update: function(anim) {
    // Use requestAnimationFrame for smooth performance
    requestAnimationFrame(() => {
      document.querySelector('.progress').innerHTML = 
        Math.round(anim.progress) + '%';
    });
  }
});
```

---

## 🔐 Security Matrix

```python
security_status = {
    "encryption": "AES-256",
    "firewall": "ACTIVE",
    "threat_level": "LOW",
    "last_scan": "2025-04-12 07:37:04",
    "multi_factor_auth": True,
    "protocols": ["TLS 1.3", "QUIC", "HTTPS"]
}
```

---

## 🌐 Hosting & Database

### 🏢 Hosting Platforms
- **Vercel**: Ideal for deploying highly scalable **Next.js** applications with CI/CD.
- **Netlify**: Best suited for hosting static websites and serverless functions.
- **Supabase (Self-Hosting)**: Used for hosting secure backend services and APIs.

### 📂 Database
- **Supabase**: PostgreSQL-based database for real-time, scalable applications.
  - Features:
    - Integrated with **RESTful APIs** and **GraphQL**.
    - Enhanced security with **row-level security**.

---

## 🎬 Featured Animation Projects

### Interactive Portfolio Showcase
```javascript
// Dynamic portfolio item animation
const portfolioAnimation = anime({
  targets: '.portfolio-item',
  translateY: [100, 0],
  opacity: [0, 1],
  scale: [0.8, 1],
  delay: anime.stagger(200, {start: 300}),
  easing: 'spring(1, 80, 10, 0)'
});

// Interactive hover effects
document.querySelectorAll('.portfolio-item').forEach(item => {
  item.addEventListener('mouseenter', () => {
    anime({
      targets: item,
      scale: 1.05,
      boxShadow: '0 8px 20px rgba(0,0,0,0.2)',
      duration: 800
    });
  });
  
  item.addEventListener('mouseleave', () => {
    anime({
      targets: item,
      scale: 1,
      boxShadow: '0 2px 10px rgba(0,0,0,0.1)',
      duration: 600
    });
  });
});
```

### Data Visualization Motion System
```javascript
// Animated data visualization
const dataVisualization = anime({
  targets: '.data-point',
  translateY: function(el) {
    return -el.getAttribute('data-value') * 3;
  },
  height: function(el) {
    return el.getAttribute('data-value') * 3;
  },
  opacity: [0, 1],
  delay: anime.stagger(100),
  duration: 1600,
  easing: 'easeInOutQuart',
  complete: function() {
    // Add labels with counter animation
    anime({
      targets: '.data-label',
      innerHTML: [0, function(el) {
        return el.getAttribute('data-final');
      }],
      round: 1,
      easing: 'easeInOutExpo',
      duration: 1200
    });
  }
});
```

### Scrolling Parallax Effects
```javascript
// Parallax scrolling system
window.addEventListener('scroll', () => {
  const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
  
  anime({
    targets: '.parallax-layer-1',
    translateY: scrollTop * 0.1,
    easing: 'linear',
    duration: 0
  });
  
  anime({
    targets: '.parallax-layer-2',
    translateY: scrollTop * 0.3,
    easing: 'linear',
    duration: 0
  });
  
  anime({
    targets: '.parallax-layer-3',
    translateY: scrollTop * 0.5,
    easing: 'linear',
    duration: 0
  });
});
```

---

## 🌐 Connect with Me

<div align="center" style="border: 2px solid #FF5555; border-radius: 10px; padding: 15px; box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.1);">
  <a href="https://github.com/zynthera">
    <img src="https://img.shields.io/badge/GitHub-@zynthera-black?style=flat&logo=github" alt="GitHub">
  </a>
  <a href="https://twitter.com/PrakharYud">
    <img src="https://img.shields.io/badge/Twitter-@PrakharYud-blue?style=flat&logo=twitter" alt="Twitter">
  </a>
  <a href="https://instagram.com/xpolit.ninja">
    <img src="https://img.shields.io/badge/Instagram-@xpolit.ninja-purple?style=flat&logo=instagram" alt="Instagram">
  </a>
</div>

<p align="center">
   <img
       src="https://github-readme-stats-sigma-ochre.vercel.app/api?username=zynthera&theme=tokyonight&hide_border=true&count_private=true"
       alt="My GitHub stats"
     />
</p>

<p align="center">
   <img
       src="https://github-readme-streak-stats-wine-two.vercel.app/?user=zynthera&theme=tokyonight&hide_border=true"
       alt="My GitHub Streaks"
     />
</p>


---
<p align="center">
   <img
       src="https://visitcount.itsvg.in/api?id=zynthera&icon=5&color=6"
       alt="Visit Counts"
     />
</p>

---

<div align="center" style="padding: 10px; border: 2px solid #333; border-radius: 10px; box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);">
  <p style="font-family: 'JetBrains Mono', monospace; color: #333; margin: 0;">
    <strong>🔑 Active Session | User:</strong> zynthera | <strong>UTC:</strong> 2025-04-18 09:14:32
  </p>
</div>

<!-- Animated script for README display -->
<script>
document.addEventListener('DOMContentLoaded', function() {
  // Initialize 9D Animation System
  anime({
    targets: '.readme-header',
    translateY: [-50, 0],
    opacity: [0, 1],
    duration: 1200,
    easing: 'easeOutElastic(1, .5)'
  });
  
  // Animate sections sequentially
  anime.timeline({
    easing: 'easeOutExpo'
  })
  .add({
    targets: '.section',
    translateY: [100, 0],
    opacity: [0, 1],
    delay: anime.stagger(150),
    duration: 800
  })
  .add({
    targets: '.highlight',
    backgroundColor: ['rgba(255,85,85,0)', 'rgba(255,85,85,0.2)'],
    delay: anime.stagger(100),
    duration: 600
  });
});
</script>