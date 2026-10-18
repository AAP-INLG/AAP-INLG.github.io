---
title: "Program"
featured_image: "/images/utrecht-netherlands.jpg"
description: "Workshop schedule for AAP 2026"
---

*Sunday afternoon, 18 October 2026 · Spoorwegmuseum, Utrecht, Netherlands*

**Room:** Wachtkamer 3e Klasse

---

## Schedule

<style>
  .program { margin: 2rem 0; }
  .program-item, .program-session {
    border-top: 1px solid #d9d9d9;
    padding: 1.25rem 0;
  }
  .program-item, .program-session-header, .program-talk {
    display: grid;
    grid-template-columns: 8rem minmax(0, 1fr);
    gap: 1.5rem;
  }
  .program-time {
    color: #555;
    font-weight: 700;
    white-space: nowrap;
  }
  .program-title {
    font-size: 1.1rem;
    font-weight: 700;
    line-height: 1.4;
  }
  .program-description, .program-speaker {
    color: #555;
    margin-top: 0.25rem;
  }
  .keynote-image {
    display: block;
    width: 320px;
    max-width: 100%;
    height: auto;
    margin: 1rem 0;
    border-radius: 0.25rem;
  }
  .keynote-bio {
    color: #555;
    margin-top: 0.75rem;
  }
  .program-talks {
    border-left: 3px solid #ddd;
    margin: 1rem 0 0 9.5rem;
    padding-left: 1rem;
  }
  .program-talk {
    grid-template-columns: 7rem minmax(0, 1fr);
    gap: 2rem;
    padding: 0.75rem 0;
  }
  .program-talk + .program-talk { border-top: 1px solid #eee; }
  .program-note {
    background: #f5f5f5;
    border-left: 4px solid #777;
    margin-top: 2rem;
    padding: 1rem 1.25rem;
  }
  @media (max-width: 600px) {
    .program-item, .program-session-header, .program-talk {
      grid-template-columns: 1fr;
      gap: 0.25rem;
    }
    .program-talks {
      margin-left: 0;
      margin-top: 1rem;
    }
  }
</style>

<div class="program">
  <div class="program-item">
    <div class="program-time">12:30–13:30</div>
    <div>
      <div class="program-title">Lunch</div>
      <div class="program-description">Provided at the venue free of charge</div>
    </div>
  </div>

  <div class="program-item">
    <div class="program-time">13:30–13:45</div>
    <div>
      <div class="program-title">Welcome and Introduction</div>
      <div class="program-description">Opening remarks and an overview of the workshop</div>
    </div>
  </div>

  <div class="program-item" id="keynote">
    <div class="program-time">13:45–14:30</div>
    <div>
      <div class="program-title">Keynote: From Found to Designed: Concepts as a Design Axis for Large Language Models <a class="paper-pdf" href="/pdfs/1_from-found-to-designed.pdf" aria-label="PDF: From Found to Designed: Concepts as a Design Axis for Large Language Models">PDF</a></div>
      <div class="program-speaker">Chen Shani</div>
      <img class="keynote-image" src="/images/chen-shani.jpg" alt="Chen Shani">
      <div class="keynote-bio">Chen Shani is a Senior Lecturer at Tel Aviv University, where she leads the CoAI Lab, studying concepts, knowledge, and cognition in AI systems. Her research focuses on understanding what language models represent, how their knowledge is organized, and how these representations can be deliberately shaped. Before joining Tel Aviv University, she was a postdoctoral researcher at Stanford University and a researcher at Amazon. She holds a PhD in Computer Science from the Hebrew University of Jerusalem.</div>
    </div>
  </div>

  <section class="program-session">
    <div class="program-session-header">
      <div class="program-time">14:30–15:30</div>
      <div>
        <div class="program-title">Presentation Session 1</div>
        <div class="program-description">Accepted paper presentations and discussion</div>
      </div>
    </div>
    <div class="program-talks">
      <div class="program-talk">
        <div class="program-time">14:30–14:50</div>
        <div>
          <div class="program-title">Scan Order Is a Reasoning Prior: Geometry-Aware Multi-Directional Mamba-2 for Tiny Recursive Reasoning <a class="paper-pdf" href="/pdfs/5_scan-order-reasoning-prior.pdf" aria-label="PDF: Scan Order Is a Reasoning Prior: Geometry-Aware Multi-Directional Mamba-2 for Tiny Recursive Reasoning">PDF</a></div>
          <div class="program-speaker">Zhenxuan Yu</div>
        </div>
      </div>
      <div class="program-talk">
        <div class="program-time">14:50–15:10</div>
        <div>
          <div class="program-title">Reconstructing Locality-Disrupted Text: Effects of Architecture and Scale <a class="paper-pdf" href="/pdfs/4_reconstructing-locality-disrupted-text.pdf" aria-label="PDF: Reconstructing Locality-Disrupted Text: Effects of Architecture and Scale">PDF</a></div>
          <div class="program-speaker">Evelien van Driel, Amirhossein Mohammadi, Robert A. Bagheri</div>
        </div>
      </div>
      <div class="program-talk">
        <div class="program-time">15:10–15:30</div>
        <div>
          <div class="program-title"><del>A Scrambled Positional Encoding Is Worse Than None</del> <a class="paper-pdf" href="/pdfs/2_scrambled-positional-encoding.pdf" aria-label="PDF: A Scrambled Positional Encoding Is Worse Than None">PDF</a></div>
          <div class="program-speaker"><del>Srinivas Harish</del></div>
          <div class="program-description">Cancelled — presenter unable to attend</div>
        </div>
      </div>
    </div>
  </section>

  <div class="program-item">
    <div class="program-time">15:30–15:45</div>
    <div>
      <div class="program-title">Coffee Break</div>
      <div class="program-description">Refreshments and conversation</div>
    </div>
  </div>

  <section class="program-session">
    <div class="program-session-header">
      <div class="program-time">15:45–16:45</div>
      <div>
        <div class="program-title">Presentation Session 2</div>
        <div class="program-description">Accepted paper presentations and discussion</div>
      </div>
    </div>
    <div class="program-talks">
      <div class="program-talk">
        <div class="program-time">15:45–16:05</div>
        <div>
          <div class="program-title">Does SAM Pay Off? A Cost-Adjusted Analysis of Sharpness-Aware Pretraining <a class="paper-pdf" href="/pdfs/6_does-sam-pay-off.pdf" aria-label="PDF: Does SAM Pay Off? A Cost-Adjusted Analysis of Sharpness-Aware Pretraining">PDF</a></div>
          <div class="program-speaker">Ivan Maksimov, Joqsan Azocar, Vasily Konovalov</div>
        </div>
      </div>
      <div class="program-talk">
        <div class="program-time">16:05–16:25</div>
        <div>
          <div class="program-title">Small Encoder-Decoders as Tool-Calling Backbones: A Capability Decomposition at 270M–1B <a class="paper-pdf" href="/pdfs/7_small-encoder-decoders-tool-calling.pdf" aria-label="PDF: Small Encoder-Decoders as Tool-Calling Backbones: A Capability Decomposition at 270M–1B">PDF</a></div>
          <div class="program-speaker">Sergey Pletenev</div>
        </div>
      </div>
      <div class="program-talk">
        <div class="program-time">16:25–16:45</div>
        <div>
          <div class="program-title">Autoregressive vs. Diffusion Language Models for Clinical Text Summarisation <a class="paper-pdf" href="/pdfs/9_autoregressive-vs-diffusion.pdf" aria-label="PDF: Autoregressive vs. Diffusion Language Models for Clinical Text Summarisation">PDF</a></div>
          <div class="program-speaker">Carlos Alejandro Conde Giron, Zexuan Li, Robert A. Bagheri, Ruurd Jan Anthonius Kuiper</div>
        </div>
      </div>
    </div>
  </section>

  <div class="program-item">
    <div class="program-time">16:45–17:00</div>
    <div>
      <div class="program-title">Closing Discussion</div>
      <div class="program-description">Reflections, next steps, and goodbye</div>
    </div>
  </div>

  <div class="program-item">
    <div class="program-time">17:00</div>
    <div class="program-title">Reception @ Academiegebouw</div>
  </div>
</div>

<div class="program-note"><strong>Talk format:</strong> Each accepted-paper talk consists of a 15-minute presentation followed by 5 minutes for questions.</div>

## Attendee Information

The workshop takes place at the [Spoorwegmuseum (The Railway Museum)](https://www.spoorwegmuseum.nl/), Maliebaanstation 16, 3581 XW Utrecht. Lunch is provided at the venue free of charge.

Attendance requires [INLG 2026 registration](https://2026.inlgmeeting.org/registration.html). The welcome reception at the Academiegebouw is free with registration.
