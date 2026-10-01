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
</style>

<div class="page">

<aside class="sidebar" markdown="1">

## Useful Links

- [GitHub](https://github.com/j-ack999)
- [LinkedIn](https://www.linkedin.com/in/jack-walker-aab8982ba/)
- [See my CV](cv.pdf)

</aside>

<div class="main" markdown="1">

# Hi, I'm Jack

I'm a second-year Biomedical Engineering student at King's College London, with an interest in statistics and machine learning, and their applications to healthcare and finance.

## What am I up to?

Alongside studies I am currently further building my knowledge on neural networks by developing a convolutional neural network which I hope to use in the classification of brain tumours. This is in the early stages however you can see my progress [here](https://github.com/j-ack999/brainTumourNN)

## Relevant Grades and Results

- Computational Statistics Programming Examination - 99%
- Mathematics for Biomedical Engineers (Multivariate Calculus, Linear Algebra) - 84%
- Electrical Engineering - 74%

</div>

</div>