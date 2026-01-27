---
layout: default
title: Home
---

<section class="hero">
  <div class="container hero-grid">
    <div class="hero-text">
      <h1>Ospitalità autentica,<br>come a casa</h1>
      <p>
        Scopri i nostri B&B pensati per offrirti comfort,
        eleganza e una posizione ideale.
      </p>
    </div>

    <div class="hero-image">
      <img src="/img/Immagine1.png" alt="prova testo">
    </div>
  </div>
</section>

<section class="quote">
  <div class="container">
    <p>
      “Ogni soggiorno è un’esperienza, non solo una notte fuori casa.”
    </p>
  </div>
</section>

<section class="feature">
  <div class="container feature-grid">
    <div class="feature-text">
      <h2>Nel cuore della città</h2>
      <p>
        Posizioni strategiche per vivere la città
        senza rinunciare alla tranquillità.
      </p>
    </div>

    <div class="feature-image">
      <img src="/img/bnb2.jpg" alt="">
    </div>
  </div>
</section>

<section class="feature reverse">
  <div class="container feature-grid">
    <div class="feature-text">
      <h2>Comfort e stile</h2>
      <p>
        Ambienti curati e dotati di ogni comfort
        per un soggiorno senza pensieri.
      </p>
    </div>

    <div class="feature-image">
      <img src="/img/bnb3.jpg" alt="">
    </div>
  </div>
</section>

<section class="feature">
  <div class="container feature-grid">
    <div class="feature-text">
      <h2>Accoglienza su misura</h2>
      <p>
        Sempre disponibili per assisterti
        e rendere il tuo soggiorno speciale.
      </p>
    </div>

    <div class="feature-image">
      <img src="/img/bnb1.jpg" alt="">
    </div>
  </div>
</section>
<section class="faq">
  <div class="container">
    <h2>Domande frequenti</h2>

    <div class="accordion-item">
      <button class="accordion-question">
        Quali servizi offrite nei B&B?
        <span class="arrow">▼</span>
      </button>
      <div class="accordion-answer">
        <p>Tutti i nostri B&B offrono Wi-Fi gratuito, colazione inclusa, aria condizionata e biancheria di qualità.</p>
      </div>
    </div>

    <div class="accordion-item">
      <button class="accordion-question">
        Come posso prenotare?
        <span class="arrow">▼</span>
      </button>
      <div class="accordion-answer">
        <p>Puoi prenotare direttamente dal nostro sito tramite il form di contatto o via email.</p>
      </div>
    </div>

    <div class="accordion-item">
      <button class="accordion-question">
        È possibile arrivare in anticipo o posticipare il check-out?
        <span class="arrow">▼</span>
      </button>
      <div class="accordion-answer">
        <p>Sì, il check-in anticipato o il check-out posticipato sono possibili su richiesta, compatibilmente con le disponibilità.</p>
      </div>
    </div>

  </div>
</section>


<script>
document.querySelectorAll('.accordion-question').forEach(button => {
  button.addEventListener('click', () => {
    const item = button.parentElement;

    // Chiude tutte le altre
    document.querySelectorAll('.accordion-item').forEach(i => {
      if(i !== item) i.classList.remove('active');
    });

    // Toggle apertura/chiusura
    item.classList.toggle('active');
  });
});
</script>
