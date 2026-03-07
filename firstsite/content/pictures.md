---
title: "Pictures"
date: 2026-03-06T22:50:25+01:00
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
  color: rgba(255, 255, 255, 0.7);
}
.gallery .title {
  font-weight: 600;
  margin-bottom: 0.3rem;
  color: rgba(255, 255, 255, 0.85);
}
</style>

<div class="gallery">
  <details>
    <summary>
      <img src="/images/fen_ditton.jpg" alt="Fen Ditton.">
    </summary>
    <div class="info">
      <div class="title">Fen Ditton</div>
      Fen Ditton on a cold morning, near dawn. The church!
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/imperial_palace_gardens.jpeg" alt="Imperial Palace Gardens, golden.">
    </summary>
    <div class="info">
      <div class="title">Imperial Palace Gardens</div>
      Lucky to have an evening like this. Trees, rigidly straight buildings and huge planes.
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/leckhampton_frost.jpeg" alt="Light frost.">
    </summary>
    <div class="info">
      <div class="title">Light frost.</div>
      Mystical morning. Sunrise was otherworldly.
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/otaru.jpeg" alt="Fishing in Otaru.">
    </summary>
    <div class="info">
      <div class="title">Fishing.</div>
      Picture of a man fishing. Very quiet corner of the world.
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/michael_tanner_corpus.webp" alt="Michael Tanner.">
    </summary>
    <div class="info">
      <div class="title">Tanner</div>
      Perfect rooms. E?
    </div>
  </details>

  <details>
    <summary>
      <img src="/images/when_god_came_to_cambridge.jpg" alt="Emperor at Queens'.">
    </summary>
    <div class="info">
      <div class="title">When god came to Cambridge.</div>
      Taken by M.A.P. Wood.
    </div>
  </details>
</div>


