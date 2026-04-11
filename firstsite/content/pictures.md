---
title: "Pictures"
date: 2026-03-06T22:50:25+01:00
weight: 7
draft: false
---


### Gallery
<!--more-->

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.25rem;
  margin-top: 1.5rem;
}
.gallery details {
  border: 1px solid rgba(0, 0, 0, 0.06);
  border-radius: 12px;
  overflow: hidden;
  background: rgba(0, 0, 0, 0.015);
  transition: box-shadow 0.2s ease, transform 0.2s ease;
}
.gallery details[open] {
  box-shadow: 0 10px 24px rgba(0, 0, 0, 0.08);
  transform: translateY(-2px);
}
.gallery summary {
  list-style: none;
  cursor: pointer;
}
.gallery summary::-webkit-details-marker {
  display: none;
}
.gallery img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
}
.gallery .info {
  padding: 0.9rem 1rem 1rem;
  font-size: 0.95rem;
  color: inherit;
}
.gallery .title {
  font-weight: 600;
  margin-bottom: 0.3rem;
  color: inherit;
}
.gallery .caption {
  opacity: 0.72;
}
</style>

<div class="gallery">
  <details>
    <summary>
      <img src="/images/fen_ditton.jpg" alt="Fen Ditton.">
    </summary>
    <div class="info">
      <div class="title">Fen Ditton</div>
      <div class="caption">Fen Ditton on a cold morning, near dawn.</div>
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/imperial_palace_gardens.jpeg" alt="Imperial Palace Gardens, golden.">
    </summary>
    <div class="info">
      <div class="title">Imperial Palace Gardens</div>
      <div class="caption">Lucky to have an evening like this. Trees, rigidly straight buildings and huge planes.</div>
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/leckhampton_frost.jpeg" alt="Light frost.">
    </summary>
    <div class="info">
      <div class="title">Light frost.</div>
      <div class="caption">Sunrise.</div>
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/otaru.jpeg" alt="Fishing in Otaru.">
    </summary>
    <div class="info">
      <div class="title">Fishing.</div>
      <div class="caption">Picture of a man fishing. Very quiet corner of the world.</div>
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/michael_tanner_corpus.webp" alt="Michael Tanner.">
    </summary>
    <div class="info">
      <div class="title">Tanner</div>
      <div class="caption">Perfect rooms. E?</div>
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/when_god_came_to_cambridge.jpg" alt="Emperor at Queens'.">
    </summary>
    <div class="info">
      <div class="title">When god came to Cambridge.</div>
      <div class="caption">Taken by M.A.P. Wood.</div>
    </div>
  </details>
</div>


