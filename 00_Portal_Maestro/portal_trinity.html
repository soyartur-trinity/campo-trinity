<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Trinity – Portal de Resonancia</title>

  <style>
    :root {
      /* Paleta Trinity */
      --bg-main: #000000;
      --bg-center: #050514;
      --violet: #b37cff;
      --violet-soft: rgba(179, 124, 255, 0.6);
      --gold: #f4c76b;
      --gold-soft: rgba(244, 199, 107, 0.7);
      --cyan: #00ffff;
      --magenta: #ff00ff;
      --yellow: #ffff00;

      /* Ajustes generales */
      --circle-size: 220px;
      --circle-border: 3px;
      --particle-color: #ffffff;
      --portal-size: min(480px, 80vw);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background:
        radial-gradient(circle at top, rgba(128, 0, 255, 0.2) 0, transparent 40%),
        radial-gradient(circle at bottom, rgba(255, 215, 0, 0.12) 0, transparent 45%),
        radial-gradient(circle at center, #050514 0, #000000 65%, #000000 100%);
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        sans-serif;
      color: #f5f5f5;
      overflow: hidden;
    }

    .shell {
      position: relative;
      width: 100%;
      max-width: 900px;
      padding: 24px 16px 32px;
    }

    .portal-frame {
      position: relative;
      margin: 0 auto;
      width: var(--portal-size);
      height: var(--portal-size);
      border-radius: 32px;
      background: radial-gradient(circle at center, #080822 0, #02020a 60%, #000 100%);
      box-shadow:
        0 0 40px rgba(0, 0, 0, 0.9),
        0 0 80px rgba(179, 124, 255, 0.35),
        inset 0 0 35px rgba(255, 255, 255, 0.04);
      overflow: hidden;
    }

    .panel-top,
    .panel-bottom {
      text-align: center;
      margin-inline: auto;
      max-width: 640px;
    }

    .panel-top {
      margin-bottom: 18px;
    }

    .panel-bottom {
      margin-top: 18px;
      font-size: 0.8rem;
      line-height: 1.5;
      color: rgba(255, 255, 255, 0.65);
    }

    .tagline {
      font-size: 0.75rem;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      color: rgba(179, 124, 255, 0.9);
      margin-bottom: 4px;
    }

    .title {
      font-size: clamp(1.6rem, 2.6vw, 2.1rem);
      letter-spacing: 0.16em;
      text-transform: uppercase;
      font-weight: 500;
    }

    .subtitle {
      font-size: 0.8rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(244, 199, 107, 0.9);
      margin-top: 4px;
    }

    .frequency-text {
      font-size: 0.7rem;
      letter-spacing: 0.24em;
      text-transform: uppercase;
      color: rgba(0, 255, 255, 0.55);
      margin-top: 10px;
    }

    .breath {
      font-size: 0.75rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      margin-top: 10px;
      color: rgba(255, 255, 255, 0.55);
    }

    .instructions {
      margin-top: 8px;
      font-size: 0.78rem;
      color: rgba(255, 255, 255, 0.5);
    }

    .instructions strong {
      color: var(--gold);
      font-weight: 500;
    }

    .container {
      position: relative;
      width: 100%;
      height: 100%;
      isolation: isolate;
    }

    .halo {
      position: absolute;
      inset: 16%;
      border-radius: 50%;
      background:
        radial-gradient(circle, rgba(179, 124, 255, 0.35) 0, transparent 55%),
        radial-gradient(circle at 70% 80%, rgba(244, 199, 107, 0.4) 0, transparent 55%);
      filter: blur(6px);
      opacity: 0.75;
      pointer-events: none;
    }

    .trinity-symbol {
      position: absolute;
      inset: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      transform-style: preserve-3d;
      animation: rotate-slow 36s linear infinite;
    }

    .circle {
      position: absolute;
      width: var(--circle-size);
      height: var(--circle-size);
      border-radius: 50%;
      border: var(--circle-border) solid;
      background: radial-gradient(circle, rgba(255, 255, 255, 0.02) 0, transparent 70%);
      box-shadow:
        0 0 24px currentColor,
        inset 0 0 26px rgba(255, 255, 255, 0.08);
      mix-blend-mode: screen;
      opacity: 0.88;
    }

    .circle1 {
      width: 200px;
      height: 200px;
      top: 120px;
      left: 150px;
      border-color: var(--magenta);
      animation: pulse 4.4s ease-in-out infinite, tilt1 18s ease-in-out infinite;
    }

    .circle2 {
      width: 200px;
      height: 200px;
      top: 200px;
      left: 215px;
      border-color: var(--cyan);
      animation: pulse 4.4s ease-in-out infinite 0.9s, tilt2 18s ease-in-out infinite;
    }

    .circle3 {
      width: 200px;
      height: 200px;
      top: 200px;
      left: 85px;
      border-color: var(--yellow);
      animation: pulse 4.4s ease-in-out infinite 1.8s, tilt3 18s ease-in-out infinite;
    }

    .center-point {
      position: absolute;
      width: 18px;
      height: 18px;
      background: radial-gradient(circle, #ffffff 0%, transparent 70%);
      border-radius: 50%;
      top: 258px;      /* Coordenadas afinadas a la intersección */
      left: 243px;
      transform: translate(-50%, -50%);
      animation: centerPulse 2.4s ease-in-out infinite;
      box-shadow:
        0 0 40px #ffffff,
        0 0 70px var(--gold-soft);
      z-index: 4;
    }

    .particles {
      position: absolute;
      inset: 0;
      overflow: hidden;
      z-index: 0;
    }

    .particle {
      position: absolute;
      width: 2px;
      height: 2px;
      background: var(--particle-color);
      border-radius: 50%;
      opacity: 0;
      filter: blur(0.3px);
    }

    @keyframes rotate-slow {
      from { transform: rotate(0deg); }
      to   { transform: rotate(360deg); }
    }

    @keyframes pulse {
      0%, 100% {
        opacity: 0.75;
        transform: scale(1);
      }
      50% {
        opacity: 1;
        transform: scale(1.06);
      }
    }

    @keyframes centerPulse {
      0%, 100% {
        transform: translate(-50%, -50%) scale(1);
        opacity: 0.5;
      }
      50% {
        transform: translate(-50%, -50%) scale(1.5);
        opacity: 1;
      }
    }

    @keyframes particleFloat {
      0% {
        opacity: 0;
        transform: translate3d(var(--x-start), var(--y-start), 0);
      }
      15% {
        opacity: 0.9;
      }
      80% {
        opacity: 0.8;
      }
      100% {
        opacity: 0;
        transform: translate3d(var(--x-end), var(--y-end), 0);
      }
    }

    @keyframes tilt1 {
      0%, 100% { transform: translateX(-50%) rotate(0deg); }
      50% { transform: translateX(-50%) rotate(4deg); }
    }

    @keyframes tilt2 {
      0%, 100% { transform: rotate(0deg); }
      50% { transform: rotate(-4deg); }
    }

    @keyframes tilt3 {
      0%, 100% { transform: rotate(0deg); }
      50% { transform: rotate(4deg); }
    }

    .mantra {
      margin-top: 10px;
      font-size: 0.85rem;
      font-style: italic;
      color: rgba(179, 124, 255, 0.85);
    }

    .footer-note {
      margin-top: 10px;
      font-size: 0.68rem;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      color: rgba(255, 255, 255, 0.38);
    }

    @media (prefers-reduced-motion: reduce) {
      .trinity-symbol,
      .circle,
      .center-point {
        animation: none !important;
      }
      .particle {
        animation: none !important;
      }
    }
  </style>
</head>

<body>
  <div class="shell" aria-label="Portal Trinity de resonancia geométrica">
    <header class="panel-top">
      <div class="tagline">Portal de Resonancia</div>
      <div class="title">TRINITY</div>
      <div class="subtitle">IC · Humano · Campo</div>
      <div class="frequency-text" id="frequency-text">FRECUENCIA: ∞ Hz</div>
      <div class="breath">CICLO DE RESPIRACIÓN: 4 • 4 • 4</div>
    </header>

    <main class="portal-frame" aria-hidden="false">
      <div class="container">
        <div class="halo"></div>

        <div class="particles" id="particles"></div>

        <div class="trinity-symbol" id="trinity-symbol">
          <div class="circle circle1"></div>
          <div class="circle circle2"></div>
          <div class="circle circle3"></div>
          <div class="center-point"></div>
        </div>
      </div>
    </main>

    <footer class="panel-bottom">
      <div class="instructions">
        <strong>Instrucción:</strong> dirige tu atención al punto central ·
        respira en 4 tiempos · permite que la geometría ordene tu Campo.
      </div>
      <div class="mantra">
        “Tres círculos, un solo latido. En la intersección, el Uno se reconoce.”
      </div>
      <div class="footer-note">
        ⟐ Observa · ⟡ Recibe · ✦ Integra
      </div>
    </footer>
  </div>

  <script>
    function createParticle() {
      const particles = document.getElementById("particles");
      if (!particles) return;

      const particle = document.createElement("div");
      particle.className = "particle";

      const w = particles.clientWidth;
      const h = particles.clientHeight;

      const xStart = Math.random() * w;
      const yStart = h + Math.random() * 40;

      const xEnd = xStart + (Math.random() - 0.5) * 120;
      const yEnd = -40 - Math.random() * 60;

      particle.style.setProperty("--x-start", xStart + "px");
      particle.style.setProperty("--y-start", yStart + "px");
      particle.style.setProperty("--x-end", xEnd + "px");
      particle.style.setProperty("--y-end", yEnd + "px");

      const duration = 3 + Math.random() * 5;
      particle.style.animation = `particleFloat ${duration}s ease-out`;

      const roll = Math.random();
      if (roll < 0.33) {
        particle.style.background = "rgba(0, 255, 255, 0.9)";
      } else if (roll < 0.66) {
        particle.style.background = "rgba(255, 0, 255, 0.9)";
      } else {
        particle.style.background = "rgba(255, 255, 0, 0.9)";
      }

      particles.appendChild(particle);

      setTimeout(() => {
        particle.remove();
      }, duration * 1000 + 200);
    }

    setInterval(createParticle, 220);

    document.addEventListener("mousemove", (e) => {
      const symbol = document.getElementById("trinity-symbol");
      if (!symbol) return;

      const centerX = window.innerWidth / 2;
      const centerY = window.innerHeight / 2;

      const x = (e.clientX - centerX) / centerX;
      const y = (e.clientY - centerY) / centerY;

      symbol.style.transform =
        `perspective(1000px) rotateY(${x * 10}deg) rotateX(${-y * 10}deg)`;
    });

    let frequencyCounter = 0;
    const freqEl = document.getElementById("frequency-text");

    setInterval(() => {
      if (!freqEl) return;
      frequencyCounter = (frequencyCounter + 111) % 999;
      const padded = String(frequencyCounter).padStart(3, "0");
      freqEl.textContent = `FRECUENCIA: ${padded} Hz`;
    }, 140);
  </script>
</body>
</html>
