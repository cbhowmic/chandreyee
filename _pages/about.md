---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="lp-wrapper">

<!-- ═══════════════════════════════════════════
     HERO
════════════════════════════════════════════ -->
<section class="lp-hero">
  <div class="lp-hero__role">
    <span class="lp-hero__role-dot"></span>
    Ph.D. Researcher, Vanderbilt University &amp; Oak Ridge National Laboratory
  </div>
  <h1 class="lp-hero__name">Chandreyee Bhowmick</h1>
  <p class="lp-hero__tagline">Distributed Learning &nbsp;·&nbsp; Resilient AI &nbsp;·&nbsp; Multi-Agent Systems</p>
  <p class="lp-hero__intro">
    I design <strong>resilient machine learning algorithms</strong> for distributed and federated settings,
    where adversarial agents may corrupt model updates or system behavior. My work spans
    <strong>federated learning</strong>, <strong>multi-agent reinforcement learning</strong>, and
    <strong>cyber-physical systems security</strong> — building provably robust aggregation methods
    that maintain accuracy even under Byzantine attacks and model poisoning.
  </p>
  <div class="lp-hero__ctas">
    <a href="/publications/" class="lp-btn lp-btn--primary">
      <i class="fas fa-book-open"></i> Publications
    </a>
    <a href="/cv/" class="lp-btn lp-btn--outline">
      <i class="fas fa-file-alt"></i> Curriculum Vitae
    </a>
    <a href="mailto:chandreyee.bhowmick@vanderbilt.edu" class="lp-btn lp-btn--outline">
      <i class="fas fa-envelope"></i> Get in Touch
    </a>
  </div>
</section>

<!-- ═══════════════════════════════════════════
     STATS
════════════════════════════════════════════ -->
<div class="lp-stats-grid">
  <div class="lp-stat-card">
    <div class="lp-stat-card__number" data-count="19" data-suffix="">19</div>
    <div class="lp-stat-card__label">Publications</div>
  </div>
  <div class="lp-stat-card">
    <div class="lp-stat-card__number" data-count="234" data-suffix="">234</div>
    <div class="lp-stat-card__label">Citations</div>
  </div>
  <div class="lp-stat-card">
    <div class="lp-stat-card__number" data-count="5" data-suffix="">5</div>
    <div class="lp-stat-card__label">h-index</div>
  </div>
  <div class="lp-stat-card">
    <div class="lp-stat-card__number" data-count="10" data-suffix="+">10+</div>
    <div class="lp-stat-card__label">Years Research</div>
  </div>
</div>

<hr class="lp-divider">

<!-- ═══════════════════════════════════════════
     RESEARCH AREAS
════════════════════════════════════════════ -->
<span class="lp-section-label">Focus Areas</span>
<h2 class="lp-section-title">Research</h2>

<div class="lp-research-grid">

  <div class="lp-research-card">
    <div class="lp-research-card__icon"><i class="fas fa-network-wired"></i></div>
    <div class="lp-research-card__title">Resilient Federated &amp; Distributed Learning</div>
    <p class="lp-research-card__desc">
      Designing aggregation mechanisms — trimmed means, clipping, soft-medoid, adaptive
      aggregation — that remain accurate under Byzantine faults and model poisoning attacks
      in both federated and peer-to-peer distributed learning settings.
    </p>
  </div>

  <div class="lp-research-card">
    <div class="lp-research-card__icon"><i class="fas fa-robot"></i></div>
    <div class="lp-research-card__title">Multi-Agent Reinforcement Learning</div>
    <p class="lp-research-card__desc">
      Building resilient distributed actor-critic algorithms and flocking/formation
      controllers for multi-agent systems, with provable convergence guarantees even
      when a fraction of agents behave adversarially.
    </p>
  </div>

  <div class="lp-research-card">
    <div class="lp-research-card__icon"><i class="fas fa-shield-alt"></i></div>
    <div class="lp-research-card__title">Cyber-Physical Systems Security</div>
    <p class="lp-research-card__desc">
      Developing learning-based attack detection and mitigation for networked control
      systems, including neural network estimators and χ² detectors for sensor and
      actuator attacks in stochastic linear and nonlinear systems.
    </p>
  </div>

</div>

<hr class="lp-divider">

<!-- ═══════════════════════════════════════════
     FEATURED RESEARCH (SVG animations)
════════════════════════════════════════════ -->
<span class="lp-section-label">Highlighted Work</span>
<h2 class="lp-section-title">Featured Research</h2>

<div class="lp-projects-grid" style="grid-template-columns: repeat(2, 1fr);">

  <!-- ── Project 1: Federated Learning ── -->
  <div class="lp-project-card">
    <svg class="lp-project-card__visual" viewBox="0 0 280 140" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <defs>
        <linearGradient id="fl-bg" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#071526"/>
          <stop offset="100%" stop-color="#0d3358"/>
        </linearGradient>
        <filter id="fl-glow">
          <feGaussianBlur stdDeviation="2.2" result="b"/>
          <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
        <filter id="fl-red-glow">
          <feGaussianBlur stdDeviation="2.8" result="b"/>
          <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
      </defs>
      <rect width="280" height="140" fill="url(#fl-bg)"/>

      <!-- Good client → server lines -->
      <line x1="38" y1="28"  x2="130" y2="68" stroke="rgba(66,165,245,0.35)" stroke-width="1.2" stroke-dasharray="4,3"><animate attributeName="opacity" values="0.35;0.75;0.35" dur="2.1s" repeatCount="indefinite"/></line>
      <line x1="15" y1="72"  x2="130" y2="72" stroke="rgba(66,165,245,0.35)" stroke-width="1.2" stroke-dasharray="4,3"><animate attributeName="opacity" values="0.35;0.75;0.35" dur="2.6s" repeatCount="indefinite"/></line>
      <line x1="38" y1="112" x2="130" y2="76" stroke="rgba(66,165,245,0.35)" stroke-width="1.2" stroke-dasharray="4,3"><animate attributeName="opacity" values="0.35;0.75;0.35" dur="1.9s" repeatCount="indefinite"/></line>
      <line x1="210" y1="112" x2="150" y2="76" stroke="rgba(66,165,245,0.35)" stroke-width="1.2" stroke-dasharray="4,3"><animate attributeName="opacity" values="0.35;0.75;0.35" dur="2.3s" repeatCount="indefinite"/></line>

      <!-- Byzantine → server lines (partial, blocked) -->
      <line x1="230" y1="28" x2="185" y2="52" stroke="rgba(239,83,80,0.45)" stroke-width="1.2" stroke-dasharray="3,3"/>
      <line x1="258" y1="72" x2="197" y2="72" stroke="rgba(239,83,80,0.45)" stroke-width="1.2" stroke-dasharray="3,3"/>

      <!-- Animated good gradient packets -->
      <circle r="3.2" fill="#42a5f5" opacity="0" filter="url(#fl-glow)">
        <animateMotion dur="1.9s" repeatCount="indefinite" begin="0s"   path="M38,28  L130,68"/>
        <animate attributeName="opacity" values="0;1;0" dur="1.9s" repeatCount="indefinite" begin="0s"/>
      </circle>
      <circle r="3.2" fill="#42a5f5" opacity="0" filter="url(#fl-glow)">
        <animateMotion dur="2.2s" repeatCount="indefinite" begin="0.7s" path="M15,72  L130,72"/>
        <animate attributeName="opacity" values="0;1;0" dur="2.2s" repeatCount="indefinite" begin="0.7s"/>
      </circle>
      <circle r="3.2" fill="#42a5f5" opacity="0" filter="url(#fl-glow)">
        <animateMotion dur="2.0s" repeatCount="indefinite" begin="1.3s" path="M38,112 L130,76"/>
        <animate attributeName="opacity" values="0;1;0" dur="2.0s" repeatCount="indefinite" begin="1.3s"/>
      </circle>
      <circle r="3.2" fill="#42a5f5" opacity="0" filter="url(#fl-glow)">
        <animateMotion dur="1.8s" repeatCount="indefinite" begin="0.4s" path="M210,112 L150,76"/>
        <animate attributeName="opacity" values="0;1;0" dur="1.8s" repeatCount="indefinite" begin="0.4s"/>
      </circle>

      <!-- Animated bad packets (stop mid-way) -->
      <circle r="3.2" fill="#ef5350" opacity="0" filter="url(#fl-red-glow)">
        <animateMotion dur="1.4s" repeatCount="indefinite" begin="0.5s" path="M230,28 L185,52"/>
        <animate attributeName="opacity" values="0;0.9;0" dur="1.4s" repeatCount="indefinite" begin="0.5s"/>
      </circle>
      <circle r="3.2" fill="#ef5350" opacity="0" filter="url(#fl-red-glow)">
        <animateMotion dur="1.3s" repeatCount="indefinite" begin="1.5s" path="M258,72 L197,72"/>
        <animate attributeName="opacity" values="0;0.9;0" dur="1.3s" repeatCount="indefinite" begin="1.5s"/>
      </circle>

      <!-- Block markers -->
      <text x="181" y="51" fill="#ef9a9a" font-size="9" font-weight="bold" font-family="sans-serif">✕</text>
      <text x="193" y="75" fill="#ef9a9a" font-size="9" font-weight="bold" font-family="sans-serif">✕</text>

      <!-- Good client nodes -->
      <circle cx="38"  cy="28"  r="10" fill="rgba(66,165,245,0.14)" stroke="#42a5f5" stroke-width="1.4"/>
      <circle cx="38"  cy="28"  r="5"  fill="#42a5f5"/>
      <circle cx="15"  cy="72"  r="10" fill="rgba(66,165,245,0.14)" stroke="#42a5f5" stroke-width="1.4"/>
      <circle cx="15"  cy="72"  r="5"  fill="#42a5f5"/>
      <circle cx="38"  cy="112" r="10" fill="rgba(66,165,245,0.14)" stroke="#42a5f5" stroke-width="1.4"/>
      <circle cx="38"  cy="112" r="5"  fill="#42a5f5"/>
      <circle cx="210" cy="112" r="10" fill="rgba(66,165,245,0.14)" stroke="#42a5f5" stroke-width="1.4"/>
      <circle cx="210" cy="112" r="5"  fill="#42a5f5"/>

      <!-- Byzantine client nodes -->
      <circle cx="230" cy="28" r="12" fill="rgba(239,83,80,0.15)" stroke="#ef5350" stroke-width="1.5"><animate attributeName="r" values="12;14;12" dur="1.4s" repeatCount="indefinite"/></circle>
      <circle cx="230" cy="28" r="5.5" fill="#ef5350" filter="url(#fl-red-glow)"/>
      <circle cx="258" cy="72" r="12" fill="rgba(239,83,80,0.15)" stroke="#ef5350" stroke-width="1.5"><animate attributeName="r" values="12;14;12" dur="1.7s" repeatCount="indefinite"/></circle>
      <circle cx="258" cy="72" r="5.5" fill="#ef5350" filter="url(#fl-red-glow)"/>

      <!-- Central FL Server -->
      <circle cx="140" cy="72" r="26" fill="rgba(25,118,210,0.08)" stroke="none"><animate attributeName="r" values="26;32;26" dur="2.4s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.6;0.1;0.6" dur="2.4s" repeatCount="indefinite"/></circle>
      <circle cx="140" cy="72" r="20" fill="rgba(25,118,210,0.28)" stroke="#42a5f5" stroke-width="2" filter="url(#fl-glow)"/>
      <!-- Shield icon -->
      <path d="M140,60 L150,65 L150,74 Q150,82 140,85 Q130,82 130,74 L130,65 Z" fill="#1565c0" opacity="0.95"/>
      <path d="M136,73 L139,77 L145,68" stroke="#69f0ae" stroke-width="2.2" fill="none" stroke-linecap="round" stroke-linejoin="round"/>

      <!-- Labels -->
      <text x="18"  y="22"  fill="rgba(255,255,255,0.45)" font-size="6.2" font-family="sans-serif">benign</text>
      <text x="216" y="22"  fill="#ef9a9a" font-size="6.2" font-family="sans-serif">Byzantine</text>
      <text x="122" y="100" fill="#90caf9" font-size="6.8" font-weight="bold" font-family="sans-serif">FL Server</text>
      <text x="14"  y="136" fill="rgba(255,255,255,0.55)" font-size="8.5" font-family="sans-serif">Trimmed-Clipping Federated Aggregation</text>
    </svg>
    <div class="lp-project-card__body">
      <span class="lp-project-card__tag">Federated Learning · Byzantine Resilience</span>
      <div class="lp-project-card__title">Resilient Federated Learning via Trimmed-Clipping</div>
      <p class="lp-project-card__desc">
        Novel aggregation rule that combines gradient trimming with norm clipping at the
        FL server, provably filtering Byzantine and model poisoning attacks while
        preserving accuracy on benign data. Presented at IEEE TPS-ISA 2024.
      </p>
    </div>
  </div>

  <!-- ── Project 2: Resilient P2P Learning ── -->
  <div class="lp-project-card">
    <svg class="lp-project-card__visual" viewBox="0 0 280 140" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <defs>
        <linearGradient id="p2p-bg" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#07091a"/>
          <stop offset="100%" stop-color="#0e1740"/>
        </linearGradient>
        <filter id="p2p-blue-glow">
          <feGaussianBlur stdDeviation="2.5" result="b"/>
          <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
        <filter id="p2p-red-glow">
          <feGaussianBlur stdDeviation="3" result="b"/>
          <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
        <filter id="p2p-green-glow">
          <feGaussianBlur stdDeviation="2" result="b"/>
          <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
      </defs>
      <rect width="280" height="140" fill="url(#p2p-bg)"/>

      <!-- Mesh edges — pentagon outer ring + 2 diagonals -->
      <!-- Nodes: A(50,30) B(200,28) C(255,88) D(160,125) E(70,118) + center F(140,72) -->
      <!-- Outer ring edges -->
      <line x1="50"  y1="30"  x2="200" y2="28"  stroke="rgba(66,165,245,0.3)" stroke-width="1.1"><animate attributeName="opacity" values="0.3;0.65;0.3" dur="3.0s" repeatCount="indefinite"/></line>
      <line x1="200" y1="28"  x2="255" y2="88"  stroke="rgba(239,83,80,0.3)"  stroke-width="1.1"><animate attributeName="opacity" values="0.3;0.65;0.3" dur="2.5s" repeatCount="indefinite"/></line>
      <line x1="255" y1="88"  x2="160" y2="125" stroke="rgba(66,165,245,0.3)" stroke-width="1.1"><animate attributeName="opacity" values="0.3;0.65;0.3" dur="2.8s" repeatCount="indefinite"/></line>
      <line x1="160" y1="125" x2="70"  y2="118" stroke="rgba(66,165,245,0.3)" stroke-width="1.1"><animate attributeName="opacity" values="0.3;0.65;0.3" dur="2.2s" repeatCount="indefinite"/></line>
      <line x1="70"  y1="118" x2="50"  y2="30"  stroke="rgba(239,83,80,0.3)"  stroke-width="1.1"><animate attributeName="opacity" values="0.3;0.65;0.3" dur="3.2s" repeatCount="indefinite"/></line>
      <!-- Diagonal edges through center node -->
      <line x1="50"  y1="30"  x2="140" y2="72"  stroke="rgba(66,165,245,0.25)" stroke-width="1.0"><animate attributeName="opacity" values="0.25;0.55;0.25" dur="2.0s" repeatCount="indefinite"/></line>
      <line x1="200" y1="28"  x2="140" y2="72"  stroke="rgba(239,83,80,0.25)"  stroke-width="1.0"><animate attributeName="opacity" values="0.25;0.55;0.25" dur="2.3s" repeatCount="indefinite"/></line>
      <line x1="255" y1="88"  x2="140" y2="72"  stroke="rgba(66,165,245,0.25)" stroke-width="1.0"><animate attributeName="opacity" values="0.25;0.55;0.25" dur="1.9s" repeatCount="indefinite"/></line>
      <line x1="160" y1="125" x2="140" y2="72"  stroke="rgba(66,165,245,0.25)" stroke-width="1.0"><animate attributeName="opacity" values="0.25;0.55;0.25" dur="2.6s" repeatCount="indefinite"/></line>
      <line x1="70"  y1="118" x2="140" y2="72"  stroke="rgba(239,83,80,0.25)"  stroke-width="1.0"><animate attributeName="opacity" values="0.25;0.55;0.25" dur="2.1s" repeatCount="indefinite"/></line>

      <!-- Good data packets (blue) between good nodes -->
      <circle r="3" fill="#42a5f5" opacity="0" filter="url(#p2p-blue-glow)">
        <animateMotion dur="1.8s" repeatCount="indefinite" begin="0s"   path="M50,30 L140,72"/>
        <animate attributeName="opacity" values="0;1;0" dur="1.8s" repeatCount="indefinite" begin="0s"/>
      </circle>
      <circle r="3" fill="#42a5f5" opacity="0" filter="url(#p2p-blue-glow)">
        <animateMotion dur="2.0s" repeatCount="indefinite" begin="0.8s" path="M255,88 L140,72"/>
        <animate attributeName="opacity" values="0;1;0" dur="2.0s" repeatCount="indefinite" begin="0.8s"/>
      </circle>
      <circle r="3" fill="#42a5f5" opacity="0" filter="url(#p2p-blue-glow)">
        <animateMotion dur="1.7s" repeatCount="indefinite" begin="1.5s" path="M160,125 L140,72"/>
        <animate attributeName="opacity" values="0;1;0" dur="1.7s" repeatCount="indefinite" begin="1.5s"/>
      </circle>
      <circle r="3" fill="#42a5f5" opacity="0" filter="url(#p2p-blue-glow)">
        <animateMotion dur="2.1s" repeatCount="indefinite" begin="0.4s" path="M50,30 L200,28"/>
        <animate attributeName="opacity" values="0;1;0" dur="2.1s" repeatCount="indefinite" begin="0.4s"/>
      </circle>

      <!-- Bad packets from Byzantine nodes (red, fade partway) -->
      <circle r="3" fill="#ef5350" opacity="0" filter="url(#p2p-red-glow)">
        <animateMotion dur="1.4s" repeatCount="indefinite" begin="0.6s" path="M200,28 L140,72"/>
        <animate attributeName="opacity" values="0;0.85;0" dur="1.4s" repeatCount="indefinite" begin="0.6s"/>
      </circle>
      <circle r="3" fill="#ef5350" opacity="0" filter="url(#p2p-red-glow)">
        <animateMotion dur="1.5s" repeatCount="indefinite" begin="1.8s" path="M70,118 L140,72"/>
        <animate attributeName="opacity" values="0;0.85;0" dur="1.5s" repeatCount="indefinite" begin="1.8s"/>
      </circle>

      <!-- Adaptive filter checkmark at center (flashes after bad packet arrives) -->
      <circle cx="140" cy="72" r="6" fill="#69f0ae" opacity="0" filter="url(#p2p-green-glow)">
        <animate attributeName="opacity" values="0;0;0.9;0.9;0" dur="1.4s" repeatCount="indefinite" begin="1.9s"/>
      </circle>
      <circle cx="140" cy="72" r="6" fill="#69f0ae" opacity="0" filter="url(#p2p-green-glow)">
        <animate attributeName="opacity" values="0;0;0.9;0.9;0" dur="1.5s" repeatCount="indefinite" begin="3.0s"/>
      </circle>

      <!-- Good nodes -->
      <circle cx="50"  cy="30"  r="11" fill="rgba(66,165,245,0.15)" stroke="#42a5f5" stroke-width="1.4"/>
      <circle cx="50"  cy="30"  r="5.5" fill="#42a5f5" filter="url(#p2p-blue-glow)"/>
      <circle cx="255" cy="88"  r="11" fill="rgba(66,165,245,0.15)" stroke="#42a5f5" stroke-width="1.4"/>
      <circle cx="255" cy="88"  r="5.5" fill="#42a5f5" filter="url(#p2p-blue-glow)"/>
      <circle cx="160" cy="125" r="11" fill="rgba(66,165,245,0.15)" stroke="#42a5f5" stroke-width="1.4"/>
      <circle cx="160" cy="125" r="5.5" fill="#42a5f5" filter="url(#p2p-blue-glow)"/>

      <!-- Byzantine nodes (red pulsing) -->
      <circle cx="200" cy="28"  r="13" fill="rgba(239,83,80,0.15)" stroke="#ef5350" stroke-width="1.5"><animate attributeName="r" values="13;15;13" dur="1.6s" repeatCount="indefinite"/></circle>
      <circle cx="200" cy="28"  r="5.5" fill="#ef5350" filter="url(#p2p-red-glow)"/>
      <circle cx="70"  cy="118" r="13" fill="rgba(239,83,80,0.15)" stroke="#ef5350" stroke-width="1.5"><animate attributeName="r" values="13;15;13" dur="1.9s" repeatCount="indefinite"/></circle>
      <circle cx="70"  cy="118" r="5.5" fill="#ef5350" filter="url(#p2p-red-glow)"/>

      <!-- Center aggregation node -->
      <circle cx="140" cy="72" r="24" fill="rgba(25,118,210,0.08)" stroke="none"><animate attributeName="r" values="24;30;24" dur="2.2s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.2s" repeatCount="indefinite"/></circle>
      <circle cx="140" cy="72" r="17" fill="rgba(25,118,210,0.28)" stroke="#42a5f5" stroke-width="2" filter="url(#p2p-blue-glow)"/>
      <text x="131" y="75" fill="#e3f2fd" font-size="7.5" font-weight="bold" font-family="monospace">AGG</text>

      <!-- Labels -->
      <text x="26"  y="23"  fill="#90caf9" font-size="6.2" font-family="sans-serif">peer</text>
      <text x="186" y="22"  fill="#ef9a9a" font-size="6.2" font-family="sans-serif">adversarial</text>
      <text x="44"  y="113" fill="#ef9a9a" font-size="6.2" font-family="sans-serif">adversarial</text>

      <!-- Award badge -->
      <rect x="186" y="6" width="80" height="14" rx="4" fill="rgba(255,193,7,0.15)" stroke="rgba(255,193,7,0.5)" stroke-width="1"/>
      <text x="226" y="16" fill="#ffd54f" font-size="6.5" font-family="sans-serif" text-anchor="middle">🏆 Best Paper DCAI 2024</text>

      <text x="14"  y="136" fill="rgba(255,255,255,0.55)" font-size="8.5" font-family="sans-serif">Adaptive Aggregation — Byzantine-Resilient P2P</text>
    </svg>
    <div class="lp-project-card__body">
      <span class="lp-project-card__tag">Distributed Learning · P2P · Resilience</span>
      <div class="lp-project-card__title">Resilient Peer-to-Peer Learning via Adaptive Aggregation</div>
      <p class="lp-project-card__desc">
        Fully serverless federated learning where each node adaptively weights neighbor
        updates by gradient similarity, filtering Byzantine poisoning without any
        central coordinator. <strong>Best Paper Award — IEEE DCAI 2024.</strong>
      </p>
    </div>
  </div>

</div>

<hr class="lp-divider">

<!-- ═══════════════════════════════════════════
     NEWS / TIMELINE
════════════════════════════════════════════ -->
<span class="lp-section-label">Latest Updates</span>
<h2 class="lp-section-title">News &amp; Milestones</h2>

<ul class="lp-news-timeline">
  <li class="lp-news-item">
    <span class="lp-news-item__date">2025</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>New paper</strong> — "Decentralized Learning using Hashgraph Consensus" at
      <em>IEEE 49th Annual Computers, Software, and Applications Conference (COMPSAC) 2025</em>.
    </span>
  </li>
  <li class="lp-news-item">
    <span class="lp-news-item__date">2025</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>Papers under review</strong> — "Improving Resilient Aggregation Against Model Poisoning Attacks
      Using Efficient Trimming" (IEEE TISPN) and "Adaptive Aggregation Based Resilient Learning for
      Distributed Actor-Critic Algorithms" (JAAMAS, Springer).
    </span>
  </li>
  <li class="lp-news-item">
    <span class="lp-news-item__date">2024</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>🏆 Best Paper Award</strong> at <em>IEEE International Conference on Distributed Computing
      and Artificial Intelligence (DCAI) 2024</em> for "Resilient Peer-to-Peer Learning based on
      Adaptive Aggregation."
    </span>
  </li>
  <li class="lp-news-item">
    <span class="lp-news-item__date">2024</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>Student Travel Award</strong> to attend <em>IEEE TPS-ISA 2024</em>. Presented
      "Resilient Federated Learning Using Trimmed-Clipping Aggregation."
    </span>
  </li>
  <li class="lp-news-item">
    <span class="lp-news-item__date">2024</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>Joined Oak Ridge National Laboratory</strong> as a researcher, working on
      distributed learning and resilient AI for large-scale scientific computing.
    </span>
  </li>
  <li class="lp-news-item">
    <span class="lp-news-item__date">2023</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>New publication</strong> — "Adaptive Learning from Peers for Distributed Actor-Critic
      Algorithms" at <em>International Symposium on Distributed Computing and Artificial Intelligence
      (DCAI) 2023</em>.
    </span>
  </li>
  <li class="lp-news-item">
    <span class="lp-news-item__date">2022</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>Applied Scientist Intern</strong> at <strong>Amazon Web Services (AWS)</strong>, Herndon, VA —
      developed reinforcement learning algorithms for battery scheduling and supply chain management.
    </span>
  </li>
  <li class="lp-news-item">
    <span class="lp-news-item__date">2021</span>
    <span class="lp-news-item__dot"></span>
    <span class="lp-news-item__text">
      <strong>Joined Vanderbilt University</strong> as a Ph.D. student in Electrical and Computer
      Engineering under <strong>Dr. Xenofon Koutsoukos</strong>.
    </span>
  </li>
</ul>

<hr class="lp-divider">

<!-- ═══════════════════════════════════════════
     TECH STACK
════════════════════════════════════════════ -->
<span class="lp-section-label">Tools &amp; Technologies</span>
<h2 class="lp-section-title">Tech Stack</h2>

<div class="lp-tech-grid">
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="">Python</span>
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matlab/matlab-original.svg" alt="">MATLAB</span>
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/latex/latex-original.svg" alt="">LaTeX</span>
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytorch/pytorch-original.svg" alt="">PyTorch</span>
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tensorflow/tensorflow-original.svg" alt="">TensorFlow</span>
  <span class="lp-tech-badge"><span class="tech-dot" style="background:#1976d2"></span>Federated Learning</span>
  <span class="lp-tech-badge"><span class="tech-dot" style="background:#1565c0"></span>Multi-Agent RL</span>
  <span class="lp-tech-badge"><span class="tech-dot" style="background:#008080"></span>Graph Neural Networks</span>
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" alt="">NumPy / Matplotlib</span>
  <span class="lp-tech-badge"><span class="tech-dot" style="background:#4527a0"></span>Byzantine Fault Tolerance</span>
  <span class="lp-tech-badge"><span class="tech-dot" style="background:#c0392b"></span>Cyber-Physical Security</span>
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="">Git</span>
  <span class="lp-tech-badge"><img class="tech-logo" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" alt="">Linux</span>
</div>

<hr class="lp-divider">

<!-- ═══════════════════════════════════════════
     COLLABORATIONS
════════════════════════════════════════════ -->
<span class="lp-section-label">Affiliations &amp; Partners</span>
<h2 class="lp-section-title">Collaborations</h2>

<div class="lp-collab-strip">
  <span class="lp-collab-badge"><i class="fas fa-university"></i> Vanderbilt University</span>
  <span class="lp-collab-badge"><i class="fas fa-atom"></i> Oak Ridge National Laboratory</span>
  <span class="lp-collab-badge"><i class="fas fa-cloud"></i> Amazon Web Services</span>
  <span class="lp-collab-badge"><i class="fas fa-graduation-cap"></i> IIT Kanpur</span>
  <span class="lp-collab-badge"><i class="fas fa-flask"></i> Missouri S&amp;T</span>
  <span class="lp-collab-badge"><i class="fas fa-shield-alt"></i> Resilient AI Research</span>
</div>

<hr class="lp-divider">

<!-- ═══════════════════════════════════════════
     CONTACT
════════════════════════════════════════════ -->
<span class="lp-section-label">Let's Connect</span>
<h2 class="lp-section-title">Contact</h2>

<p style="color:#475569; margin-bottom:1.1rem; text-align:left !important;">
  I welcome discussions on research collaborations in distributed learning, resilient AI,
  and federated systems. The best way to reach me is by email.
</p>

<div class="lp-hero__ctas">
  <a href="mailto:chandreyee.bhowmick@vanderbilt.edu" class="lp-btn lp-btn--primary">
    <i class="fas fa-envelope"></i> chandreyee.bhowmick@vanderbilt.edu
  </a>
  <a href="https://scholar.google.com/citations?user=QUmmn7kAAAAJ&hl=en" class="lp-btn lp-btn--outline">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a>
  <a href="https://orcid.org/0000-0002-2261-8288" class="lp-btn lp-btn--outline">
    <i class="ai ai-orcid"></i> ORCID
  </a>
  <a href="https://github.com/cbhowmic" class="lp-btn lp-btn--outline">
    <i class="fab fa-github"></i> GitHub
  </a>
</div>

</div><!-- /.lp-wrapper -->

<script>
(function() {
  function animateCounter(el) {
    var target  = parseInt(el.getAttribute('data-count'), 10);
    var suffix  = el.getAttribute('data-suffix') || '';
    var step    = Math.max(1, Math.ceil(target / 28));
    var current = 0;
    el.textContent = '0';
    var timer   = setInterval(function() {
      current = Math.min(current + step, target);
      el.textContent = current + (current >= target ? suffix : '');
      if (current >= target) clearInterval(timer);
    }, 38);
  }
  setTimeout(function() {
    var counters = document.querySelectorAll('.lp-stat-card__number[data-count]');
    counters.forEach(function(c) { animateCounter(c); });
  }, 300);
})();
</script>
