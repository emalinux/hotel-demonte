---
title: "Le nostre camere"
---

{{ define "main" }}

<section class="camere">
  <div class="container">

    <h1>Le nostre camere</h1>

    <p class="intro">
      Ambienti semplici, curati e pensati per offrirti un soggiorno rilassante nel cuore della Valle Stura.
    </p>

    <div class="camere-grid">

      <!-- CAMERA 1 -->
      <div class="camera-card">
        <img src="/img/camere/singola.webp" alt="Camera singola">

        <div class="camera-content">
          <h2>Camera Singola</h2>
          <p>Ideale per soggiorni brevi o viaggiatori singoli.</p>

          <ul>
            <li>✔ Letto singolo</li>
            <li>✔ Bagno privato</li>
            <li>✔ Wi-Fi</li>
          </ul>

          <a href="/contatti/" class="btn">Richiedi disponibilità</a>
        </div>
      </div>

      <!-- CAMERA 2 -->
      <div class="camera-card">
        <img src="/img/camere/doppia.webp" alt="Camera doppia">

        <div class="camera-content">
          <h2>Camera Doppia</h2>
          <p>Perfetta per coppie o soggiorni rilassanti in montagna.</p>

          <ul>
            <li>✔ Letto matrimoniale</li>
            <li>✔ Bagno privato</li>
            <li>✔ Vista montagna</li>
          </ul>

          <a href="/contatti/" class="btn">Richiedi disponibilità</a>
        </div>
      </div>

      <!-- CAMERA 3 -->
      <div class="camera-card">
        <img src="/img/camere/familiare.webp" alt="Camera familiare">

        <div class="camera-content">
          <h2>Camera Familiare</h2>
          <p>Spazio e comfort per famiglie e gruppi.</p>

          <ul>
            <li>✔ Più posti letto</li>
            <li>✔ Bagno privato</li>
            <li>✔ Ambienti spaziosi</li>
          </ul>

          <a href="/contatti/" class="btn">Richiedi disponibilità</a>
        </div>
      </div>

    </div>

  </div>
</section>

{{ end }}
