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
    background-color: rgb(218,205,112);
  }

  /* ── Masthead + footer transparency ── */
  .masthead, .page__footer {
    background: transparent !important;
  }
  .masthead a, .page__footer a, .page__footer p {
    color: #fff !important;
    text-shadow: 0 1px 3px rgba(0,0,0,0.6);
  }

  /* ── Mobile: use fixed div instead (iOS Safari fix) ── */
  @media (max-width: 768px) {
    body { background-image: none !important; }
  }

  /* ── Fixed background div for mobile ── */
  #bg-fixed { display: none; }
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

  /* ── Outer layout: left col + right col side by side ── */
  .two-column-layout {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
  }

  /* ── LEFT: stacks top-section + scroll-column vertically ── */
  .left-column {
    flex: 1;
    min-width: 0;
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }

  /* ── RIGHT: sticky image + RSVP ── */
  .fixed-column {
    width: 350px;
    flex-shrink: 0;
    position: sticky;
    top: 1rem;
    height: fit-content;
  }

  /* ── Mobile: unwrap left-column, reorder all four pieces ── */
  @media (max-width: 768px) {
    .two-column-layout {
      flex-direction: column;
    }
    .left-column {
      display: contents; /* lets children participate in flex order directly */
    }
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
    text-align: center;
    backdrop-filter: blur(3px);
    -webkit-backdrop-filter: blur(3px);
    border-radius: 15px;
    padding: 2rem;
    border: 1px solid #eaf0f0;
  }

</style>

<div id="bg-fixed"></div>

<div class="two-column-layout">

  <!-- LEFT COLUMN: title on top, content below -->
  <div class="left-column">

    <div class="top-section">
      <blockquote><img class="avatar" src="/images/tinyavatar.jpg" alt="picture of Sonia"> Sonia invited you! 💌</blockquote>
      <h1>⚔️🐢Defending My Shell🐢⚔️</h1>
    </div>

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

  <!-- RIGHT COLUMN: sticky image + RSVP -->
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

</div>

<!-- RSVP Modal -->
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
