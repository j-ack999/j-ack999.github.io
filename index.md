---
layout: default
title: Jack Walker
---

<style>
  .page {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
  }
  .sidebar {
    flex: 0 0 180px;          /* fixed narrow column */
    position: sticky;         /* stays visible as you scroll */
    top: 1rem;
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 8px;
    background: #f8f8f8;
    font-size: 0.95rem;
  }
  .sidebar h2 { margin-top: 0; font-size: 1.1rem; }
  .sidebar ul { list-style: none; padding: 0; margin: 0; }
  .sidebar li { margin: 0.4rem 0; }
  .main { flex: 1; min-width: 0; }

  /* stack on phones: links go on top */
  @media (max-width: 700px) {
    .page { flex-direction: column; }
    .sidebar { flex: none; width: 100%; position: static; box-sizing: border-box; }
  }

    .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 1rem;
    margin: 1rem 0;
  }
  .gallery img {
    width: 100%;
    height: 220px;
    object-fit: cover;      /* crops to a tidy grid; use "contain" to avoid cropping */
    border-radius: 8px;
  }

    .hero {
    display: flex;
    align-items: center;
    gap: 1.5rem;
    padding: 2.5rem 1.5rem;
    margin-bottom: 1.5rem;
    border-radius: 10px;
    color: #fff;
    /* dark overlay keeps the text readable over any background photo */
    background:
      linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
      url('{{ "/bg.jpg" | relative_url }}') center / cover no-repeat;   /* <-- bg filename */
  }
  .hero img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #fff;
    flex-shrink: 0;
  }
  .hero h1 { margin: 0; color: #fff; }

  @media (max-width: 700px) {
    .hero { flex-direction: column; text-align: center; padding: 1.5rem 1rem; }
  }
</style>

<div class="page">

<aside class="sidebar" markdown="1">

## Useful Links

- [GitHub](https://github.com/j-ack999)
- [LinkedIn](https://www.linkedin.com/in/jack-walker-aab8982ba/)
- [See my CV](cv.pdf)

</aside>

<div class="main" markdown="1">

<div class="hero">
  <img src="{{ '/pfp.jpg' | relative_url }}" alt="Photo of Jack Walker">   <!-- pfp filename -->
  <h1>Hi, I'm Jack</h1>
</div>

I'm a second-year Biomedical Engineering student at King's College London, with an interest in statistics and machine learning, and their applications to healthcare and finance.

## What am I up to?

Alongside studies I am currently further building my knowledge on neural networks by developing a convolutional neural network which I hope to use in the classification of brain tumours. This is in the early stages, however, you can see my progress [here](https://github.com/j-ack999/brainTumourNN)

## Relevant Grades and Results

- Computational Statistics Programming Examination - 99%
- Mathematics for Biomedical Engineers (Multivariate Calculus, Linear Algebra) - 84%
- Electrical Engineering - 74%


## Hackathons and Collaborative Projects 

HardwareHacks '26 - Myself and a team of 3 other people worked for around 32 hours to repurpose an old printer into a goalkeeper game, where the goalie moves in the direction of the ball in order to try and save it. This was ran on an ESP32

<div class="gallery">
  <img src="{{ '/IMG_3E0FD535-787C-4B8C-91FE-A2B42362A7CB.jpeg' | relative_url }}" alt="Hackathon photo 1">
  <img src="{{ '/IMG_6382.jpeg' | relative_url }}" alt="Hackathon photo 2">
</div>


</div>

</div>
