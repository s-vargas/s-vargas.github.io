---
layout: single
permalink: /defense3/
author_profile: false
sidebar: false
---

<style>
  /* ── Make the GIF cover the ENTIRE page background ── */
  body {
    background-image: url('/images/grass_gif_partiful.gif') !important;
    background-size: cover !important;
    background-repeat: no-repeat !important;
    background-position: center center !important;
    background-attachment: fixed !important;
  }

  /* ── Remove the white box that Minimal Mistakes puts around page content ── */
  .page {
    background: transparent !important;
  }

  #main {
    background: transparent !important;
  }

  /* ── Let the content stretch wider and remove the width cap ── */
  .page__content {
    max-width: 900px !important;
    margin-left: auto !important;
    margin-right: auto !important;
    background: transparent !important;
  }

  /* ── Give your card a frosted/white background so text is readable ── */
  .defense-card {
    background: rgba(255, 255, 255, 0.25);
    backdrop-filter: blur(6px);
    -webkit-backdrop-filter: blur(6px);
    border-radius: 16px;
    padding: 2rem;
  }

  /* ── Two column layout ── */
  .two-column-layout {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
  }
  .scroll-column { flex: 1; }
  .fixed-column {
    width: 350px;
    position: sticky;
    top: 1rem;
    height: fit-content;
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
    padding: 0.75rem 1rem;
    border-radius: 8px;
    background: #FAF2F2;
    border-left: 3px solid #FFDEED;
    margin: 1rem 0;
  }

  /* ── Mobile ── */
  @media (max-width: 768px) {
    .two-column-layout { flex-direction: column; }
    .fixed-column { order: -1; position: static; width: 100%; }
  }
</style>

<div class="defense-card">
  <div class="two-column-layout">
    <div class="scroll-column">
      <blockquote><img class="avatar" src="/images/tinyavatar.jpg" alt="picture of Sonia"> Sonia invited you! 💌</blockquote>
      <h1>⚔️🐢Defending My Shell🐢⚔️</h1>
      <section>
        <h2>July 10th, 2026</h2>
        <p>12:00 PM</p>
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
      <a href= "https://nyc-noise.com/drone-party/">x</a>
    </div>
    <aside class="fixed-column">
      <img src="/images/Dissertation_Defense_Evite.jpg" width="auto" height="auto" alt="Dissertation Defense Evite">
  <section style="text-align: center;">
  <h3>RSVP</h3> <!-- RSVP Button! -->
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

<!-- RSVP Modal, the pop up, the background, and being able to click out -->
<div id="rsvp-modal" onclick="if(event.target===this)this.style.display='none'" style=" 
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.5);
  backdrop-filter: blur(4px);
  z-index: 9999;
  justify-content: center;
  align-items: center;
">
  <div style="
    background: white;
    border-radius: 16px;
    padding: 1.5rem;
    max-width: 480px;
    width: 90%;
    max-height: 90vh;
    overflow-y: auto;
    position: relative;
    box-shadow: 0 8px 32px rgba(0,0,0,0.2);
  ">
    <button onclick="document.getElementById('rsvp-modal').style.display='none'" style="
      position: absolute;
      top: 0.75rem;
      right: 0.75rem;
      background: #FAF2F2;
      border: none;
      border-radius: 50%;
      width: 28px;
      height: 28px;
      font-size: 1rem;
      cursor: pointer;
      line-height: 1;
    ">✕</button>
    <h3 style="margin-top:0;">👍 RSVP</h3>
    <iframe
      src="https://docs.google.com/forms/d/e/1FAIpQLSeWVrfyCb93FyXVR1wuGnnAC-bRfPutclS7-3aCzppddc8yqQ/viewform?embedded=true"
      width="100%"
      height="700"
      frameborder="0"
      marginheight="0"
      marginwidth="0">
    </iframe>
  </div>
</div>
    </aside>
  </div>
</div>
