---
title: "Reality Check: Welcome to Baja — It’s Not a Fantasyland Anymore"
description: "Baja California Sur is still beautiful, but recent cartel violence shows it's not immune to Mexico's national security struggles. Smart residents and visitors must stay aware — not afraid."
permalink: /2025/reality-check-baja-violence
date: 2025-04-26T07:00:00Z
classes: wide
categories:
  - Security
  - Expat Life
tags:
  - Baja California Sur
  - Cartels
  - Safety
  - Mexico
excerpt: "Baja's calm image shattered in April 2025. Staying safe today requires awareness, not denial — and empathy for the locals who live these realities every day."
header:
  image: /assets/images/2025/04/reality-check-baja-violence-2048px.jpg
  overlay_image: /assets/images/2025/04/reality-check-baja-violence-2048px.jpg
  overlay_filter: rgba(0, 0, 0, 0.2)
  teaser: /assets/images/2025/04/reality-check-baja-violence-575px.jpg
  og_image: /assets/images/2025/04/reality-check-baja-violence-2048px.jpg
  caption: "[Original](https://bajaexpat.com/)"
toc: true
published: true
---

You hear it again and again:  
>"Mexico is dangerous, just like Chicago."

Or the opposite:  
> "Relax, it's all overblown. Baja is perfectly safe!"

Both extremes are wrong — dangerously wrong.  

Baja California Sur, once known for its relative tranquility, has entered a new, uneasy chapter. April 2025 shattered old assumptions.  

If you’re living here — or thinking about it — you owe it to yourself and the people around you to understand what’s really happening.  

It's not about living in fear, but about **respecting reality**.

## No, This Isn’t Chicago — It’s Cartel Warfare

Baja California Sur isn’t just facing “normal crime.” It's facing an organized criminal power struggle — one that looks very different from the gang violence familiar to many U.S. cities.  

In the United States, most urban violence is interpersonal: personal disputes, often chaotic and unplanned.  
But in Mexico — and now increasingly in Baja — much of the violence is **strategic**. Cartels use terror tactics to control territories, intimidate authorities, and dominate civilian life.

When people say "it's just as bad in Chicago," they miss the point. Baja’s violence isn’t random. It’s calculated.

<figure>
  <canvas id="homicideComparisonChart" style="max-height:400px;"></canvas>
  <figcaption>Figure: Homicide Comparison Across Baja California Regions (2024–Early 2025)</figcaption>
</figure>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const ctx = document.getElementById('homicideComparisonChart').getContext('2d');
new Chart(ctx, {
  type: 'bar',
  data: {
    labels: ['Tijuana', 'Ensenada', 'Baja California Sur'],
    datasets: [
      {
        label: 'Total Homicides 2024',
        data: [1807, 92, 56],
        backgroundColor: '#5DB1B4'
      },
      {
        label: 'Homicides Jan–Apr 2025',
        data: [372, 0, 0], // Only Tijuana has early 2025 data
        backgroundColor: '#79c2c5'
      }
    ]
  },
  options: {
    responsive: true,
    scales: {
      y: {
        beginAtZero: true,
        title: {
          display: true,
          text: 'Number of Homicides'
        },
        grid: {
          color: '#ccc'
        },
        ticks: {
          color: '#333'
        }
      },
      x: {
        grid: {
          color: '#ccc'
        },
        ticks: {
          color: '#333'
        }
      }
    },
    plugins: {
      legend: {
        labels: {
          color: '#333'
        }
      }
    }
  }
});
</script>

| Region | Total Homicides (2024) | Homicides Jan–Apr 2025 | Rate per 100k |
|:------|:-----------------------|:----------------------|:-------------|
| **Tijuana** | 1,807 | 372 | 86.6 |
| **Ensenada** | 92 (by Sept 2024) | — | — |
| **Baja California Sur (entire state)** | 56 | — | — |

> **Sources:** [Zeta Tijuana](https://zetatijuana.com/), [INEGI ENVIPE 2024](https://www.inegi.org.mx/contenidos/programas/envipe/2024/doc/envipe2024_bc.pdf)

**Key points:**
- **Tijuana’s** homicide rate in 2024 (86.6 per 100,000) was among the highest in the world.
- **Baja California Sur** maintained much lower violence rates — until April 2025, when the calm cracked open.

In Mexico, violence is **a message**.  

Each shooting, each narcomanta ("narco-banner") left on a bridge or schoolyard is a public warning:  
> *"We control this place. Not the police. Not the government. Not you."*

This is what residents of La Paz, Los Cabos, and parts of Ensenada now confront — not just isolated incidents, but strategic shows of force.  

For foreigners choosing to live or travel here, **understanding this shift isn't optional anymore**.

## April 2025: When Calm Cracked in Baja Sur

For years, Baja California Sur was seen as Mexico’s exception — the calm peninsula, far removed from the bloody cartel wars plaguing the north and interior.  

But that changed dramatically in April 2025.  

In the span of just a few days, La Paz and Los Cabos experienced a cascade of violence that left even seasoned observers stunned:  
- **Shootouts on public streets** in the middle of the day.  
- **Bus burnings** in Cabo San Lucas, captured on live video.  
- **Assassinations** of high-ranking state law enforcement officials.  
- **Narcomantas** — the signature cartel banners — appearing across pedestrian bridges, highways, and even outside schools.

This wasn’t random violence.  

It was a coordinated campaign by organized crime groups, announcing their presence, flexing their power, and warning local authorities not to interfere.

<figure>
  <style>
    .timeline {
      position: relative;
      padding: 2rem 0;
      margin: 2rem 0;
    }

    .timeline::before {
      content: '';
      position: absolute;
      left: 2rem;
      width: 4px;
      height: 90%;
      background: #5DB1B4;
    }

    .timeline-event {
      position: relative;
      margin-left: 3rem;
      margin-bottom: 2rem;
      padding-left: 1.5rem;
      border-left: 3px solid transparent;
      background: #fff !important;
      padding: 1rem;
      border-radius: 12px;
    }

    .timeline-event::before {
      content: '';
      position: absolute;
      top: 0.2rem;
      left: -1.75rem;
      width: 1rem;
      height: 1rem;
      background: #5DB1B4;
      border-radius: 50%;
      border: 2px solid white;
    }

    .timeline-event h4 {
      margin: 0;
      font-size: 1rem;
      font-weight: 700;
      color: #000;
    }

    .timeline-event p {
      margin: 0.25rem 0 0;
      font-size: 0.9rem;
      color: #333;
    }

    @media screen and (max-width: 600px) {
      .timeline::before {
        left: 0.5rem;
      }
      .timeline-event {
        margin-left: 2rem;
        padding-left: 1rem;
      }
    }
  </style>

<div class="timeline">
  <div class="timeline-event">
    <h4>April 16</h4>
    <p><strong>High-Speed Chase & Shootout</strong> — A vehicle pursuit and gunfire erupted near the La Paz malecón, alarming residents and visitors alike. <a href="#sources">[6]</a></p>
  </div>

  <div class="timeline-event">
    <h4>April 18</h4>
    <p><strong>First Narcomantas Appear</strong> — Cartel banners warning of renewed violence were hung across major bridges in La Paz. <a href="#sources">[4]</a></p>
  </div>

  <div class="timeline-event">
    <h4>April 22</h4>
    <p><strong>Senior Narcotics Commander Assassinated</strong> — PGJE officer Ulises Cota Montaño was ambushed and killed outside his home. <a href="#sources">[1]</a></p>
  </div>

  <div class="timeline-event">
    <h4>April 24</h4>
    <p><strong>Coordinated Bus Burnings</strong> — Public transport buses were set ablaze in both La Paz and Cabo San Lucas, paralyzing city transit. <a href="#sources">[2]</a></p>
  </div>

  <div class="timeline-event">
    <h4>April 24–25</h4>
    <p><strong>Gun Battles Across Cabo</strong> — Shootouts erupted in several Cabo neighborhoods, triggering a U.S. Consulate security alert. <a href="#sources">[1]</a></p>
  </div>

  <div class="timeline-event">
    <h4>April 25</h4>
    <p><strong>Cartel Leader Arrested</strong> — Authorities captured "Marquitos," a key Los Mayos figure linked to the violence in La Paz. <a href="#sources">[13]</a></p>
  </div>
</div>

<figcaption>Figure: Timeline of Major Violent Events in Baja California Sur, April 2025</figcaption>
</figure>

### Why This Matters

This wasn’t just another round of isolated cartel killings.  

It was a **clear escalation** — a direct confrontation between organized crime groups and the Mexican state itself.  

Narcomantas explicitly threatened public officials. 

Drone surveillance was reportedly used in the assassination of the PGJE commander.  

Clandestine graves revealed a brutal history of disappearances that predates this latest wave.  

In the past, Baja California Sur was largely spared from the worst of Mexico’s organized crime wars. Now, the internal conflict between **Los Mayos** and **Los Chapitos** — two powerful Sinaloa Cartel factions — has spilled onto its streets.  

State officials, including Governor Víctor Castro Cosío, publicly confirmed what many had feared:  
> "The violence is tied to a reconfiguration of criminal groups, fighting for control over Baja California Sur." [3](#sources)

For expats and visitors, this isn't cause for panic — but it is a stark **reminder**:  

Baja Sur is no longer immune.  

It’s part of the same national struggle playing out across Mexico.

Understanding this reality isn't just about personal safety, it’s about respecting the lived experiences of the local people — people who now find themselves caught in the crossfire of a fight they didn’t choose.

## Stop Denying It — Have Some Empathy

Whenever violence spikes in Mexico, a familiar chorus rises in expat circles:  
> "It’s not that bad."   
> "It’s worse in Chicago."   
> "It doesn’t affect me."   

This attitude isn’t just naive. It’s disrespectful.

Yes, it's true that crime exists everywhere.  

Yes, it's true that most cartel violence is targeted, not random.  

But minimizing what’s happening here — especially after the April 2025 events — shows a profound lack of empathy for the local people who are living through it firsthand.

When public buses are burned to the frame, it’s not tourists who suffer most.  **It’s the local workers who can’t get to their jobs.**

When narcomantas are strung up across schools and overpasses, it’s not foreigners who feel the daily chill of fear.  **It’s Mexican parents, wondering if it’s still safe to send their kids out the door.**

When shootouts erupt on residential streets, it’s not short-term visitors who bear the emotional weight.  **It’s the families who have lived here for generations — who don't have the option to just "go home" if things get worse.**

<figure>
  <canvas id="cartelMapChart" style="max-height:500px;"></canvas>
  <figcaption>Figure: Major Cartel Influence Across Baja California, 2025</figcaption>
</figure>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const ctx2 = document.getElementById('cartelMapChart').getContext('2d');
  new Chart(ctx2, {
    type: 'bar',
    data: {
      labels: ['Tijuana', 'Ensenada', 'La Paz', 'Los Cabos'],
      datasets: [
        {
          label: 'CJNG',
          data: [90, 75, 20, 15],
          backgroundColor: '#5DB1B4'
        },
        {
          label: 'Los Chapitos (Sinaloa Faction)',
          data: [60, 50, 60, 65],
          backgroundColor: '#79c2c5'
        },
        {
          label: 'Los Mayos (Sinaloa Faction)',
          data: [40, 35, 50, 45],
          backgroundColor: '#b7e3e5'
        },
        {
          label: 'CAF (Arellano Félix Remnants)',
          data: [20, 15, 0, 0],
          backgroundColor: '#d4f1f2'
        }
      ]
    },
    options: {
      indexAxis: 'y',
      responsive: true,
      scales: {
        x: {
          beginAtZero: true,
          max: 100,
          grid: { color: '#ccc' },
          ticks: { color: '#333' },
          title: {
            display: true,
            text: 'Influence Strength (0–100)',
            color: '#333'
          }
        },
        y: {
          grid: { color: '#ccc' },
          ticks: { color: '#333' }
        }
      },
      plugins: {
        legend: {
          labels: { color: '#333' }
        }
      }
    }
  });
});
</script>

According to INEGI’s 2024 ENVIPE survey, insecurity in Baja California cost households an estimated **8.7 billion pesos** in 2023 alone. [42](#sources) That’s billions spent not on vacations or education — but on private security, reinforced doors, altered routines, and lost income.

In fact, over **one-third** of the total cost of crime was borne directly by families trying to protect themselves.

### This Isn’t About Living in Fear

No one is saying you need to barricade yourself inside. No one is saying you should stop enjoying the beaches, the sunsets, the vibrant culture that makes Baja so special.

But living responsibly here means recognizing the truth:  
- Security conditions are shifting.  
- Locals are carrying a heavy burden.  
- You are not immune just because you're a foreigner.

Awareness isn't weakness.  
It's respect.  

And empathy isn’t pity.  
It’s solidarity.

**If you truly love Baja, show it.**  

Stay aware.  
Stay humble.  
Support local communities.  

And never, ever dismiss the reality they are facing just because you’re lucky enough to leave when you want.

## New Criminal Battleground: Why Baja Matters Now

For a long time, many foreigners — and even some locals — believed that Baja California Sur was somehow "off-limits" to cartel violence.  

A sleepy, beautiful, tourism-focused peninsula.  

A natural paradise where the worst parts of Mexico’s cartel wars simply wouldn’t reach.

That was never really true.  

And today, it’s unmistakably false.

The April 2025 events aren’t an isolated flare-up.  

They are the symptom of a much bigger shift: **Baja California Sur has become part of a national criminal reorganization.**

According to state officials and multiple media investigations:  
- **Los Mayos** and **Los Chapitos** — two warring factions of the fractured Sinaloa Cartel — are now actively fighting for dominance over Baja Sur. [3](#sources)
- The arrest of "Marquitos" and the violent reemergence of "El Babay" show that criminal structures here are **deep, organized, and strategic**. [13](#sources) 
- Narcomantas and drone-surveilled assassinations aren’t “random violence.” They’re signs that Baja Sur is now **a contested prize** in a wider war.

<figure>
  <canvas id="cartelBattlegroundsChart" style="max-height:500px;"></canvas>
  <figcaption>Figure: Key Areas of Organized Crime Contestation in Baja California, 2025</figcaption>
</figure>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const ctx = document.getElementById('cartelBattlegroundsChart').getContext('2d');
  new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['Tijuana', 'Ensenada', 'La Paz', 'Los Cabos'],
      datasets: [{
        label: 'Organized Crime Activity Level',
        data: [95, 75, 65, 70],
        backgroundColor: '#5DB1B4'
      }]
    },
    options: {
      responsive: true,
      scales: {
        y: {
          beginAtZero: true,
          max: 100,
          title: {
            display: true,
            text: 'Activity Intensity (0–100)'
          },
          grid: {
            color: '#ccc'
          },
          ticks: {
            color: '#333'
          }
        },
        x: {
          grid: {
            color: '#ccc'
          },
          ticks: {
            color: '#333'
          }
        }
      },
      plugins: {
        legend: {
          display: false
        }
      }
    }
  });
});
</script>

<figure>
<div id="bajaCartelMap" style="height: 500px; width: 100%; margin: 2rem 0;"></div>

<figcaption>Figure: Major Criminal Organizations Active in Baja California and Baja California Sur (April 2025)</figcaption>

<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"/>

<script>
const map = L.map('bajaCartelMap').setView([27.5, -113.5], 6);

L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
  attribution: '&copy; OpenStreetMap contributors'
}).addTo(map);

// Tijuana
L.marker([32.5149, -117.0382]).addTo(map)
  .bindPopup('<b>Tijuana</b><br>CJNG, Los Mayos, Los Chapitos, CAF remnants');

// Ensenada
L.marker([31.8667, -116.6000]).addTo(map)
  .bindPopup('<b>Ensenada</b><br>Sinaloa (split factions), CJNG presence');

// La Paz
L.marker([24.1426, -110.3128]).addTo(map)
  .bindPopup('<b>La Paz</b><br>Los Mayos vs. Los Chapitos factional war');

// Los Cabos (Cabo San Lucas)
L.marker([22.8905, -109.9167]).addTo(map)
  .bindPopup('<b>Los Cabos</b><br>Los Mayos vs. Los Chapitos, emerging splinters');

// Guerrero Negro
L.marker([27.9764, -114.0617]).addTo(map)
  .bindPopup('<b>Guerrero Negro</b><br>Narcomanta activity, cartel influence zone');

// Santa Rosalía
L.marker([27.3405, -112.2736]).addTo(map)
  .bindPopup('<b>Santa Rosalía</b><br>Narcomanta threats, strategic smuggling route');
</script>
</figure>

### Why Baja?

Several factors explain why organized crime is now fighting harder for Baja Sur:

- **Tourism money** — Hotels, clubs, restaurants, transportation — all cash businesses that can be taxed through extortion, money laundering, and control.
- **Ports and highways** — Baja offers critical logistics points for drug and weapons movement, both domestically and internationally.
- **Geography** — With fewer large cities and lots of rural stretches, Baja provides ideal hiding places, smuggling routes, and less resistance from overburdened local law enforcement.
- **Perception** — Controlling "peaceful" Baja sends a powerful signal to rivals and the government alike: nowhere is truly beyond reach anymore.

And cartels aren’t just interested in moving product.  

They’re building parallel power structures:  
- **Security forces** (sicarios)  
- **Finance arms** (money laundering networks)  
- **Social control** (terror tactics through visible acts of brutality)

In short:  
- They don’t just want to operate in Baja.  
- They want to **own it**.

### The Big Shift: From "Safe Haven" to Strategic Territory

The mistake isn’t believing Baja was once calmer — it genuinely was. The mistake is believing that calm was permanent.

Today, Baja Sur is no longer just a tourist playground. It’s part of a much larger map — a new criminal frontier in a national conflict that shows no signs of slowing down.

- Ignoring that shift won’t protect you.  
- Pretending it’s "just like the U.S." won’t change it.
- Understanding it — and respecting it — is the only responsible way forward.

## Stay Smart, Stay Safe: Realistic Tips for Living Here Now

No, you don’t need to panic.  

No, you don’t need to sell your house, pack your bags, or cancel your trip.

But you **do** need to adjust your mindset.

If you’re living in, working in, or visiting Baja California Sur today, the best thing you can do is stay calm — and stay situationally aware.

Here’s what responsible, respectful behavior looks like right now:

<figure>
<style>
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.card {
  background: #fff;
  border: 2px solid #5DB1B4;
  border-radius: 10px;
  padding: 1rem;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

.card h4 {
  margin-top: 0;
  color: #5DB1B4;
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}

.card p {
  font-size: 0.9rem;
  color: #333;
}
</style>

<div class="card-grid">

<div class="card">
<h4>1. Accept the Reality</h4>
<p>Violence is up. Organized crime activity is real. Acknowledging reality helps you make smarter, safer choices.</p>
</div>

<div class="card">
<h4>2. Respect Local Fear</h4>
<p>If locals seem cautious, listen. Don’t dismiss their concerns by comparing Baja to U.S. cities — this is about Baja now.</p>
</div>

<div class="card">
<h4>3. Avoid Large Gatherings</h4>
<p>Stay clear of protest sites, cartel-linked nightclubs, sketchy bars, and late-night gas stations, especially alone.</p>
</div>

<div class="card">
<h4>4. Mind Your Vehicle</h4>
<p>Keep your car clean. No loose weapons, drugs, or large sums of cash. Be polite at checkpoints and carry ID copies.</p>
</div>

<div class="card">
<h4>5. Stay Informed Locally</h4>
<p>Use real local news like <em>Zeta Tijuana</em> ([15](#sources)) and <em>El Sudcaliforniano</em> ([5](#sources)) — not Facebook rumors.</p>
</div>

<div class="card">
<h4>6. Support Local Communities</h4>
<p>Shop local, support small businesses, and strengthen Baja’s real economy over the criminal one.</p>
</div>

<div class="card">
<h4>7. Remember: You Are a Guest</h4>
<p>Mexico isn’t yours to fix. Stay humble, stay respectful, and stay grateful for the chance to live here during challenging times.</p>
</div>

</div>

<figcaption>Figure: Practical Safety and Respect Tips for Life in Baja California Sur, 2025</figcaption>
</figure>

## Stay Aware, Stay Grateful

Baja California Sur is still one of the most beautiful, welcoming, and vibrant places on Earth.  

That hasn’t changed.

But pretending that violence and organized crime aren’t real problems doesn’t protect this place — it cheapens it.  

It disrespects the people who live here.  

It risks turning hope into complacency.

You don’t need to live in fear.  You *do* need to live with respect.
- Stay aware of your surroundings.  
- Stay connected to your community.  
- Stay humble about the risks you don't always see.
- And most importantly: stay grateful.  

Grateful for the beauty that endures, even in difficult times.  

Grateful for the resilience of the people who call Baja home — and who face challenges most visitors can barely imagine.

True love for a place means seeing it clearly. The good and the bad. The paradise and the problems.

It means standing with it, not just when it's easy, but when it’s hard.

That’s the real spirit of Baja.

## Sources
<a name="sources"></a>

| # | Source |
|---|-------|
| [1] | [Latinus — U.S. Consulate Issues Alert for Violence in Baja California Sur](https://latinus.us/mexico/2025/4/25/hay-una-situacion-de-manera-emergente-en-baja-california-sur-eu-emite-alerta-por-violencia-en-los-cabos-140588.html) |
| [2] | [YouTube — Bus Burning Incidents in Los Cabos, Baja California Sur](https://www.youtube.com/watch?v=dFfy1qEQPgg) |
| [3] | [Zeta Tijuana — Cartel Reorganization and Killings in BCS](https://zetatijuana.com/2025/04/narco-reacomoda-fuerzas-en-bcs-cuatro-ejecuciones-en-24-horas/) |
| [4] | [Peninsular Digital — Narcomantas Signal Return of Violence](https://peninsulardigital.com/bcs-2/) |
| [5] | [El Sudcaliforniano — Local News Coverage Baja California Sur](https://oem.com.mx/elsudcaliforniano/) |
| [6] | [El Universal — La Paz Boardwalk Shootout Details](https://www.eluniversal.com.mx/estados/persecucion-y-balacera-en-la-paz-baja-california-sur-deja-dos-heridos-desata-fuerte-movilizacion-policiaca/) |
| [7] | [Milenio — Armed Attack on Civilians in La Paz](https://www.milenio.com/estados/dos-civiles-sufren-ataque-armado-en-la-paz-baja-california-sur) |
| [8] | [BCS Noticias — Discovery of Clandestine Graves Near La Paz](https://www.bcsnoticias.mx/lapaz/) |
| [9] | [Tribuna de México — Assassination of PGJE Narcotics Chief](https://tribunademexico.com/ataque-armado-jefe-narcoticos/) |
| [10] | [Tribuna de México — Investigations into Narcomantas](https://tribunademexico.com/investigan-narcomantas-encontradas-bcs/) |
| [13] | [La Jornada — Arrest of "Marquitos" Linked to PGJE Murder](https://www.jornada.com.mx/noticia/2025/04/25/politica/detienen-en-bcs-a-presuntos-implicados-en-asesinato-de-agente-ministerial) |
| [15] | [Zeta Tijuana — Organized Crime and Violence Tracking](https://zetatijuana.com/) |
| [42] | [INEGI — 2024 ENVIPE Report on Victimization and Public Security](https://www.inegi.org.mx/contenidos/programas/envipe/2024/doc/envipe2024_bc.pdf) |

<!-- 
## AudioTranscript

Someone asked recently if the violence in Baja California Sur is "really that bad." The answer is simple: it's not about living in fear, but it's definitely about living with awareness.

In April 2025, Baja Sur saw a serious escalation. There were public shootouts in La Paz near the tourist boardwalk. Narcomantas — those public cartel banners — started appearing again. A senior state narcotics commander, Ulises Cota Montaño, was ambushed and killed outside his home.

Then came the bus burnings — coordinated attacks on public transportation in La Paz and Cabo San Lucas — followed by gun battles that led to a U.S. Consulate security alert.

Authorities arrested a key cartel figure, "Marquitos," tied to the murder of the commander. But the real story is bigger: Baja California Sur is no longer just a peaceful tourist destination. It's now a frontline in the ongoing cartel wars, with Los Mayos and Los Chapitos factions fighting for control.

Too many foreigners make two mistakes. Some panic and assume they’re automatically targets. They're not. Others dismiss the violence, saying, "It’s worse in Los Angeles." That’s disrespectful. It ignores what locals are living through — and it ignores the real shift happening here.

Staying safe doesn't mean being paranoid. It means being smart. Avoid large crowds, stay out of sketchy areas late at night, keep your vehicle clean and your documents handy, and pay attention to local Spanish-language news — not just Facebook rumors.

Most importantly, have empathy. Remember that when buses burn, when shootings happen, it’s local families — not tourists — who carry the biggest burden. People still have to get to work, take their kids to school, and try to live normal lives under extraordinary stress.

Baja is still beautiful. It’s still welcoming. But if you truly love this place, you owe it the respect of seeing it clearly. Acknowledge the problems. Stand with the people who call it home. Stay aware. Stay humble. And stay grateful.

Because real love for Baja isn’t just about enjoying the good days. It’s about standing with it through the hard ones, too.

-->