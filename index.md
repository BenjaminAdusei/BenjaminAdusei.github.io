---
layout: home
title: "Adusei Foundation"
---

<style>
body {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  background-attachment: fixed;
  color: white;
  font-family: 'Segoe UI', sans-serif;
}

.wrapper {
  background: rgba(255, 255, 255, 0.95);
  border-radius: 20px;
  padding: 40px;
  margin: 40px auto;
  max-width: 1200px;
  color: #333;
  box-shadow: 0 20px 60px rgba(0,0,0,0.3);
}

.hero {
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
              url('https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1600&q=80');
  background-size: cover;
  padding: 100px 20px;
  text-align: center;
  border-radius: 20px;
  margin-bottom: 40px;
  color: white;
}

.hero h1 {
  font-size: 3.5em;
  text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
}

.btn {
  display: inline-block;
  padding: 15px 40px;
  background: linear-gradient(90deg, #ff416c, #ff4b2b);
  color: white;
  border-radius: 50px;
  text-decoration: none;
  font-weight: bold;
  margin: 10px;
  transition: transform 0.3s;
}

.btn:hover {
  transform: scale(1.05);
}

.card {
  background: white;
  border-radius: 15px;
  padding: 30px;
  margin: 20px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-10px);
}
</style>

<div class="hero">
  <h1>Transforming Education, Building Futures</h1>
  <p>Empowering students through technology, mentorship, and opportunity</p>
  <a href="./programs.md" class="btn">Our Programs</a>
  <a href="./contact.md" class="btn">Support Our Work</a>
</div>

<div class="wrapper">
  <h2 style="color: #4361ee; text-align: center;">Our Impact</h2>
  <p style="text-align: center;">Since our founding, we've reached hundreds of students through our educational initiatives.</p>
  
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; margin: 40px 0;">
    <div class="card">
      <h3 style="color: #4361ee;">📚 Coding Workshops</h3>
      <p>Free programming workshops for high school students.</p>
    </div>
    
    <div class="card">
      <h3 style="color: #4361ee;">💻 Tech Equipment Drive</h3>
      <p>Collecting and refurbishing computers for students in need.</p>
    </div>
    
    <div class="card">
      <h3 style="color: #4361ee;">🤝 Mentorship Program</h3>
      <p>Connecting CS students with industry professionals.</p>
    </div>
  </div>
</div>
