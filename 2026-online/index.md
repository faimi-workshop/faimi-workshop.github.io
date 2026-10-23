---
title: Fairness of AI in Medical Imaging
description: "2026 Online Symposium"
layout: default
permalink: /2026-online/index.html
weight: -1
redirect_from: /2026-online/
---

<style>
  .symposium-hero {
    position: relative; overflow: hidden; margin: 1rem 0 2rem; padding: 2.25rem;
    border-radius: 16px; color: #fff; background: linear-gradient(135deg, #173f62 0%, #2e73b8 100%);
    box-shadow: 0 12px 30px rgba(23, 63, 98, 0.22);
  }
  .symposium-hero::after {
    content: ""; position: absolute; right: -70px; top: -90px; width: 260px; height: 260px;
    border: 45px solid rgba(255, 255, 255, 0.07); border-radius: 50%;
  }
  .symposium-hero > * { position: relative; z-index: 1; }
  .symposium-eyebrow {
    margin: 0 0 0.45rem; color: #cfe7ff; font-size: 0.78rem;
    font-weight: 700; letter-spacing: 0.16em; text-transform: uppercase;
  }
  .symposium-hero h2 { margin: 0; color: #fff; font-size: clamp(1.8rem, 5vw, 2.8rem); line-height: 1.12; }
  .symposium-summary { max-width: 650px; margin: 0.9rem 0 1.4rem; color: #e8f3ff; font-size: 1.05rem; }
  .symposium-facts {
    display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 0.75rem;
    margin: 0 0 1.5rem; padding: 0; list-style: none;
  }
  .symposium-facts li {
    margin: 0; padding: 0.8rem 0.9rem; border: 1px solid rgba(255, 255, 255, 0.2);
    border-radius: 8px; background: rgba(255, 255, 255, 0.09);
  }
  .symposium-facts strong { display: block; margin-bottom: 0.15rem; color: #fff; }
  .symposium-keynote {
    margin: 0 0 1.5rem; padding: 1.15rem 1.25rem; border-left: 4px solid #9ed0ff;
    border-radius: 0 9px 9px 0; background: rgba(255, 255, 255, 0.11);
  }
  .symposium-keynote .label {
    display: block; margin-bottom: 0.35rem; color: #cfe7ff;
    font-size: 0.75rem; font-weight: 700; letter-spacing: 0.12em; text-transform: uppercase;
  }
  .symposium-keynote a { color: #fff; font-size: 1.2rem; font-weight: 700; }
  .symposium-keynote .affiliation { display: block; margin-top: 0.2rem; color: #e8f3ff; }
  .symposium-keynote .talk-title { margin: 0.8rem 0 0; color: #fff; font-size: 1.05rem; font-weight: 700; }
  .symposium-keynote .talk-label { color: #cfe7ff; font-size: 0.75rem; letter-spacing: 0.08em; text-transform: uppercase; }
  .symposium-register {
    display: inline-block; padding: 0.85rem 1.45rem; border-radius: 7px;
    color: #173f62 !important; background: #fff; font-weight: 700; text-decoration: none;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.16);
  }
  .symposium-register:hover { background: #eef7ff; text-decoration: none; }
  .keynote-details {
    margin: 0 0 1.25rem; padding: 1.4rem 1.5rem; border: 1px solid #dce4ec;
    border-radius: 10px; background: #fff; box-shadow: 0 5px 16px rgba(36, 50, 75, 0.06);
  }
  .keynote-details h2 { margin-top: 0; color: #24324b; font-size: 1.35rem; }
  .keynote-details p:last-child { margin-bottom: 0; }
  .online-agenda {
    width: 100%; margin: 1rem 0 2rem; overflow: hidden;
    border: 1px solid #dce4ec; border-radius: 12px;
    border-collapse: separate; border-spacing: 0;
    box-shadow: 0 8px 24px rgba(36, 50, 75, 0.08);
  }
  .online-agenda th {
    padding: 0.85rem 1rem; color: #fff; background: #2e73b8;
    font-size: 0.8rem; letter-spacing: 0.06em; text-align: left; text-transform: uppercase;
  }
  .online-agenda th:first-child { width: 100px; }
  .online-agenda td { padding: 0.95rem 1rem; border-bottom: 1px solid #e7edf3; vertical-align: top; }
  .online-agenda tr:last-child td { border-bottom: 0; }
  .online-agenda tbody tr:nth-child(even) { background: #f7faff; }
  .online-agenda .agenda-time { color: #2e73b8; font-weight: 700; white-space: nowrap; }
  .online-agenda .agenda-title { display: block; color: #24324b; font-weight: 700; }
  .online-agenda .agenda-detail { display: block; margin-top: 0.2rem; color: #606c71; }
  .online-agenda .agenda-keynote td { background: #eef6ff; }
  .online-agenda .agenda-break td { background: #fff8ec; }
  .online-agenda .agenda-section td {
    padding: 0.55rem 1rem; color: #285f96; background: #e4f0fc;
    font-size: 0.78rem; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase;
  }
  @media (max-width: 640px) {
    .symposium-hero { padding: 1.5rem; }
    .symposium-facts { grid-template-columns: 1fr; }
    .online-agenda, .online-agenda tbody, .online-agenda tr, .online-agenda td { display: block; }
    .online-agenda { border: 0; border-radius: 0; box-shadow: none; }
    .online-agenda thead { position: absolute; width: 1px; height: 1px; overflow: hidden; clip: rect(0 0 0 0); }
    .online-agenda tr { margin-bottom: 0.7rem; border: 1px solid #dce4ec; border-radius: 8px; overflow: hidden; }
    .online-agenda td { border: 0; }
    .online-agenda .agenda-time { padding-bottom: 0; }
    .online-agenda td + td { padding-top: 0.35rem; }
  }
</style>

<section class="symposium-hero">
  <p class="symposium-eyebrow">Fairness of AI in Medical Imaging</p>
  <h2>FAIMI 2026 Online Symposium</h2>
  <p class="symposium-summary">Join researchers, clinicians, and AI experts for an afternoon exploring fairness, evaluation, regulation, and trustworthy AI in medical imaging.</p>

  <ul class="symposium-facts">
    <li><strong>Tuesday</strong>24 November 2026</li>
    <li><strong>13:30&ndash;17:00 GMT</strong>Afternoon programme</li>
    <li><strong>Free</strong>Fully online</li>
  </ul>

  <div class="symposium-keynote">
    <span class="label">Keynote speaker</span>
    <a href="https://www.linkedin.com/in/ghada-zamzmi-10978589/">Dr. Ghada Zamzmi</a>
    <span class="affiliation">Heartflow</span>
    <p class="talk-title"><span class="talk-label">Keynote talk</span><br>The Fairness Illusion: When Equal Errors Hide Unequal Harm</p>
  </div>

  <a class="symposium-register" href="https://us02web.zoom.us/webinar/register/WN__UE1NqHDS0ytUEdCV_2AGw">Register for free &rarr;</a>
</section>

## Agenda

<table class="online-agenda">
  <thead>
    <tr><th scope="col">Time</th><th scope="col">Item</th></tr>
  </thead>
  <tbody>
    <tr><td class="agenda-time">13:30</td><td><span class="agenda-title">Opening remarks</span></td></tr>
    <tr class="agenda-keynote"><td class="agenda-time">13:40</td><td><span class="agenda-title">Keynote</span><span class="agenda-detail"><strong>Ghada Zamzmi</strong> (Heartflow): <em>The Fairness Illusion: When Equal Errors Hide Unequal Harm</em></span></td></tr>
    <tr class="agenda-break"><td class="agenda-time">14:45</td><td><span class="agenda-title">Break</span></td></tr>
    <tr class="agenda-section"><td colspan="2">Short talks</td></tr>
    <tr><td class="agenda-time">15:00</td><td><span class="agenda-title">Amelia Jiménez-Sánchez</span><span class="agenda-detail"><em>In the Picture: Medical Imaging Datasets, Artifacts, and their Living Review</em></span></td></tr>
    <tr><td class="agenda-time">15:15</td><td><span class="agenda-title">Matthew Cockayne</span><span class="agenda-detail"><em>Fair Curriculum Learning for Concept Bottleneck Models in Dermatology</em></span></td></tr>
    <tr><td class="agenda-time">15:30</td><td><span class="agenda-title">Alceu Bissoto</span><span class="agenda-detail"><em>On Evaluating Subgroup Discovery in Medical Image Classification</em></span></td></tr>
    <tr><td class="agenda-time">15:45</td><td><span class="agenda-title">Aparajita Kashyap</span><span class="agenda-detail"><em>A Pipeline for Enabling Path-specific Causal Fairness in Observational Health Data</em></span></td></tr>
    <tr><td class="agenda-time">16:00</td><td><span class="agenda-title">Xiaoxiao Li</span><span class="agenda-detail"><em>DUCX: Decomposing Unfairness in Tool-Using Chest X-Ray Agents</em></span></td></tr>
    <tr><td class="agenda-time">16:15</td><td><span class="agenda-title">FAIMI: What&rsquo;s Next?</span></td></tr>
    <tr><td class="agenda-time">16:55</td><td><span class="agenda-title">Closing remarks</span></td></tr>
  </tbody>
</table>

<section class="keynote-details">
  <h2>Keynote Abstract</h2>
  <p>Fairness in medical AI has largely been framed as a problem of statistical parity. But parity metrics say little about clinical meaning—the same model error or failure can carry very different consequences depending on who the patient is, what the model is intended to do, and what clinical decision follows from its output.</p>
  <p>In this talk, drawing on a practical and regulatory-science perspective, I will present a framework for evaluating clinical AI around its intended-use population and the clinical outcomes it is meant to produce, rather than around statistical parity alone. Instead of asking only whether models are fair, I will show why the operative questions are who benefits when the model succeeds, who is harmed when it fails, and whether that harm is acceptable for the patients the technology is meant to serve. I will lay out a hierarchy of fairness questions that follows the clinical pathway from model to patient: prediction fairness, clinical response fairness, and outcome fairness. I will close with examples where favorable statistical performance failed to translate into comparable clinical benefit, and show why fair evaluation of clinical AI requires new metrics and study designs.</p>
</section>

<section class="keynote-details">
  <h2>About Dr. Ghada Zamzmi</h2>
  <p>Ghada Zamzmi is an AI researcher and regulatory scientist working at the intersection of artificial intelligence, healthcare, and real-world deployment. Over the past decade, she has worked across academia, government, and industry. She earned her PhD from the University of South Florida, where her research focused on multimodal AI for assessing neonatal emotions. She later worked as an AI research scientist at the National Institutes of Health, followed by a role as a staff scientist at the U.S. Food and Drug Administration, where she evaluated the safety and reliability of AI technologies deployed in clinical practice worldwide. She also serves as a subject matter expert for the European Innovation Council and SMEs Executive Agency (EISMEA), and currently works as a Regulatory Science Principal at Heartflow.</p>
  <p>Her research spans multimodal AI, medical imaging, responsible AI development and deployment, and the regulatory science challenges of AI-enabled medical devices. She is passionate about bridging the gap between innovative AI development and the safe, effective, and reasonable deployment of these technologies in real-world clinical practice. She has received several recognitions, including MIT Innovators Under 35, and serves on organizing committees for leading conferences and organizations.</p>
</section>
