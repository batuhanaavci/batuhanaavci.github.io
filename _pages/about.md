---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a master's student in Electrical Engineering at Aalto University, Espoo, Finland. I am specializing in control and robotics, with a minor in machine learning. My research interests lie at the intersection of these fields, particularly in optimal control, uncertainty quantification, reinforcement learning, and probabilistic methods.

## Teaching and Research Assistantships

Currently, I am a teaching assistant for *ELEC-E8101 Digital and Optimal Control* at Aalto University under Prof. Dominik Baumann. For the upcoming semester, I will also be a teaching assistant for *CS-E4825 Probabilistic Machine Learning* under Prof. Pekka Marttinen.

My research journey began at the *Artificial Intelligence and Intelligent Systems (AI2S) Laboratory* at Istanbul Technical University, where I focused on uncertainty quantification and its integration into deep learning and fuzzy logic systems.

Last summer, I joined the *Computational Systems Biology* group at Aalto University, led by Prof. Harri Lähdesmäki, as a research assistant. During this time, I worked on continuous-time reinforcement learning methods.

## Publications

<div class="publications-grid">
  <div class="publication-card">
    <img src="/images/paper1.jpg" alt="Paper 1 Cover" class="publication-image"/>
    <div class="publication-info">
      <div class="publication-title">
        <strong>Towards Reliable Uncertainty Quantification and High Precision with General Type-2 Fuzzy Systems</strong>
      </div>
      <div class="publication-authors">
        B. Avcı, A. Beke, and T. Kumbasar
      </div>
      <div class="publication-venue">
        <em>IEEE International Conference on Fuzzy Systems</em>, Songdo Incheon, Korea, 2023.
      </div>
      <a href="/files/paper1.pdf" class="publication-link" target="_blank">Read Paper</a>
    </div>
  </div>
  <div class="publication-card">
    <img src="/images/paper2.jpg" alt="Paper 2 Cover" class="publication-image"/>
    <div class="publication-info">
      <div class="publication-title">
        <strong>Recognizing and Tracking Person of Interest: A Real-Time Efficient Deep Learning-Based Method for Quadcopters</strong>
      </div>
      <div class="publication-authors">
        H. E. Dursun, E. C. Guven, B. Avcı, and T. Kumbasar
      </div>
      <div class="publication-venue">
        <em>10th International Conference on Recent Advances in Space Technologies (RAST)</em>, Istanbul, Turkey, 2023.
      </div>
      <a href="/files/paper2.pdf" class="publication-link" target="_blank">Read Paper</a>
    </div>
  </div>
</div>

## CSS Styling

Add the following CSS to your main stylesheet (e.g., `assets/css/main.scss` or a custom CSS file):

```css
.publications-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  margin-top: 1rem;
}
.publication-card {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  overflow: hidden;
  width: 350px;
  display: flex;
  flex-direction: column;
}
.publication-image {
  width: 100%;
  height: 180px;
  object-fit: cover;
}
.publication-info {
  padding: 1rem;
}
.publication-title {
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}
.publication-authors,
.publication-venue {
  font-size: 0.95rem;
  color: #555;
  margin-bottom: 0.3rem;
}
.publication-link {
  display: inline-block;
  margin-top: 0.5rem;
  color: #fff;
  background: #222;
  padding: 0.4em 1em;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.95rem;
  transition: background 0.2s;
}
.publication-link:hover {
  background: #444;
}

