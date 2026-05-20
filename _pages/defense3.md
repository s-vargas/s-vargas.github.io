---
layout: single
permalink: /defense3/
author_profile: false
sidebar: false
---

<style>
  /* ── Full-page background (desktop) ── */
  body {
    background-image: url('/images/grass_gif_partiful.gif') !important;
    background-size: cover !important;
    background-repeat: no-repeat !important;
    background-position: center center !important;
    background-attachment: fixed !important;
  }

  /* ── Mobile: use fixed div instead (iOS Safari fix) ── */
  @media (max-width: 768px) {
    body {
      background-image: none !important;
    }
  }

  /* ── Fixed background div for mobile ── */
  #bg-fixed {
    display: none;
  }
  @media (max-width: 768px) {
    #bg-fixed {
      display: block;
      position: fixed;
      inset: 0;
      z-index: -1;
      background-image: url('/images/grass_gif_partiful.gif');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center center;
    }
  }

  /* ── Strip Minimal Mistakes white backgrounds ── */
  .page, #main, .page__content {
    background: transparent !important;
  }

  .page__content {
    max-width: 900px !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }

 /* ── Two-column layout ── */
.two-column-layout {
  display: flex;
  gap: 2rem;
  align-items: flex-start;
  flex-wrap: wrap;
}

/* Top section spans full width on desktop, sits left */
.top-section {
  width: 100%;
}

/* On desktop: scroll-column and fixed-column sit side by side below */
.scroll-column {
  flex: 1;
  min-width: 0;
}
.fixed-column {
  width: 350px;
  position: sticky;
  top: 1rem;
  height: fit-content;
}

/* ── Mobile: stack in order top → image → content ── */
@media (max-width: 768px) {
  .top-section  { order: 1; width: 100%; }
  .fixed-column { order: 2; position: static; width: 100%; }
  .scroll-column { order: 3; width: 100%; }
}
  /* ── Tiny avatar ── */
  .avatar {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    vertical-align: middle;
  }

  /* ── Blockquote ── */
  blockquote {
    backdrop-filter: blur(6px);
    -webkit-backdrop-filter: blur(6px);
    border-radius: 8px;
    padding: 2rem;
  }
</style>


<div id="bg-fixed"></div>

 <div class="defense-card"> 
  <div class="two-column-layout">
    <div class="scroll-column">
      <blockquote><img class="avatar" src="/images/tinyavatar.jpg" alt="picture of Sonia"> Sonia invited you! 💌</blockquote>
      <h1>⚔️🐢Defending My Shell🐢⚔️</h1>
      <section>
        <h2>Friday, July 10</h2>
        <p>12:00 PM EDT</p>
      </section>
      <p>🎓 Hosted by: <img class="avatar" src="/images/tinyavatar.jpg" alt="picture of Sonia"> Sonia</p>
      <p>
        I will be defending my dissertation project:
        <em>"Generations of Negotiation: Viewing U.S. Political Attitudes through the Lens of Contemporary Immigrant Generations"</em>
        in fulfillment of the requirements for the degree of Doctor of Philosophy in Government and Politics from the
        University of Maryland. Please RSVP for an accurate headcount and a spotlight at the bottom of the page!
      </p>
      <section>
        <h3>Virtual Attendance</h3>
        <ul>
          <li>For those unable to join in person, a Zoom link will be provided.</li>
          <li>Zoom<div class="two-column-layout">

  <!-- TOP: blockquote + title, always first -->
  <div class="top-section">
    <blockquote><img class="avatar" src="/images/tinyavatar.jpg" alt="picture of Sonia"> Sonia invited you! 💌</blockquote>
    <h1>⚔️🐢Defending My Shell🐢⚔️</h1>
  </div>

  <!-- MIDDLE on mobile: evite image + RSVP button -->
  <aside class="fixed-column">
    <img src="/images/Dissertation_Defense_Evite.jpg" width="auto" height="auto" alt="Dissertation Defense Evite">
    <section style="text-align: center;">
      <h3>RSVP</h3>
      <button onclick="document.getElementById('rsvp-modal').style.display='flex'"
              style="
                background: #FAF2F2;
                border: none;
                border-radius: 20px;
                padding: 0.6rem 1.4rem;
                font-size: 1rem;
                cursor: pointer;
                font-family: inherit;
                box-shadow: 0 2px 8px rgba(0,0,0,0.15);
              ">
        👍
      </button>
    </section>
  </aside>

  <!-- BOTTOM: rest of the content -->
  <div class="scroll-column">
    <section>
      <h2>Friday, July 10</h2>
      <p>12:00 PM EDT</p>
    </section>
    <p>🎓 Hosted by: <img class="avatar" src="/images/tinyavatar.jpg" alt="picture of Sonia"> Sonia</p>
    <p>
      I will be defending my dissertation project:
      <em>"Generations of Negotiation: Viewing U.S. Political Attitudes through the Lens of Contemporary Immigrant Generations"</em>
      in fulfillment of the requirements for the degree of Doctor of Philosophy in Government and Politics from the
      University of Maryland. Please RSVP for an accurate headcount and a spotlight at the bottom of the page!
    </p>
    <section>
      <h3>Virtual Attendance</h3>
      <ul>
        <li>For those unable to join in person, a Zoom link will be provided.</li>
        <li>Zoom Meeting Link: <em>TBD</em></li>
      </ul>
    </section>
    <section>
      <h3>Guest List</h3>
      <ul></ul>
    </section>
    <em>Please contact svargas@umd.edu if you have any questions!</em>
    <p><a href="https://nyc-noise.com/drone-party/">x</a></p>
  </div>

</div>
