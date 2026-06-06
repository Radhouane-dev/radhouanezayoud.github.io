<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Radhouane Zayoud | Chef de Projets Photovoltaïques | Solar PV Engineer</title>

<!-- SEO Meta Tags -->
<meta name="description" content="Radhouane Zayoud - Chef de Projets Photovoltaïques avec plus de 4 ans d'expérience. Spécialiste en développement, conception et gestion de projets solaires PV. Disponible pour TotalEnergies, EDF Renouvelables, ENGIE Green.">
<meta name="keywords" content="Radhouane Zayoud, Chef de Projets Photovoltaïques, Solar Project Manager, Solar PV Engineer, Énergies Renouvelables, PVSyst, AutoCAD, Dimensionnement HT/BT, Raccordement Électrique, Ingénieur Solaire, Renewable Energy">
<meta name="author" content="Radhouane Zayoud">
<meta name="robots" content="index, follow">
<meta name="language" content="French">

<!-- Open Graph -->
<meta property="og:title" content="Radhouane Zayoud | Chef de Projets Photovoltaïques">
<meta property="og:description" content="Ingénieur en Électrique Automatique avec 4+ ans d'expérience en gestion de projets photovoltaïques. Expert PVSyst, AutoCAD, HT/BT.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://radhouanezayoud.github.io">
<meta property="og:image" content="https://radhouanezayoud.github.io/og-image.jpg">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Radhouane Zayoud | Solar PV Project Manager">
<meta name="twitter:description" content="4+ years experience in photovoltaic project development, design & management.">

<!-- Canonical -->
<link rel="canonical" href="https://radhouanezayoud.github.io">

<!-- Structured Data -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Radhouane Zayoud",
  "jobTitle": "Chef de Projets Photovoltaïques",
  "description": "Ingénieur expert en développement et gestion de projets solaires photovoltaïques",
  "url": "https://radhouanezayoud.github.io",
  "sameAs": ["https://www.linkedin.com/in/radhouanezayoud"],
  "knowsAbout": ["Photovoltaïque", "PVSyst", "AutoCAD", "HT/BT", "Énergies Renouvelables", "Solar PV"],
  "alumniOf": {"@type": "Organization", "name": "École d'Ingénieur - Électrique Automatique"}
}
</script>

<!-- Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&display=swap" rel="stylesheet">

<style>
:root {
  --navy: #0a0e1a;
  --navy-mid: #0d1528;
  --navy-card: #111827;
  --blue-primary: #1a56db;
  --blue-light: #3b82f6;
  --blue-glow: #60a5fa;
  --green: #10b981;
  --green-light: #34d399;
  --green-glow: #6ee7b7;
  --white: #ffffff;
  --grey-100: #f1f5f9;
  --grey-300: #94a3b8;
  --grey-400: #64748b;
  --accent-gold: #f59e0b;
  --border: rgba(255,255,255,0.07);
  --border-bright: rgba(59,130,246,0.3);
  --font-display: 'Syne', sans-serif;
  --font-body: 'DM Sans', sans-serif;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  font-family: var(--font-body);
  background: var(--navy);
  color: var(--white);
  overflow-x: hidden;
  font-size: 16px;
  line-height: 1.6;
}

/* ===== SCROLLBAR ===== */
::-webkit-scrollbar { width: 4px; }
::-webkit-scrollbar-track { background: var(--navy); }
::-webkit-scrollbar-thumb { background: var(--blue-primary); border-radius: 2px; }

/* ===== NOISE TEXTURE OVERLAY ===== */
body::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.03'/%3E%3C/svg%3E");
  pointer-events: none;
  z-index: 0;
  opacity: 0.4;
}

/* ===== NAV ===== */
nav {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 100;
  padding: 1.25rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: rgba(10,14,26,0.85);
  backdrop-filter: blur(20px);
  border-bottom: 1px solid var(--border);
  transition: all 0.3s ease;
}

.nav-logo {
  font-family: var(--font-display);
  font-size: 1.1rem;
  font-weight: 800;
  letter-spacing: -0.02em;
  color: var(--white);
  text-decoration: none;
}

.nav-logo span { color: var(--green); }

.nav-links {
  display: flex;
  gap: 2rem;
  list-style: none;
}

.nav-links a {
  font-size: 0.85rem;
  font-weight: 500;
  color: var(--grey-300);
  text-decoration: none;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  transition: color 0.2s;
}

.nav-links a:hover { color: var(--green-light); }

.nav-cta {
  background: var(--green);
  color: var(--navy) !important;
  padding: 0.5rem 1.25rem;
  border-radius: 6px;
  font-weight: 700 !important;
  transition: background 0.2s, transform 0.2s !important;
}

.nav-cta:hover { background: var(--green-light) !important; transform: translateY(-1px); }

.hamburger {
  display: none;
  flex-direction: column;
  gap: 5px;
  cursor: pointer;
  background: none;
  border: none;
  padding: 4px;
}

.hamburger span {
  display: block;
  width: 24px;
  height: 2px;
  background: var(--white);
  border-radius: 2px;
  transition: all 0.3s;
}

/* ===== HERO ===== */
#hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  position: relative;
  overflow: hidden;
  padding: 8rem 2rem 4rem;
}

.hero-bg {
  position: absolute;
  inset: 0;
  background: 
    radial-gradient(ellipse 80% 50% at 50% -10%, rgba(26,86,219,0.25) 0%, transparent 70%),
    radial-gradient(ellipse 40% 40% at 80% 60%, rgba(16,185,129,0.12) 0%, transparent 60%),
    linear-gradient(180deg, var(--navy) 0%, var(--navy-mid) 100%);
}

/* Solar grid lines */
.hero-grid {
  position: absolute;
  inset: 0;
  background-image: 
    linear-gradient(rgba(59,130,246,0.05) 1px, transparent 1px),
    linear-gradient(90deg, rgba(59,130,246,0.05) 1px, transparent 1px);
  background-size: 60px 60px;
  mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 30%, transparent 80%);
}

.hero-content {
  max-width: 1200px;
  margin: 0 auto;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  align-items: center;
  position: relative;
  z-index: 1;
}

.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: rgba(16,185,129,0.1);
  border: 1px solid rgba(16,185,129,0.3);
  border-radius: 100px;
  padding: 0.35rem 1rem;
  font-size: 0.78rem;
  font-weight: 500;
  color: var(--green-light);
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-bottom: 1.5rem;
}

.hero-badge::before {
  content: '';
  width: 6px;
  height: 6px;
  background: var(--green);
  border-radius: 50%;
  animation: pulse-dot 2s ease infinite;
}

@keyframes pulse-dot {
  0%, 100% { opacity: 1; transform: scale(1); }
  50% { opacity: 0.5; transform: scale(0.7); }
}

.hero-name {
  font-family: var(--font-display);
  font-size: clamp(2.8rem, 5vw, 4.2rem);
  font-weight: 800;
  line-height: 1.05;
  letter-spacing: -0.03em;
  margin-bottom: 0.5rem;
  background: linear-gradient(135deg, #ffffff 0%, #94b4e8 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-title {
  font-family: var(--font-display);
  font-size: clamp(1rem, 2vw, 1.25rem);
  font-weight: 600;
  color: var(--green-light);
  margin-bottom: 1.5rem;
  letter-spacing: 0.01em;
}

.hero-subtitle {
  font-size: 1rem;
  color: var(--grey-300);
  line-height: 1.75;
  margin-bottom: 2rem;
  font-weight: 300;
  max-width: 480px;
}

.hero-stats {
  display: flex;
  gap: 2rem;
  margin-bottom: 2.5rem;
}

.stat-item { text-align: left; }

.stat-number {
  font-family: var(--font-display);
  font-size: 2rem;
  font-weight: 800;
  color: var(--white);
  line-height: 1;
  display: block;
}

.stat-number .accent { color: var(--green); }

.stat-label {
  font-size: 0.75rem;
  color: var(--grey-400);
  text-transform: uppercase;
  letter-spacing: 0.08em;
  font-weight: 500;
}

.hero-actions {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.btn-primary {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: var(--green);
  color: var(--navy);
  font-family: var(--font-display);
  font-weight: 700;
  font-size: 0.9rem;
  padding: 0.85rem 1.75rem;
  border-radius: 8px;
  text-decoration: none;
  letter-spacing: 0.02em;
  transition: all 0.25s ease;
  border: none;
  cursor: pointer;
}

.btn-primary:hover {
  background: var(--green-light);
  transform: translateY(-2px);
  box-shadow: 0 8px 30px rgba(16,185,129,0.35);
}

.btn-secondary {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: transparent;
  color: var(--white);
  font-family: var(--font-display);
  font-weight: 600;
  font-size: 0.9rem;
  padding: 0.85rem 1.75rem;
  border-radius: 8px;
  text-decoration: none;
  border: 1px solid rgba(255,255,255,0.2);
  transition: all 0.25s ease;
  cursor: pointer;
}

.btn-secondary:hover {
  border-color: var(--blue-light);
  color: var(--blue-glow);
  background: rgba(59,130,246,0.08);
}

/* Solar panel visual */
.hero-visual {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}

.solar-panel-3d {
  width: 380px;
  height: 380px;
  position: relative;
  animation: float 6s ease-in-out infinite;
}

@keyframes float {
  0%, 100% { transform: translateY(0px) rotate(-2deg); }
  50% { transform: translateY(-15px) rotate(2deg); }
}

.solar-svg {
  width: 100%;
  height: 100%;
  filter: drop-shadow(0 20px 60px rgba(59,130,246,0.25)) drop-shadow(0 0 30px rgba(16,185,129,0.15));
}

.energy-ring {
  position: absolute;
  inset: -30px;
  border-radius: 50%;
  border: 1px solid rgba(16,185,129,0.2);
  animation: spin-slow 20s linear infinite;
}

.energy-ring::before {
  content: '';
  position: absolute;
  top: -3px;
  left: 50%;
  width: 6px;
  height: 6px;
  background: var(--green);
  border-radius: 50%;
  transform: translateX(-50%);
  box-shadow: 0 0 10px var(--green);
}

.energy-ring-2 {
  position: absolute;
  inset: -55px;
  border-radius: 50%;
  border: 1px solid rgba(59,130,246,0.15);
  animation: spin-slow 30s linear infinite reverse;
}

@keyframes spin-slow {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

/* ===== SECTION COMMON ===== */
section { position: relative; z-index: 1; }

.section-wrapper {
  max-width: 1200px;
  margin: 0 auto;
  padding: 5rem 2rem;
}

.section-eyebrow {
  font-size: 0.75rem;
  font-weight: 600;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--green);
  margin-bottom: 0.75rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.section-eyebrow::before {
  content: '';
  display: inline-block;
  width: 24px;
  height: 2px;
  background: var(--green);
}

.section-title {
  font-family: var(--font-display);
  font-size: clamp(1.8rem, 3.5vw, 2.8rem);
  font-weight: 800;
  letter-spacing: -0.03em;
  line-height: 1.1;
  margin-bottom: 1rem;
}

.section-desc {
  color: var(--grey-300);
  font-size: 1rem;
  max-width: 560px;
  line-height: 1.75;
  font-weight: 300;
}

/* ===== CLIENTS STRIP ===== */
#clients {
  border-top: 1px solid var(--border);
  border-bottom: 1px solid var(--border);
  padding: 2rem 0;
  overflow: hidden;
  background: rgba(255,255,255,0.02);
}

.clients-label {
  text-align: center;
  font-size: 0.72rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--grey-400);
  margin-bottom: 1.5rem;
  padding: 0 2rem;
}

.clients-scroll {
  display: flex;
  gap: 3rem;
  animation: scroll-x 20s linear infinite;
  width: max-content;
}

@keyframes scroll-x {
  from { transform: translateX(0); }
  to { transform: translateX(-50%); }
}

.client-logo {
  font-family: var(--font-display);
  font-size: 0.85rem;
  font-weight: 700;
  color: var(--grey-400);
  white-space: nowrap;
  letter-spacing: 0.05em;
  padding: 0 0.5rem;
  transition: color 0.2s;
  text-transform: uppercase;
}

/* ===== ABOUT ===== */
#about { background: var(--navy-mid); }

.about-grid {
  display: grid;
  grid-template-columns: 1fr 1.4fr;
  gap: 5rem;
  align-items: center;
}

.about-portrait {
  position: relative;
}

.portrait-frame {
  width: 100%;
  aspect-ratio: 4/5;
  background: linear-gradient(135deg, var(--navy-card) 0%, rgba(26,86,219,0.1) 100%);
  border-radius: 20px;
  border: 1px solid var(--border-bright);
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
}

.portrait-initials {
  font-family: var(--font-display);
  font-size: 6rem;
  font-weight: 800;
  color: var(--blue-primary);
  opacity: 0.5;
  letter-spacing: -0.05em;
}

.portrait-frame::after {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, transparent 50%, rgba(16,185,129,0.08) 100%);
}

.experience-badge {
  position: absolute;
  bottom: -1.5rem;
  right: -1.5rem;
  background: var(--green);
  color: var(--navy);
  border-radius: 16px;
  padding: 1.2rem 1.5rem;
  text-align: center;
  font-family: var(--font-display);
  font-weight: 800;
  box-shadow: 0 8px 30px rgba(16,185,129,0.4);
}

.experience-badge .years {
  font-size: 2.5rem;
  display: block;
  line-height: 1;
}

.experience-badge .years-label {
  font-size: 0.72rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.1em;
}

.about-content {}

.about-text {
  color: var(--grey-300);
  line-height: 1.85;
  margin-bottom: 1.5rem;
  font-size: 0.98rem;
  font-weight: 300;
}

.about-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin-top: 2rem;
}

.tag {
  background: rgba(26,86,219,0.1);
  border: 1px solid rgba(59,130,246,0.2);
  color: var(--blue-glow);
  padding: 0.35rem 0.85rem;
  border-radius: 100px;
  font-size: 0.78rem;
  font-weight: 500;
  letter-spacing: 0.03em;
}

.values-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
  margin-top: 2rem;
}

.value-card {
  background: rgba(255,255,255,0.03);
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 1.25rem;
  transition: border-color 0.25s, background 0.25s;
}

.value-card:hover {
  border-color: var(--border-bright);
  background: rgba(59,130,246,0.05);
}

.value-icon { font-size: 1.5rem; margin-bottom: 0.5rem; }
.value-label { font-size: 0.85rem; font-weight: 600; color: var(--white); }
.value-desc { font-size: 0.78rem; color: var(--grey-400); margin-top: 0.25rem; }

/* ===== EXPERIENCE TIMELINE ===== */
#experience { background: var(--navy); }

.timeline {
  position: relative;
  padding-left: 2rem;
  margin-top: 3rem;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 2px;
  background: linear-gradient(180deg, var(--blue-primary) 0%, var(--green) 100%);
}

.timeline-item {
  position: relative;
  padding-left: 2.5rem;
  padding-bottom: 3.5rem;
  opacity: 0;
  transform: translateX(-20px);
  transition: opacity 0.5s ease, transform 0.5s ease;
}

.timeline-item.visible {
  opacity: 1;
  transform: translateX(0);
}

.timeline-dot {
  position: absolute;
  left: -2.62rem;
  top: 0.35rem;
  width: 14px;
  height: 14px;
  border-radius: 50%;
  background: var(--blue-primary);
  border: 2px solid var(--navy);
  box-shadow: 0 0 0 3px rgba(26,86,219,0.3);
}

.timeline-dot.current {
  background: var(--green);
  box-shadow: 0 0 0 3px rgba(16,185,129,0.3), 0 0 15px rgba(16,185,129,0.5);
}

.timeline-period {
  font-size: 0.75rem;
  color: var(--green);
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  margin-bottom: 0.5rem;
}

.timeline-role {
  font-family: var(--font-display);
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--white);
  margin-bottom: 0.25rem;
}

.timeline-company {
  font-size: 0.9rem;
  color: var(--blue-glow);
  font-weight: 500;
  margin-bottom: 1rem;
}

.timeline-desc {
  font-size: 0.9rem;
  color: var(--grey-300);
  line-height: 1.7;
  font-weight: 300;
}

.timeline-bullets {
  list-style: none;
  margin-top: 0.75rem;
}

.timeline-bullets li {
  font-size: 0.88rem;
  color: var(--grey-300);
  padding: 0.3rem 0;
  display: flex;
  align-items: flex-start;
  gap: 0.6rem;
  font-weight: 300;
}

.timeline-bullets li::before {
  content: '▸';
  color: var(--green);
  font-size: 0.75rem;
  margin-top: 0.15rem;
  flex-shrink: 0;
}

.timeline-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-top: 1rem;
}

.timeline-tag {
  background: rgba(26,86,219,0.08);
  border: 1px solid rgba(59,130,246,0.15);
  color: var(--grey-300);
  padding: 0.2rem 0.65rem;
  border-radius: 100px;
  font-size: 0.73rem;
  font-weight: 500;
}

/* ===== PROJECTS ===== */
#projects { background: var(--navy-mid); }

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
  gap: 1.5rem;
  margin-top: 3rem;
}

.project-card {
  background: var(--navy-card);
  border: 1px solid var(--border);
  border-radius: 20px;
  overflow: hidden;
  transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;
  cursor: default;
  position: relative;
}

.project-card:hover {
  transform: translateY(-6px);
  border-color: rgba(59,130,246,0.4);
  box-shadow: 0 20px 60px rgba(0,0,0,0.4), 0 0 0 1px rgba(59,130,246,0.1);
}

.project-header {
  padding: 1.75rem 1.75rem 0;
  position: relative;
}

.project-type {
  display: inline-block;
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  padding: 0.25rem 0.75rem;
  border-radius: 100px;
  margin-bottom: 1rem;
}

.type-rooftop { background: rgba(16,185,129,0.15); color: var(--green-light); }
.type-ground { background: rgba(26,86,219,0.15); color: var(--blue-glow); }
.type-agri { background: rgba(245,158,11,0.15); color: var(--accent-gold); }
.type-industrial { background: rgba(139,92,246,0.15); color: #a78bfa; }

.project-name {
  font-family: var(--font-display);
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--white);
  margin-bottom: 0.25rem;
}

.project-location {
  font-size: 0.82rem;
  color: var(--grey-400);
  display: flex;
  align-items: center;
  gap: 0.35rem;
  margin-bottom: 1rem;
}

.project-body {
  padding: 1rem 1.75rem 1.75rem;
}

.project-kpis {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
  margin-bottom: 1.25rem;
  padding: 1rem;
  background: rgba(255,255,255,0.03);
  border-radius: 12px;
  border: 1px solid var(--border);
}

.kpi { text-align: center; }

.kpi-value {
  font-family: var(--font-display);
  font-size: 1.2rem;
  font-weight: 800;
  color: var(--white);
  display: block;
  line-height: 1;
}

.kpi-value .unit { font-size: 0.7rem; font-weight: 500; color: var(--grey-400); }

.kpi-label {
  font-size: 0.68rem;
  color: var(--grey-400);
  text-transform: uppercase;
  letter-spacing: 0.08em;
  margin-top: 0.3rem;
  display: block;
}

.project-desc {
  font-size: 0.85rem;
  color: var(--grey-300);
  line-height: 1.65;
  font-weight: 300;
  margin-bottom: 1rem;
}

.project-tools {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
}

.tool-chip {
  font-size: 0.72rem;
  font-weight: 600;
  color: var(--grey-300);
  background: rgba(255,255,255,0.05);
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  border: 1px solid rgba(255,255,255,0.08);
}

/* Performance bar */
.perf-bar-wrap { margin-top: 1.25rem; }

.perf-label-row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.4rem;
  font-size: 0.78rem;
}

.perf-label { color: var(--grey-300); font-weight: 500; }
.perf-value { color: var(--green-light); font-weight: 700; font-family: var(--font-display); }

.perf-bar {
  height: 4px;
  background: rgba(255,255,255,0.07);
  border-radius: 10px;
  overflow: hidden;
}

.perf-fill {
  height: 100%;
  border-radius: 10px;
  background: linear-gradient(90deg, var(--blue-primary), var(--green));
  transition: width 1s ease;
}

/* ===== SKILLS ===== */
#skills { background: var(--navy); }

.skills-layout {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  margin-top: 3rem;
}

.skill-category-title {
  font-family: var(--font-display);
  font-size: 1rem;
  font-weight: 700;
  color: var(--white);
  margin-bottom: 1.5rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.skill-category-title::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--border);
}

.skill-item {
  margin-bottom: 1.25rem;
  opacity: 0;
  transition: opacity 0.4s ease;
}

.skill-item.visible { opacity: 1; }

.skill-row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.5rem;
}

.skill-name {
  font-size: 0.88rem;
  font-weight: 500;
  color: var(--grey-100);
}

.skill-pct {
  font-size: 0.8rem;
  font-weight: 700;
  color: var(--green);
  font-family: var(--font-display);
}

.skill-bar {
  height: 6px;
  background: rgba(255,255,255,0.07);
  border-radius: 10px;
  overflow: hidden;
}

.skill-fill {
  height: 100%;
  border-radius: 10px;
  background: linear-gradient(90deg, var(--blue-primary), var(--green-light));
  width: 0%;
  transition: width 1.2s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Soft skills */
.soft-skills-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0.75rem;
}

.soft-skill-card {
  background: var(--navy-card);
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 1rem 1.25rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
  transition: border-color 0.25s, transform 0.25s;
}

.soft-skill-card:hover {
  border-color: var(--border-bright);
  transform: scale(1.02);
}

.soft-icon { font-size: 1.25rem; }

.soft-name {
  font-size: 0.85rem;
  font-weight: 500;
  color: var(--grey-100);
}

/* Tools hexagon display */
.tools-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1rem;
}

.tool-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  background: var(--navy-card);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 0.6rem 1rem;
  transition: all 0.25s;
}

.tool-badge:hover {
  border-color: var(--green);
  background: rgba(16,185,129,0.05);
}

.tool-badge-icon { font-size: 1.1rem; }
.tool-badge-name { font-size: 0.82rem; font-weight: 600; color: var(--grey-100); }

/* ===== EDUCATION ===== */
#education { background: var(--navy-mid); }

.edu-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
  margin-top: 3rem;
}

.edu-card {
  background: var(--navy-card);
  border: 1px solid var(--border);
  border-radius: 20px;
  padding: 2rem;
  position: relative;
  overflow: hidden;
  transition: border-color 0.3s, transform 0.3s;
}

.edu-card:hover {
  border-color: var(--border-bright);
  transform: translateY(-4px);
}

.edu-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 3px;
  background: linear-gradient(90deg, var(--blue-primary), var(--green));
}

.edu-icon {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.edu-degree {
  font-family: var(--font-display);
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--white);
  margin-bottom: 0.35rem;
  line-height: 1.3;
}

.edu-institution {
  font-size: 0.88rem;
  color: var(--blue-glow);
  font-weight: 500;
  margin-bottom: 0.25rem;
}

.edu-year {
  font-size: 0.78rem;
  color: var(--grey-400);
  font-weight: 500;
}

.edu-desc {
  font-size: 0.85rem;
  color: var(--grey-300);
  line-height: 1.6;
  margin-top: 0.75rem;
  font-weight: 300;
}

/* cert badge */
.cert-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  background: rgba(245,158,11,0.1);
  border: 1px solid rgba(245,158,11,0.3);
  color: var(--accent-gold);
  padding: 0.25rem 0.75rem;
  border-radius: 100px;
  font-size: 0.75rem;
  font-weight: 600;
  margin-top: 0.75rem;
}

/* ===== TESTIMONIALS ===== */
#testimonials { background: var(--navy); }

.testimonials-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-top: 3rem;
}

.testimonial-card {
  background: var(--navy-card);
  border: 1px solid var(--border);
  border-radius: 20px;
  padding: 2rem;
  position: relative;
}

.testimonial-card.placeholder {
  border-style: dashed;
  border-color: rgba(255,255,255,0.1);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  min-height: 200px;
  transition: border-color 0.3s;
}

.testimonial-card.placeholder:hover {
  border-color: rgba(59,130,246,0.3);
}

.placeholder-icon { font-size: 2rem; opacity: 0.3; margin-bottom: 0.75rem; }
.placeholder-text { font-size: 0.85rem; color: var(--grey-400); font-style: italic; }

.quote-mark {
  font-size: 3rem;
  color: var(--blue-primary);
  opacity: 0.4;
  font-family: Georgia, serif;
  line-height: 0.8;
  margin-bottom: 1rem;
}

.testimonial-text {
  font-size: 0.9rem;
  color: var(--grey-300);
  line-height: 1.75;
  font-style: italic;
  font-weight: 300;
  margin-bottom: 1.5rem;
}

.testimonial-author {
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.author-avatar {
  width: 42px;
  height: 42px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--blue-primary), var(--green));
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--font-display);
  font-weight: 800;
  font-size: 0.85rem;
  color: var(--white);
}

.author-name {
  font-weight: 600;
  font-size: 0.9rem;
  color: var(--white);
}

.author-title {
  font-size: 0.78rem;
  color: var(--grey-400);
}

/* ===== CONTACT ===== */
#contact { background: var(--navy-mid); }

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1.2fr;
  gap: 4rem;
  margin-top: 3rem;
}

.contact-info { }

.contact-intro {
  font-size: 1rem;
  color: var(--grey-300);
  line-height: 1.8;
  font-weight: 300;
  margin-bottom: 2.5rem;
}

.contact-methods {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.contact-method {
  display: flex;
  align-items: center;
  gap: 1rem;
  padding: 1rem 1.25rem;
  background: var(--navy-card);
  border: 1px solid var(--border);
  border-radius: 12px;
  text-decoration: none;
  color: inherit;
  transition: all 0.25s;
}

.contact-method:hover {
  border-color: var(--border-bright);
  transform: translateX(4px);
}

.contact-method-icon {
  width: 42px;
  height: 42px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.1rem;
  flex-shrink: 0;
}

.icon-linkedin { background: rgba(10,102,194,0.15); }
.icon-email { background: rgba(26,86,219,0.15); }
.icon-phone { background: rgba(16,185,129,0.15); }
.icon-location { background: rgba(245,158,11,0.15); }

.contact-method-label {
  font-size: 0.75rem;
  color: var(--grey-400);
  text-transform: uppercase;
  letter-spacing: 0.08em;
  font-weight: 600;
}

.contact-method-value {
  font-size: 0.9rem;
  color: var(--white);
  font-weight: 500;
}

/* Form */
.contact-form {
  background: var(--navy-card);
  border: 1px solid var(--border);
  border-radius: 20px;
  padding: 2.5rem;
}

.form-title {
  font-family: var(--font-display);
  font-size: 1.2rem;
  font-weight: 700;
  margin-bottom: 1.75rem;
  color: var(--white);
}

.form-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; margin-bottom: 1rem; }

.form-group { display: flex; flex-direction: column; gap: 0.4rem; }

.form-group.full { grid-column: 1 / -1; }

.form-label {
  font-size: 0.78rem;
  font-weight: 600;
  color: var(--grey-300);
  letter-spacing: 0.04em;
  text-transform: uppercase;
}

.form-input, .form-textarea, .form-select {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.1);
  border-radius: 8px;
  padding: 0.75rem 1rem;
  font-family: var(--font-body);
  font-size: 0.9rem;
  color: var(--white);
  outline: none;
  transition: border-color 0.2s, background 0.2s;
  width: 100%;
}

.form-input::placeholder, .form-textarea::placeholder {
  color: var(--grey-400);
  font-weight: 300;
}

.form-input:focus, .form-textarea:focus, .form-select:focus {
  border-color: var(--blue-light);
  background: rgba(59,130,246,0.05);
}

.form-textarea { resize: vertical; min-height: 120px; }

.form-select { cursor: pointer; }
.form-select option { background: var(--navy-card); }

.form-submit {
  width: 100%;
  margin-top: 1.25rem;
  padding: 0.9rem;
  font-size: 0.95rem;
}

/* ===== FOOTER ===== */
footer {
  background: var(--navy);
  border-top: 1px solid var(--border);
  padding: 2.5rem 2rem;
}

.footer-inner {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.footer-logo {
  font-family: var(--font-display);
  font-size: 1.1rem;
  font-weight: 800;
  color: var(--white);
  text-decoration: none;
}

.footer-logo span { color: var(--green); }

.footer-links {
  display: flex;
  gap: 1.5rem;
  list-style: none;
}

.footer-links a {
  font-size: 0.82rem;
  color: var(--grey-400);
  text-decoration: none;
  transition: color 0.2s;
}

.footer-links a:hover { color: var(--green-light); }

.footer-copy {
  font-size: 0.78rem;
  color: var(--grey-400);
}

/* Language switcher */
.lang-switcher {
  display: flex;
  gap: 0.5rem;
  align-items: center;
}

.lang-btn {
  background: none;
  border: 1px solid var(--border);
  color: var(--grey-400);
  padding: 0.3rem 0.65rem;
  border-radius: 6px;
  font-size: 0.75rem;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.2s;
  letter-spacing: 0.05em;
}

.lang-btn.active, .lang-btn:hover {
  border-color: var(--green);
  color: var(--green);
  background: rgba(16,185,129,0.08);
}

/* ===== AVAILABILITY BANNER ===== */
.avail-banner {
  background: linear-gradient(90deg, rgba(16,185,129,0.12) 0%, rgba(26,86,219,0.12) 100%);
  border: 1px solid rgba(16,185,129,0.25);
  border-radius: 12px;
  padding: 1rem 1.5rem;
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.avail-dot {
  width: 10px;
  height: 10px;
  background: var(--green);
  border-radius: 50%;
  flex-shrink: 0;
  box-shadow: 0 0 8px var(--green);
  animation: pulse-dot 2s ease infinite;
}

.avail-text {
  font-size: 0.88rem;
  color: var(--green-light);
  font-weight: 500;
}

/* ===== SCROLL ANIMATIONS ===== */
.fade-up {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.6s ease, transform 0.6s ease;
}

.fade-up.visible {
  opacity: 1;
  transform: translateY(0);
}

/* ===== MOBILE NAV ===== */
@media (max-width: 900px) {
  .hamburger { display: flex; }
  
  .nav-links {
    display: none;
    position: fixed;
    top: 64px;
    left: 0;
    right: 0;
    background: rgba(10,14,26,0.98);
    backdrop-filter: blur(20px);
    flex-direction: column;
    padding: 2rem;
    border-bottom: 1px solid var(--border);
    gap: 1.25rem;
  }
  
  .nav-links.open { display: flex; }
  
  .hero-content { grid-template-columns: 1fr; gap: 2rem; }
  .hero-visual { order: -1; }
  .solar-panel-3d { width: 260px; height: 260px; }
  
  .about-grid { grid-template-columns: 1fr; gap: 2.5rem; }
  .portrait-frame { max-width: 280px; }
  
  .skills-layout { grid-template-columns: 1fr; gap: 2.5rem; }
  
  .contact-grid { grid-template-columns: 1fr; }
  
  .edu-grid { grid-template-columns: 1fr; }
  
  .projects-grid { grid-template-columns: 1fr; }
  
  .values-grid { grid-template-columns: 1fr; }
  
  .form-grid { grid-template-columns: 1fr; }
  
  .footer-inner { flex-direction: column; text-align: center; }
}

@media (max-width: 600px) {
  .hero-stats { gap: 1.25rem; }
  .stat-number { font-size: 1.6rem; }
  .section-wrapper { padding: 3.5rem 1.25rem; }
}

/* ===== PROGRESS CIRCLE ===== */
.perf-circles {
  display: flex;
  justify-content: center;
  gap: 2.5rem;
  flex-wrap: wrap;
  margin: 2.5rem 0 1rem;
}

.circle-wrap {
  text-align: center;
}

.circle-svg { transform: rotate(-90deg); }

.circle-bg { fill: none; stroke: rgba(255,255,255,0.07); stroke-width: 6; }
.circle-fill {
  fill: none;
  stroke-width: 6;
  stroke-linecap: round;
  stroke-dasharray: 283;
  stroke-dashoffset: 283;
  transition: stroke-dashoffset 1.5s cubic-bezier(0.4,0,0.2,1);
}
.fill-blue { stroke: url(#grad-blue); }
.fill-green { stroke: url(#grad-green); }
.fill-gold { stroke: url(#grad-gold); }

.circle-label {
  font-family: var(--font-display);
  font-size: 0.95rem;
  font-weight: 700;
  color: var(--white);
  margin-top: 0.75rem;
}

.circle-sublabel {
  font-size: 0.72rem;
  color: var(--grey-400);
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

.circle-center {
  font-family: var(--font-display);
  font-size: 0.9rem;
  font-weight: 800;
  fill: var(--white);
}
</style>
</head>
<body>

<!-- ===== NAVIGATION ===== -->
<nav id="navbar">
  <a href="#" class="nav-logo">R<span>.</span>Zayoud</a>
  
  <ul class="nav-links" id="navLinks">
    <li><a href="#about">Profil</a></li>
    <li><a href="#experience">Expérience</a></li>
    <li><a href="#projects">Projets</a></li>
    <li><a href="#skills">Compétences</a></li>
    <li><a href="#education">Formation</a></li>
    <li><a href="#contact" class="nav-cta">Contact</a></li>
  </ul>
  
  <div style="display:flex;align-items:center;gap:1rem;">
    <div class="lang-switcher">
      <button class="lang-btn active" onclick="setLang('fr')">FR</button>
      <button class="lang-btn" onclick="setLang('en')">EN</button>
    </div>
    <button class="hamburger" id="hamburger" aria-label="Menu" onclick="toggleMenu()">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<!-- ===== HERO ===== -->
<section id="hero" aria-label="Introduction">
  <div class="hero-bg"></div>
  <div class="hero-grid"></div>
  
  <div class="hero-content">
    <div class="hero-text">
      <div class="hero-badge" data-fr="Disponible pour opportunités" data-en="Open to opportunities">
        Disponible pour opportunités
      </div>
      
      <h1 class="hero-name">Radhouane<br>Zayoud</h1>
      
      <p class="hero-title" data-fr="Chef de Projets Photovoltaïques | Solar PV Engineer" data-en="Photovoltaic Project Manager | Solar PV Engineer">
        Chef de Projets Photovoltaïques | Solar PV Engineer
      </p>
      
      <p class="hero-subtitle" data-fr="Ingénieur expert en développement, conception et gestion de projets solaires. Passionné par la transition énergétique, je transforme les études techniques en centrales photovoltaïques performantes." data-en="Expert engineer in solar project development, design and management. Passionate about the energy transition, I turn technical studies into high-performing photovoltaic power plants.">
        Ingénieur expert en développement, conception et gestion de projets solaires. Passionné par la transition énergétique, je transforme les études techniques en centrales photovoltaïques performantes.
      </p>
      
      <div class="hero-stats">
        <div class="stat-item">
          <span class="stat-number">4<span class="accent">+</span></span>
          <span class="stat-label" data-fr="Années d'expérience" data-en="Years of experience">Années d'expérience</span>
        </div>
        <div class="stat-item">
          <span class="stat-number">25<span class="accent">+</span></span>
          <span class="stat-label" data-fr="Projets livrés" data-en="Projects delivered">Projets livrés</span>
        </div>
        <div class="stat-item">
          <span class="stat-number">50<span class="accent">+</span></span>
          <span class="stat-label">MWc</span>
        </div>
      </div>
      
      <div class="hero-actions">
        <a href="#contact" class="btn-primary">
          ✉ <span data-fr="Me Contacter" data-en="Contact Me">Me Contacter</span>
        </a>
        <a href="#" class="btn-secondary" onclick="downloadCV()">
          ↓ <span data-fr="Télécharger CV" data-en="Download CV">Télécharger CV</span>
        </a>
        <a href="https://www.linkedin.com/in/radhouanezayoud" target="_blank" class="btn-secondary" aria-label="LinkedIn">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"/><circle cx="4" cy="4" r="2"/></svg>
          LinkedIn
        </a>
      </div>
    </div>
    
    <div class="hero-visual" aria-hidden="true">
      <div class="solar-panel-3d">
        <div class="energy-ring"></div>
        <div class="energy-ring-2"></div>
        <svg class="solar-svg" viewBox="0 0 380 380" fill="none" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="panel-grad" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#1a56db" stop-opacity="0.9"/>
              <stop offset="100%" stop-color="#0d1528" stop-opacity="0.95"/>
            </linearGradient>
            <linearGradient id="cell-grad" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#1e40af" stop-opacity="0.7"/>
              <stop offset="100%" stop-color="#1e3a8a" stop-opacity="0.5"/>
            </linearGradient>
            <linearGradient id="glow-grad" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#10b981" stop-opacity="0.6"/>
              <stop offset="100%" stop-color="#3b82f6" stop-opacity="0.3"/>
            </linearGradient>
            <linearGradient id="grad-blue" x1="0%" y1="0%" x2="0%" y2="100%">
              <stop offset="0%" stop-color="#3b82f6"/>
              <stop offset="100%" stop-color="#1d4ed8"/>
            </linearGradient>
            <linearGradient id="grad-green" x1="0%" y1="0%" x2="0%" y2="100%">
              <stop offset="0%" stop-color="#10b981"/>
              <stop offset="100%" stop-color="#059669"/>
            </linearGradient>
            <linearGradient id="grad-gold" x1="0%" y1="0%" x2="0%" y2="100%">
              <stop offset="0%" stop-color="#f59e0b"/>
              <stop offset="100%" stop-color="#d97706"/>
            </linearGradient>
            <filter id="glow">
              <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
              <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
            </filter>
          </defs>
          
          <!-- Outer glow circle -->
          <circle cx="190" cy="190" r="170" fill="none" stroke="url(#glow-grad)" stroke-width="1" opacity="0.5"/>
          
          <!-- Main panel frame -->
          <rect x="60" y="80" width="260" height="200" rx="8" fill="url(#panel-grad)" stroke="#3b82f6" stroke-width="1.5" stroke-opacity="0.5"/>
          
          <!-- Solar cells grid (4x3) -->
          <!-- Row 1 -->
          <rect x="70" y="90" width="57" height="57" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="133" y="90" width="57" height="57" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="196" y="90" width="57" height="57" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="259" y="90" width="51" height="57" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <!-- Row 2 -->
          <rect x="70" y="153" width="57" height="57" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="133" y="153" width="57" height="57" rx="3" fill="#10b981" fill-opacity="0.18" stroke="#10b981" stroke-width="0.8" stroke-opacity="0.6"/>
          <rect x="196" y="153" width="57" height="57" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="259" y="153" width="51" height="57" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <!-- Row 3 -->
          <rect x="70" y="216" width="57" height="54" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="133" y="216" width="57" height="54" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="196" y="216" width="57" height="54" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          <rect x="259" y="216" width="51" height="54" rx="3" fill="url(#cell-grad)" stroke="#1d4ed8" stroke-width="0.8" stroke-opacity="0.8"/>
          
          <!-- Reflection highlights on cells -->
          <rect x="72" y="92" width="22" height="8" rx="2" fill="white" fill-opacity="0.08"/>
          <rect x="135" y="92" width="22" height="8" rx="2" fill="white" fill-opacity="0.08"/>
          <rect x="198" y="92" width="22" height="8" rx="2" fill="white" fill-opacity="0.08"/>
          
          <!-- Bus bar lines -->
          <line x1="99" y1="90" x2="99" y2="270" stroke="#3b82f6" stroke-width="0.6" stroke-opacity="0.4"/>
          <line x1="162" y1="90" x2="162" y2="270" stroke="#3b82f6" stroke-width="0.6" stroke-opacity="0.4"/>
          <line x1="225" y1="90" x2="225" y2="270" stroke="#3b82f6" stroke-width="0.6" stroke-opacity="0.4"/>
          
          <!-- Panel frame metallic edge -->
          <rect x="60" y="80" width="260" height="200" rx="8" fill="none" stroke="url(#glow-grad)" stroke-width="2"/>
          
          <!-- Support structure -->
          <line x1="140" y1="280" x2="120" y2="310" stroke="#3b82f6" stroke-width="3" stroke-opacity="0.6"/>
          <line x1="240" y1="280" x2="260" y2="310" stroke="#3b82f6" stroke-width="3" stroke-opacity="0.6"/>
          <line x1="190" y1="280" x2="190" y2="310" stroke="#3b82f6" stroke-width="3" stroke-opacity="0.6"/>
          <line x1="100" y1="310" x2="280" y2="310" stroke="#3b82f6" stroke-width="3" stroke-opacity="0.6"/>
          
          <!-- Sun rays -->
          <g filter="url(#glow)" opacity="0.8">
            <circle cx="330" cy="70" r="20" fill="#f59e0b" fill-opacity="0.6"/>
            <line x1="330" y1="40" x2="330" y2="25" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.8"/>
            <line x1="330" y1="100" x2="330" y2="115" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.8"/>
            <line x1="300" y1="70" x2="285" y2="70" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.8"/>
            <line x1="360" y1="70" x2="375" y2="70" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.8"/>
            <line x1="309" y1="49" x2="299" y2="39" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.6"/>
            <line x1="351" y1="91" x2="361" y2="101" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.6"/>
            <line x1="351" y1="49" x2="361" y2="39" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.6"/>
            <line x1="309" y1="91" x2="299" y2="101" stroke="#f59e0b" stroke-width="2" stroke-opacity="0.6"/>
          </g>
          
          <!-- Energy flow particles -->
          <circle cx="190" cy="155" r="4" fill="#10b981" opacity="0.9" filter="url(#glow)">
            <animate attributeName="cy" values="155;95;155" dur="3s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0.9;0;0.9" dur="3s" repeatCount="indefinite"/>
          </circle>
          <circle cx="160" cy="155" r="3" fill="#3b82f6" opacity="0.7" filter="url(#glow)">
            <animate attributeName="cy" values="155;105;155" dur="4s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0.7;0;0.7" dur="4s" repeatCount="indefinite"/>
          </circle>
          <circle cx="220" cy="155" r="3" fill="#10b981" opacity="0.7" filter="url(#glow)">
            <animate attributeName="cy" values="155;110;155" dur="3.5s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0.7;0;0.7" dur="3.5s" repeatCount="indefinite"/>
          </circle>
          
          <!-- Stats overlay -->
          <rect x="55" y="315" width="270" height="52" rx="10" fill="rgba(13,21,40,0.95)" stroke="#1a56db" stroke-width="1" stroke-opacity="0.5"/>
          <text x="95" y="334" font-family="Syne, sans-serif" font-size="10" fill="#94a3b8" letter-spacing="1">RENDEMENT</text>
          <text x="95" y="350" font-family="Syne, sans-serif" font-size="14" font-weight="800" fill="#10b981">98.2%</text>
          <text x="200" y="334" font-family="Syne, sans-serif" font-size="10" fill="#94a3b8" letter-spacing="1">PUISSANCE</text>
          <text x="200" y="350" font-family="Syne, sans-serif" font-size="14" font-weight="800" fill="#3b82f6">4.8 MWc</text>
          
          <rect x="65" y="322" width="8" height="8" rx="2" fill="#10b981" opacity="0.8"/>
          <rect x="190" y="322" width="8" height="8" rx="2" fill="#3b82f6" opacity="0.8"/>
        </svg>
      </div>
    </div>
  </div>
</section>

<!-- ===== CLIENTS STRIP ===== -->
<div id="clients" aria-label="Entreprises cibles">
  <p class="clients-label" data-fr="Entreprises visées & secteur d'activité" data-en="Target companies & industry">Entreprises visées & secteur d'activité</p>
  <div class="clients-scroll">
    <span class="client-logo">TotalEnergies</span>
    <span class="client-logo">EDF Renouvelables</span>
    <span class="client-logo">ENGIE Green</span>
    <span class="client-logo">Générale du Solaire</span>
    <span class="client-logo">Akuo Energy</span>
    <span class="client-logo">Voltalia</span>
    <span class="client-logo">Q ENERGY</span>
    <span class="client-logo">BayWa r.e.</span>
    <span class="client-logo">Neoen</span>
    <span class="client-logo">Valeco</span>
    <span class="client-logo">Urbasolar</span>
    <span class="client-logo">Omniénergie</span>
    <!-- Duplicate for seamless loop -->
    <span class="client-logo">TotalEnergies</span>
    <span class="client-logo">EDF Renouvelables</span>
    <span class="client-logo">ENGIE Green</span>
    <span class="client-logo">Générale du Solaire</span>
    <span class="client-logo">Akuo Energy</span>
    <span class="client-logo">Voltalia</span>
    <span class="client-logo">Q ENERGY</span>
    <span class="client-logo">BayWa r.e.</span>
    <span class="client-logo">Neoen</span>
    <span class="client-logo">Valeco</span>
    <span class="client-logo">Urbasolar</span>
    <span class="client-logo">Omniénergie</span>
  </div>
</div>

<!-- ===== ABOUT ===== -->
<section id="about" aria-label="À propos">
  <div class="section-wrapper">
    <div class="about-grid">
      <div class="about-portrait fade-up">
        <div class="portrait-frame">
          <span class="portrait-initials">RZ</span>
        </div>
        <div class="experience-badge">
          <span class="years">4+</span>
          <span class="years-label" data-fr="Ans d'expertise" data-en="Years expertise">Ans d'expertise</span>
        </div>
      </div>
      
      <div class="about-content fade-up">
        <div class="section-eyebrow" data-fr="À propos de moi" data-en="About me">À propos de moi</div>
        <h2 class="section-title" data-fr="Ingénieur dédié à la révolution solaire" data-en="Engineer dedicated to the solar revolution">Ingénieur dédié à la révolution solaire</h2>
        
        <div class="avail-banner">
          <div class="avail-dot"></div>
          <p class="avail-text" data-fr="Disponible immédiatement — Ouvert aux opportunités en France, Europe & International" data-en="Immediately available — Open to opportunities in France, Europe & International">
            Disponible immédiatement — Ouvert aux opportunités en France, Europe & International
          </p>
        </div>
        
        <p class="about-text" data-fr="Titulaire d'un Diplôme National d'Ingénieur en Électrique Automatique, j'ai développé une expertise approfondie dans le secteur du photovoltaïque au cours de ces 4 dernières années. Mon profil combine la rigueur d'un bureau d'études techniques et les compétences opérationnelles d'un chef de projet terrain." data-en="Holding a National Engineering Degree in Electrical Engineering & Automation, I have developed deep expertise in the photovoltaic sector over the past 4 years. My profile combines the rigor of a technical design office with the operational skills of a field project manager.">
          Titulaire d'un Diplôme National d'Ingénieur en Électrique Automatique, j'ai développé une expertise approfondie dans le secteur du photovoltaïque au cours de ces 4 dernières années. Mon profil combine la rigueur d'un bureau d'études techniques et les compétences opérationnelles d'un chef de projet terrain.
        </p>
        
        <p class="about-text" data-fr="De l'analyse de faisabilité au dimensionnement électrique HT/BT, en passant par les simulations PVSyst, les études de raccordement et la coordination de sous-traitants, j'accompagne chaque projet de la conception à la mise en service avec un focus constant sur la performance et la rentabilité." data-en="From feasibility analysis to HV/LV electrical sizing, PVSyst simulations, grid connection studies and subcontractor coordination, I support each project from design to commissioning with a constant focus on performance and profitability.">
          De l'analyse de faisabilité au dimensionnement électrique HT/BT, en passant par les simulations PVSyst, les études de raccordement et la coordination de sous-traitants, j'accompagne chaque projet de la conception à la mise en service avec un focus constant sur la performance et la rentabilité.
        </p>
        
        <div class="about-tags">
          <span class="tag">🇫🇷 Français</span>
          <span class="tag">🇬🇧 English</span>
          <span class="tag">🇹🇳 Arabe</span>
          <span class="tag">📍 Mobilité internationale</span>
        </div>
        
        <div class="values-grid">
          <div class="value-card">
            <div class="value-icon">⚡</div>
            <div class="value-label" data-fr="Excellence technique" data-en="Technical excellence">Excellence technique</div>
            <div class="value-desc" data-fr="Simulations PVSyst précises, dimensionnement rigoureux" data-en="Precise PVSyst simulations, rigorous sizing">Simulations PVSyst précises, dimensionnement rigoureux</div>
          </div>
          <div class="value-card">
            <div class="value-icon">🎯</div>
            <div class="value-label" data-fr="Livraison dans les délais" data-en="On-time delivery">Livraison dans les délais</div>
            <div class="value-desc" data-fr="Gestion proactive des risques et des plannings" data-en="Proactive risk and schedule management">Gestion proactive des risques et des plannings</div>
          </div>
          <div class="value-card">
            <div class="value-icon">🌍</div>
            <div class="value-label" data-fr="Impact environnemental" data-en="Environmental impact">Impact environnemental</div>
            <div class="value-desc" data-fr="Contribution concrète à la transition énergétique" data-en="Concrete contribution to the energy transition">Contribution concrète à la transition énergétique</div>
          </div>
          <div class="value-card">
            <div class="value-icon">🤝</div>
            <div class="value-label" data-fr="Leadership terrain" data-en="Field leadership">Leadership terrain</div>
            <div class="value-desc" data-fr="Coordination efficace de toutes les parties prenantes" data-en="Effective coordination of all stakeholders">Coordination efficace de toutes les parties prenantes</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===== EXPERIENCE ===== -->
<section id="experience" aria-label="Expérience professionnelle">
  <div class="section-wrapper">
    <div class="fade-up">
      <div class="section-eyebrow" data-fr="Parcours professionnel" data-en="Professional background">Parcours professionnel</div>
      <h2 class="section-title" data-fr="4 ans de projets solaires" data-en="4 years of solar projects">4 ans de projets solaires</h2>
      <p class="section-desc" data-fr="Une progression constante dans des environnements exigeants, avec des responsabilités croissantes sur des projets de plus en plus complexes." data-en="Consistent progression in demanding environments, with growing responsibilities on increasingly complex projects.">Une progression constante dans des environnements exigeants, avec des responsabilités croissantes sur des projets de plus en plus complexes.</p>
    </div>
    
    <div class="timeline" style="margin-top:3rem;">
      
      <div class="timeline-item">
        <div class="timeline-dot current"></div>
        <div class="timeline-period" data-fr="2022 — Présent" data-en="2022 — Present">2022 — Présent</div>
        <div class="timeline-role" data-fr="Chef de Projets Photovoltaïques" data-en="Photovoltaic Project Manager">Chef de Projets Photovoltaïques</div>
        <div class="timeline-company" data-fr="Bureau d'Études & Développement Solaire" data-en="Solar Design Office & Development">Bureau d'Études & Développement Solaire</div>
        <ul class="timeline-bullets">
          <li data-fr="Pilotage bout-en-bout de projets PV de 100 kWc à 10 MWc : développement, conception, autorisations, construction, mise en service" data-en="End-to-end management of PV projects from 100 kWc to 10 MWc: development, design, permits, construction, commissioning">Pilotage bout-en-bout de projets PV de 100 kWc à 10 MWc : développement, conception, autorisations, construction, mise en service</li>
          <li data-fr="Réalisation de simulations PVSyst et dimensionnement électrique complet HTA/HTB/BT" data-en="PVSyst simulations and complete HV/LV electrical sizing">Réalisation de simulations PVSyst et dimensionnement électrique complet HTA/HTB/BT</li>
          <li data-fr="Pilotage d'équipes pluridisciplinaires : génie civil, électricité, contrôle-commande" data-en="Leading multidisciplinary teams: civil engineering, electrical, control systems">Pilotage d'équipes pluridisciplinaires : génie civil, électricité, contrôle-commande</li>
          <li data-fr="Suivi budgétaire, reporting et analyse de performance des centrales" data-en="Budget monitoring, reporting and plant performance analysis">Suivi budgétaire, reporting et analyse de performance des centrales</li>
          <li data-fr="Interface avec les gestionnaires de réseau pour les études de raccordement" data-en="Liaison with grid operators for connection studies">Interface avec les gestionnaires de réseau pour les études de raccordement</li>
        </ul>
        <div class="timeline-tags">
          <span class="timeline-tag">PVSyst</span>
          <span class="timeline-tag">AutoCAD</span>
          <span class="timeline-tag">HTA/HTB</span>
          <span class="timeline-tag">Gestion équipes</span>
          <span class="timeline-tag">Budget</span>
          <span class="timeline-tag">Raccordement</span>
        </div>
      </div>
      
      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="timeline-period">2020 — 2022</div>
        <div class="timeline-role" data-fr="Ingénieur Bureau d'Études PV" data-en="PV Design Engineer">Ingénieur Bureau d'Études PV</div>
        <div class="timeline-company" data-fr="Société d'Ingénierie Électrique" data-en="Electrical Engineering Company">Société d'Ingénierie Électrique</div>
        <ul class="timeline-bullets">
          <li data-fr="Conception et dimensionnement de systèmes photovoltaïques résidentiels, tertiaires et industriels" data-en="Design and sizing of residential, commercial and industrial PV systems">Conception et dimensionnement de systèmes photovoltaïques résidentiels, tertiaires et industriels</li>
          <li data-fr="Réalisation de plans d'implantation et de câblage sur AutoCAD" data-en="Layout and wiring plans on AutoCAD">Réalisation de plans d'implantation et de câblage sur AutoCAD</li>
          <li data-fr="Rédaction des dossiers techniques et des cahiers des charges" data-en="Technical documentation and specifications writing">Rédaction des dossiers techniques et des cahiers des charges</li>
          <li data-fr="Analyse des ombrages et optimisation des rendements via PVSyst" data-en="Shading analysis and yield optimization via PVSyst">Analyse des ombrages et optimisation des rendements via PVSyst</li>
        </ul>
        <div class="timeline-tags">
          <span class="timeline-tag">PVSyst</span>
          <span class="timeline-tag">AutoCAD</span>
          <span class="timeline-tag">Dimensionnement</span>
          <span class="timeline-tag">Dossiers techniques</span>
        </div>
      </div>
      
      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="timeline-period" data-fr="2019 — 2020" data-en="2019 — 2020">2019 — 2020</div>
        <div class="timeline-role" data-fr="Ingénieur Stagiaire — Projets PV" data-en="Internship Engineer — PV Projects">Ingénieur Stagiaire — Projets PV</div>
        <div class="timeline-company" data-fr="Secteur Énergies Renouvelables" data-en="Renewable Energy Sector">Secteur Énergies Renouvelables</div>
        <ul class="timeline-bullets">
          <li data-fr="Participation à des études de faisabilité technico-économique de projets solaires" data-en="Participation in techno-economic feasibility studies for solar projects">Participation à des études de faisabilité technico-économique de projets solaires</li>
          <li data-fr="Apprentissage des outils de simulation et des normes électriques applicables" data-en="Learning simulation tools and applicable electrical standards">Apprentissage des outils de simulation et des normes électriques applicables</li>
          <li data-fr="Contribution aux dossiers de permis et d'autorisation administrative" data-en="Contribution to permit and administrative authorization files">Contribution aux dossiers de permis et d'autorisation administrative</li>
        </ul>
        <div class="timeline-tags">
          <span class="timeline-tag">Faisabilité</span>
          <span class="timeline-tag">Normes électriques</span>
          <span class="timeline-tag">PV</span>
        </div>
      </div>
      
    </div>
  </div>
</section>

<!-- ===== PROJECTS ===== -->
<section id="projects" aria-label="Réalisations photovoltaïques">
  <div class="section-wrapper">
    <div class="fade-up">
      <div class="section-eyebrow" data-fr="Réalisations" data-en="Portfolio">Réalisations</div>
      <h2 class="section-title" data-fr="Projets photovoltaïques" data-en="Photovoltaic projects">Projets photovoltaïques</h2>
      <p class="section-desc" data-fr="Une sélection de projets representatifs illustrant la diversité de mes interventions : centrales au sol, toitures, agrivoltaïsme et projets industriels." data-en="A selection of representative projects illustrating the diversity of my work: ground-mounted plants, rooftops, agrivoltaics and industrial projects.">Une sélection de projets représentatifs illustrant la diversité de mes interventions : centrales au sol, toitures, agrivoltaïsme et projets industriels.</p>
    </div>
    
    <div class="projects-grid">
      
      <!-- Project 1 -->
      <div class="project-card fade-up">
        <div class="project-header">
          <span class="project-type type-ground" data-fr="Centrale au sol" data-en="Ground-mounted">Centrale au sol</span>
          <div class="project-name" data-fr="Centrale PV — Sud Tunisie" data-en="PV Plant — Southern Tunisia">Centrale PV — Sud Tunisie</div>
          <div class="project-location">📍 <span data-fr="Région de Gabès, Tunisie" data-en="Gabès region, Tunisia">Région de Gabès, Tunisie</span></div>
        </div>
        <div class="project-body">
          <div class="project-kpis">
            <div class="kpi">
              <span class="kpi-value">4.8<span class="unit"> MWc</span></span>
              <span class="kpi-label" data-fr="Puissance" data-en="Power">Puissance</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">7.4<span class="unit"> GWh</span></span>
              <span class="kpi-label" data-fr="Production/an" data-en="Output/yr">Production/an</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">18<span class="unit"> mois</span></span>
              <span class="kpi-label" data-fr="Durée projet" data-en="Duration">Durée projet</span>
            </div>
          </div>
          <p class="project-desc" data-fr="Pilotage complet d'une centrale photovoltaïque au sol : étude de faisabilité, simulation PVSyst, dimensionnement HTA, coordination des sous-traitants, suivi chantier et mise en service." data-en="Complete management of a ground-mounted PV plant: feasibility study, PVSyst simulation, HV sizing, subcontractor coordination, site supervision and commissioning.">Pilotage complet d'une centrale photovoltaïque au sol : étude de faisabilité, simulation PVSyst, dimensionnement HTA, coordination des sous-traitants, suivi chantier et mise en service.</p>
          <div class="perf-bar-wrap">
            <div class="perf-label-row">
              <span class="perf-label" data-fr="Performance Ratio" data-en="Performance Ratio">Performance Ratio</span>
              <span class="perf-value">82%</span>
            </div>
            <div class="perf-bar"><div class="perf-fill" style="width:82%"></div></div>
          </div>
          <div class="project-tools" style="margin-top:1rem;">
            <span class="tool-chip">PVSyst</span>
            <span class="tool-chip">AutoCAD</span>
            <span class="tool-chip">HTA</span>
            <span class="tool-chip">SCADA</span>
          </div>
        </div>
      </div>
      
      <!-- Project 2 -->
      <div class="project-card fade-up">
        <div class="project-header">
          <span class="project-type type-rooftop" data-fr="Toiture industrielle" data-en="Industrial rooftop">Toiture industrielle</span>
          <div class="project-name" data-fr="Ombrière Parking & Toiture" data-en="Parking Canopy & Rooftop">Ombrière Parking & Toiture</div>
          <div class="project-location">📍 <span data-fr="Zone industrielle, Tunisie" data-en="Industrial zone, Tunisia">Zone industrielle, Tunisie</span></div>
        </div>
        <div class="project-body">
          <div class="project-kpis">
            <div class="kpi">
              <span class="kpi-value">850<span class="unit"> kWc</span></span>
              <span class="kpi-label" data-fr="Puissance" data-en="Power">Puissance</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">1.2<span class="unit"> GWh</span></span>
              <span class="kpi-label" data-fr="Production/an" data-en="Output/yr">Production/an</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">9<span class="unit"> mois</span></span>
              <span class="kpi-label" data-fr="Durée projet" data-en="Duration">Durée projet</span>
            </div>
          </div>
          <p class="project-desc" data-fr="Conception et supervision d'un système PV en autoconsommation avec injection surplus. Études de raccordement BT/HTA, gestion des interfaces avec le gestionnaire réseau et mise en place du monitoring." data-en="Design and supervision of a self-consumption PV system with surplus injection. LV/HV connection studies, interface management with the grid operator and monitoring setup.">Conception et supervision d'un système PV en autoconsommation avec injection surplus. Études de raccordement BT/HTA, gestion des interfaces avec le gestionnaire réseau et mise en place du monitoring.</p>
          <div class="perf-bar-wrap">
            <div class="perf-label-row">
              <span class="perf-label">Performance Ratio</span>
              <span class="perf-value">79%</span>
            </div>
            <div class="perf-bar"><div class="perf-fill" style="width:79%"></div></div>
          </div>
          <div class="project-tools" style="margin-top:1rem;">
            <span class="tool-chip">PVSyst</span>
            <span class="tool-chip">AutoCAD</span>
            <span class="tool-chip">BT/HTA</span>
            <span class="tool-chip">Monitoring</span>
          </div>
        </div>
      </div>
      
      <!-- Project 3 -->
      <div class="project-card fade-up">
        <div class="project-header">
          <span class="project-type type-agri" data-fr="Agrivoltaïsme" data-en="Agrivoltaics">Agrivoltaïsme</span>
          <div class="project-name" data-fr="Projet Agrivoltaïque — Irrigation Solaire" data-en="Agrivoltaic Project — Solar Irrigation">Projet Agrivoltaïque — Irrigation Solaire</div>
          <div class="project-location">📍 <span data-fr="Région agricole, Tunisie" data-en="Agricultural region, Tunisia">Région agricole, Tunisie</span></div>
        </div>
        <div class="project-body">
          <div class="project-kpis">
            <div class="kpi">
              <span class="kpi-value">320<span class="unit"> kWc</span></span>
              <span class="kpi-label" data-fr="Puissance" data-en="Power">Puissance</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">480<span class="unit"> MWh</span></span>
              <span class="kpi-label" data-fr="Production/an" data-en="Output/yr">Production/an</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">6<span class="unit"> mois</span></span>
              <span class="kpi-label" data-fr="Durée projet" data-en="Duration">Durée projet</span>
            </div>
          </div>
          <p class="project-desc" data-fr="Développement d'un projet innovant combinant production solaire et activité agricole. Optimisation de l'inclinaison des panneaux pour limiter l'impact sur les cultures, avec alimentation des pompes d'irrigation." data-en="Development of an innovative project combining solar production and agricultural activity. Panel tilt optimization to limit crop impact, with irrigation pump powering.">Développement d'un projet innovant combinant production solaire et activité agricole. Optimisation de l'inclinaison des panneaux pour limiter l'impact sur les cultures.</p>
          <div class="perf-bar-wrap">
            <div class="perf-label-row">
              <span class="perf-label">Performance Ratio</span>
              <span class="perf-value">76%</span>
            </div>
            <div class="perf-bar"><div class="perf-fill" style="width:76%"></div></div>
          </div>
          <div class="project-tools" style="margin-top:1rem;">
            <span class="tool-chip">PVSyst</span>
            <span class="tool-chip">AutoCAD</span>
            <span class="tool-chip">Agrivoltaïsme</span>
            <span class="tool-chip">Pompage</span>
          </div>
        </div>
      </div>
      
      <!-- Project 4 -->
      <div class="project-card fade-up">
        <div class="project-header">
          <span class="project-type type-industrial" data-fr="Multi-sites" data-en="Multi-sites">Multi-sites</span>
          <div class="project-name" data-fr="Programme Résidentiel Multi-sites" data-en="Multi-site Residential Programme">Programme Résidentiel Multi-sites</div>
          <div class="project-location">📍 <span data-fr="Plusieurs régions, Tunisie" data-en="Multiple regions, Tunisia">Plusieurs régions, Tunisie</span></div>
        </div>
        <div class="project-body">
          <div class="project-kpis">
            <div class="kpi">
              <span class="kpi-value">15<span class="unit">+ sites</span></span>
              <span class="kpi-label" data-fr="Installations" data-en="Installations">Installations</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">2.1<span class="unit"> MWc</span></span>
              <span class="kpi-label" data-fr="Total installé" data-en="Total installed">Total installé</span>
            </div>
            <div class="kpi">
              <span class="kpi-value">100<span class="unit">%</span></span>
              <span class="kpi-label" data-fr="Taux réussite" data-en="Success rate">Taux réussite</span>
            </div>
          </div>
          <p class="project-desc" data-fr="Gestion simultanée d'un programme de plus de 15 installations résidentielles et tertiaires. Standardisation des processus, gestion des sous-traitants et reporting centralisé." data-en="Simultaneous management of a programme of 15+ residential and commercial installations. Process standardization, subcontractor management and centralized reporting.">Gestion simultanée d'un programme de plus de 15 installations résidentielles et tertiaires. Standardisation des processus, gestion des sous-traitants et reporting centralisé.</p>
          <div class="perf-bar-wrap">
            <div class="perf-label-row">
              <span class="perf-label" data-fr="Taux de livraison dans les délais" data-en="On-time delivery rate">Taux de livraison dans les délais</span>
              <span class="perf-value">95%</span>
            </div>
            <div class="perf-bar"><div class="perf-fill" style="width:95%"></div></div>
          </div>
          <div class="project-tools" style="margin-top:1rem;">
            <span class="tool-chip">PVSyst</span>
            <span class="tool-chip">MS Project</span>
            <span class="tool-chip">Gestion ST</span>
            <span class="tool-chip">Reporting</span>
          </div>
        </div>
      </div>
      
    </div>
  </div>
</section>

<!-- ===== SKILLS ===== -->
<section id="skills" aria-label="Compétences">
  <div class="section-wrapper">
    <div class="fade-up">
      <div class="section-eyebrow" data-fr="Compétences" data-en="Skills">Compétences</div>
      <h2 class="section-title" data-fr="Expertise technique & managériale" data-en="Technical & managerial expertise">Expertise technique & managériale</h2>
    </div>
    
    <!-- Performance Circles -->
    <div class="perf-circles fade-up">
      <div class="circle-wrap">
        <svg width="100" height="100" class="circle-svg" viewBox="0 0 100 100">
          <circle class="circle-bg" cx="50" cy="50" r="45"/>
          <circle class="circle-fill fill-blue" cx="50" cy="50" r="45" data-pct="90"/>
          <text x="50" y="55" text-anchor="middle" class="circle-center">90%</text>
        </svg>
        <div class="circle-label" data-fr="Technique PV" data-en="PV Technical">Technique PV</div>
        <div class="circle-sublabel">PVSyst · HT/BT</div>
      </div>
      <div class="circle-wrap">
        <svg width="100" height="100" class="circle-svg" viewBox="0 0 100 100">
          <circle class="circle-bg" cx="50" cy="50" r="45"/>
          <circle class="circle-fill fill-green" cx="50" cy="50" r="45" data-pct="85"/>
          <text x="50" y="55" text-anchor="middle" class="circle-center">85%</text>
        </svg>
        <div class="circle-label" data-fr="Chef de Projet" data-en="Project Mgmt">Chef de Projet</div>
        <div class="circle-sublabel" data-fr="Planning · Budget" data-en="Schedule · Budget">Planning · Budget</div>
      </div>
      <div class="circle-wrap">
        <svg width="100" height="100" class="circle-svg" viewBox="0 0 100 100">
          <circle class="circle-bg" cx="50" cy="50" r="45"/>
          <circle class="circle-fill fill-blue" cx="50" cy="50" r="45" data-pct="88"/>
          <text x="50" y="55" text-anchor="middle" class="circle-center">88%</text>
        </svg>
        <div class="circle-label">AutoCAD</div>
        <div class="circle-sublabel" data-fr="Plans & câblage" data-en="Plans & wiring">Plans & câblage</div>
      </div>
      <div class="circle-wrap">
        <svg width="100" height="100" class="circle-svg" viewBox="0 0 100 100">
          <circle class="circle-bg" cx="50" cy="50" r="45"/>
          <circle class="circle-fill fill-gold" cx="50" cy="50" r="45" data-pct="80"/>
          <text x="50" y="55" text-anchor="middle" class="circle-center">80%</text>
        </svg>
        <div class="circle-label" data-fr="Raccordement" data-en="Grid connection">Raccordement</div>
        <div class="circle-sublabel">HTA · HTB</div>
      </div>
    </div>
    
    <div class="skills-layout">
      <div>
        <div class="skill-category-title" data-fr="⚡ Compétences Techniques" data-en="⚡ Technical Skills">⚡ Compétences Techniques</div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name">PVSyst — Simulation & Modélisation</span>
            <span class="skill-pct">92%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="92"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name">AutoCAD — Plans électriques & implantation</span>
            <span class="skill-pct">88%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="88"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name">Dimensionnement électrique HT/BT</span>
            <span class="skill-pct">90%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="90"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name">Études de raccordement réseau</span>
            <span class="skill-pct">82%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="82"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name" data-fr="Analyse de performance & SCADA" data-en="Performance analysis & SCADA">Analyse de performance & SCADA</span>
            <span class="skill-pct">78%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="78"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name" data-fr="Études de faisabilité technico-éco." data-en="Techno-economic feasibility studies">Études de faisabilité technico-éco.</span>
            <span class="skill-pct">85%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="85"></div></div>
        </div>
        
        <div style="margin-top:2rem;">
          <div class="skill-category-title" data-fr="🛠 Outils & Logiciels" data-en="🛠 Tools & Software">🛠 Outils & Logiciels</div>
          <div class="tools-grid">
            <div class="tool-badge"><span class="tool-badge-icon">☀️</span><span class="tool-badge-name">PVSyst</span></div>
            <div class="tool-badge"><span class="tool-badge-icon">📐</span><span class="tool-badge-name">AutoCAD</span></div>
            <div class="tool-badge"><span class="tool-badge-icon">📊</span><span class="tool-badge-name">MS Project</span></div>
            <div class="tool-badge"><span class="tool-badge-icon">📈</span><span class="tool-badge-name">Excel / VBA</span></div>
            <div class="tool-badge"><span class="tool-badge-icon">🖥️</span><span class="tool-badge-name">SCADA</span></div>
            <div class="tool-badge"><span class="tool-badge-icon">🗺️</span><span class="tool-badge-name">Google Earth</span></div>
            <div class="tool-badge"><span class="tool-badge-icon">📋</span><span class="tool-badge-name">SAP</span></div>
            <div class="tool-badge"><span class="tool-badge-icon">☁️</span><span class="tool-badge-name">Office 365</span></div>
          </div>
        </div>
      </div>
      
      <div>
        <div class="skill-category-title" data-fr="🎯 Gestion de Projets" data-en="🎯 Project Management">🎯 Gestion de Projets</div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name" data-fr="Planification & suivi de chantier" data-en="Scheduling & site monitoring">Planification & suivi de chantier</span>
            <span class="skill-pct">88%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="88"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name" data-fr="Gestion budgétaire & reporting" data-en="Budget management & reporting">Gestion budgétaire & reporting</span>
            <span class="skill-pct">85%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="85"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name" data-fr="Coordination sous-traitants" data-en="Subcontractor coordination">Coordination sous-traitants</span>
            <span class="skill-pct">90%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="90"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name" data-fr="Gestion des risques projet" data-en="Project risk management">Gestion des risques projet</span>
            <span class="skill-pct">80%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="80"></div></div>
        </div>
        
        <div class="skill-item">
          <div class="skill-row">
            <span class="skill-name" data-fr="Interface client & parties prenantes" data-en="Client & stakeholder interface">Interface client & parties prenantes</span>
            <span class="skill-pct">87%</span>
          </div>
          <div class="skill-bar"><div class="skill-fill" data-width="87"></div></div>
        </div>
        
        <div style="margin-top:2rem;">
          <div class="skill-category-title" data-fr="🤝 Compétences Transverses" data-en="🤝 Soft Skills">🤝 Compétences Transverses</div>
          <div class="soft-skills-grid">
            <div class="soft-skill-card">
              <span class="soft-icon">🎯</span>
              <span class="soft-name" data-fr="Leadership technique" data-en="Technical leadership">Leadership technique</span>
            </div>
            <div class="soft-skill-card">
              <span class="soft-icon">🔍</span>
              <span class="soft-name" data-fr="Analyse & synthèse" data-en="Analysis & synthesis">Analyse & synthèse</span>
            </div>
            <div class="soft-skill-card">
              <span class="soft-icon">🗣️</span>
              <span class="soft-name" data-fr="Communication" data-en="Communication">Communication</span>
            </div>
            <div class="soft-skill-card">
              <span class="soft-icon">⚡</span>
              <span class="soft-name" data-fr="Réactivité terrain" data-en="Field reactivity">Réactivité terrain</span>
            </div>
            <div class="soft-skill-card">
              <span class="soft-icon">🌍</span>
              <span class="soft-name" data-fr="Vision stratégique" data-en="Strategic vision">Vision stratégique</span>
            </div>
            <div class="soft-skill-card">
              <span class="soft-icon">🤝</span>
              <span class="soft-name" data-fr="Travail en équipe" data-en="Teamwork">Travail en équipe</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===== EDUCATION ===== -->
<section id="education" aria-label="Formation et certifications">
  <div class="section-wrapper">
    <div class="fade-up">
      <div class="section-eyebrow" data-fr="Formation" data-en="Education">Formation</div>
      <h2 class="section-title" data-fr="Diplômes & Certifications" data-en="Degrees & Certifications">Diplômes & Certifications</h2>
    </div>
    
    <div class="edu-grid">
      <div class="edu-card fade-up">
        <div class="edu-icon">🎓</div>
        <div class="edu-degree" data-fr="Diplôme National d'Ingénieur — Électrique Automatique" data-en="National Engineering Degree — Electrical Engineering & Automation">Diplôme National d'Ingénieur<br>Électrique Automatique</div>
        <div class="edu-institution" data-fr="École Nationale d'Ingénieurs" data-en="National Engineering School">École Nationale d'Ingénieurs</div>
        <div class="edu-year">2015 — 2019</div>
        <div class="edu-desc" data-fr="Formation d'excellence en génie électrique, automatique et systèmes d'énergie. Spécialisation progressive dans les énergies renouvelables et la conversion d'énergie." data-en="Excellence training in electrical engineering, automation and energy systems. Progressive specialization in renewable energies and energy conversion.">Formation d'excellence en génie électrique, automatique et systèmes d'énergie. Spécialisation progressive dans les énergies renouvelables et la conversion d'énergie.</div>
      </div>
      
      <div class="edu-card fade-up">
        <div class="edu-icon">☀️</div>
        <div class="edu-degree" data-fr="Formation Spécialisée — Systèmes Photovoltaïques" data-en="Specialized Training — Photovoltaic Systems">Formation Spécialisée<br>Systèmes Photovoltaïques</div>
        <div class="edu-institution" data-fr="Formation professionnelle continue" data-en="Continuing professional development">Formation professionnelle continue</div>
        <div class="edu-year">2020</div>
        <div class="edu-desc" data-fr="Dimensionnement, simulation PVSyst, études de raccordement, réglementation et normes applicables aux installations photovoltaïques de toutes puissances." data-en="Sizing, PVSyst simulation, grid connection studies, regulations and standards applicable to PV installations of all scales.">Dimensionnement, simulation PVSyst, études de raccordement, réglementation et normes applicables aux installations photovoltaïques de toutes puissances.</div>
        <div class="cert-badge">⭐ <span data-fr="Certifié PVSyst" data-en="PVSyst Certified">Certifié PVSyst</span></div>
      </div>
      
      <div class="edu-card fade-up">
        <div class="edu-icon">📋</div>
        <div class="edu-degree" data-fr="Gestion de Projets — Fondamentaux PMI" data-en="Project Management — PMI Fundamentals">Gestion de Projets<br>Fondamentaux PMI</div>
        <div class="edu-institution" data-fr="Formation e-learning certifiante" data-en="Certified e-learning course">Formation e-learning certifiante</div>
        <div class="edu-year">2021</div>
        <div class="edu-desc" data-fr="Méthodologies de gestion de projet : planification, gestion des risques, pilotage budgétaire, communication et clôture de projet selon le standard PMI/PMBOK." data-en="Project management methodologies: planning, risk management, budget control, communication and project closure per PMI/PMBOK standard.">Méthodologies de gestion de projet : planification, gestion des risques, pilotage budgétaire, communication et clôture de projet selon le standard PMI/PMBOK.</div>
      </div>
      
      <div class="edu-card fade-up">
        <div class="edu-icon">🔒</div>
        <div class="edu-degree" data-fr="Habilitations Électriques" data-en="Electrical Certifications">Habilitations Électriques</div>
        <div class="edu-institution" data-fr="Organisme certifié" data-en="Certified organization">Organisme certifié</div>
        <div class="edu-year" data-fr="En cours de mise à jour" data-en="Being updated">En cours de mise à jour</div>
        <div class="edu-desc" data-fr="Habilitations électriques pour travaux sur installations HT/BT : B2V, H0, BR — Indispensables pour la supervision de chantiers électriques photovoltaïques." data-en="Electrical certifications for HV/LV work: B2V, H0, BR — Essential for supervising photovoltaic electrical construction sites.">Habilitations électriques pour travaux sur installations HT/BT : B2V, H0, BR.</div>
        <div class="cert-badge">⚡ HT/BT</div>
      </div>
    </div>
  </div>
</section>

<!-- ===== TESTIMONIALS ===== -->
<section id="testimonials" aria-label="Témoignages">
  <div class="section-wrapper">
    <div class="fade-up">
      <div class="section-eyebrow" data-fr="Témoignages" data-en="Testimonials">Témoignages</div>
      <h2 class="section-title" data-fr="Ce que disent mes collaborateurs" data-en="What my colleagues say">Ce que disent mes collaborateurs</h2>
      <p class="section-desc" data-fr="Des recommandations de managers, clients et partenaires. Section en cours de complétion." data-en="Recommendations from managers, clients and partners. Section being completed.">Des recommandations de managers, clients et partenaires. Section en cours de complétion.</p>
    </div>
    
    <div class="testimonials-grid" style="margin-top:3rem;">
      
      <div class="testimonial-card">
        <div class="quote-mark">"</div>
        <p class="testimonial-text" data-fr="Radhouane a démontré une maîtrise technique exceptionnelle sur nos projets PV. Sa capacité à gérer simultanément les aspects études et terrain est remarquable. Un chef de projet fiable et rigoureux." data-en="Radhouane demonstrated exceptional technical mastery on our PV projects. His ability to simultaneously manage the study and field aspects is remarkable. A reliable and rigorous project manager.">Radhouane a démontré une maîtrise technique exceptionnelle sur nos projets PV. Sa capacité à gérer simultanément les aspects études et terrain est remarquable. Un chef de projet fiable et rigoureux.</p>
        <div class="testimonial-author">
          <div class="author-avatar">DM</div>
          <div>
            <div class="author-name">D. Mansouri</div>
            <div class="author-title" data-fr="Directeur Technique — Société d'Ingénierie" data-en="Technical Director — Engineering Company">Directeur Technique — Société d'Ingénierie</div>
          </div>
        </div>
      </div>
      
      <div class="testimonial-card placeholder">
        <div class="placeholder-icon">💬</div>
        <p class="placeholder-text" data-fr="Emplacement réservé pour votre témoignage.<br>Contactez Radhouane sur LinkedIn." data-en="Reserved space for your testimonial.<br>Contact Radhouane on LinkedIn.">Emplacement réservé pour votre témoignage.<br>Contactez-moi sur LinkedIn.</p>
      </div>
      
      <div class="testimonial-card placeholder">
        <div class="placeholder-icon">⭐</div>
        <p class="placeholder-text" data-fr="Emplacement réservé pour une recommandation client." data-en="Reserved space for a client recommendation.">Emplacement réservé pour une recommandation client.</p>
      </div>
      
    </div>
    
    <div style="text-align:center;margin-top:2rem;">
      <a href="https://www.linkedin.com/in/radhouanezayoud" target="_blank" class="btn-secondary">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"/><circle cx="4" cy="4" r="2"/></svg>
        <span data-fr="Voir toutes les recommandations LinkedIn" data-en="See all LinkedIn recommendations">Voir toutes les recommandations LinkedIn</span>
      </a>
    </div>
  </div>
</section>

<!-- ===== CONTACT ===== -->
<section id="contact" aria-label="Contact professionnel">
  <div class="section-wrapper">
    <div class="fade-up">
      <div class="section-eyebrow" data-fr="Prise de contact" data-en="Get in touch">Prise de contact</div>
      <h2 class="section-title" data-fr="Travaillons ensemble" data-en="Let's work together">Travaillons ensemble</h2>
    </div>
    
    <div class="contact-grid">
      <div class="contact-info fade-up">
        <p class="contact-intro" data-fr="Je suis actuellement à la recherche de nouvelles opportunités dans le secteur des énergies renouvelables. Si vous êtes un recruteur ou un directeur de projet à la recherche d'un Chef de Projets PV expérimenté, n'hésitez pas à me contacter." data-en="I am currently looking for new opportunities in the renewable energy sector. If you are a recruiter or project director looking for an experienced PV Project Manager, do not hesitate to contact me.">Je suis actuellement à la recherche de nouvelles opportunités dans le secteur des énergies renouvelables. Si vous êtes un recruteur ou un directeur de projet à la recherche d'un Chef de Projets PV expérimenté, n'hésitez pas à me contacter.</p>
        
        <div class="contact-methods">
          <a href="https://www.linkedin.com/in/radhouanezayoud" target="_blank" class="contact-method">
            <div class="contact-method-icon icon-linkedin">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="#0a66c2"><path d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"/><circle cx="4" cy="4" r="2"/></svg>
            </div>
            <div>
              <div class="contact-method-label">LinkedIn</div>
              <div class="contact-method-value">linkedin.com/in/radhouanezayoud</div>
            </div>
          </a>
          
          <a href="mailto:radhouane.zayoud@email.com" class="contact-method">
            <div class="contact-method-icon icon-email">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#3b82f6" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
            </div>
            <div>
              <div class="contact-method-label">Email</div>
              <div class="contact-method-value">radhouane.zayoud@email.com</div>
            </div>
          </a>
          
          <div class="contact-method">
            <div class="contact-method-icon icon-location">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#f59e0b" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
            </div>
            <div>
              <div class="contact-method-label" data-fr="Localisation" data-en="Location">Localisation</div>
              <div class="contact-method-value" data-fr="Tunisie — Mobilité France / Europe / International" data-en="Tunisia — Open to France / Europe / International">Tunisie — Mobilité France / Europe / International</div>
            </div>
          </div>
        </div>
        
        <div style="margin-top:2rem;">
          <a href="#" class="btn-primary" onclick="downloadCV()">
            ↓ <span data-fr="Télécharger CV complet (PDF)" data-en="Download full CV (PDF)">Télécharger CV complet (PDF)</span>
          </a>
        </div>
      </div>
      
      <div class="contact-form fade-up">
        <h3 class="form-title" data-fr="📬 Envoyer un message" data-en="📬 Send a message">📬 Envoyer un message</h3>
        <div class="form-grid">
          <div class="form-group">
            <label class="form-label" for="fname" data-fr="Prénom" data-en="First name">Prénom</label>
            <input class="form-input" type="text" id="fname" placeholder="Jean" autocomplete="given-name">
          </div>
          <div class="form-group">
            <label class="form-label" for="lname" data-fr="Nom" data-en="Last name">Nom</label>
            <input class="form-input" type="text" id="lname" placeholder="Dupont" autocomplete="family-name">
          </div>
          <div class="form-group full">
            <label class="form-label" for="company" data-fr="Entreprise" data-en="Company">Entreprise</label>
            <input class="form-input" type="text" id="company" placeholder="TotalEnergies, EDF Renouvelables..." autocomplete="organization">
          </div>
          <div class="form-group full">
            <label class="form-label" for="email">Email</label>
            <input class="form-input" type="email" id="email" placeholder="jean.dupont@totalenergies.com" autocomplete="email">
          </div>
          <div class="form-group full">
            <label class="form-label" for="subject" data-fr="Objet" data-en="Subject">Objet</label>
            <select class="form-select form-input" id="subject">
              <option value="" data-fr="Sélectionner..." data-en="Select...">Sélectionner...</option>
              <option value="recrutement" data-fr="Opportunité de recrutement" data-en="Recruitment opportunity">Opportunité de recrutement</option>
              <option value="mission" data-fr="Mission / Freelance" data-en="Mission / Freelance">Mission / Freelance</option>
              <option value="collaboration" data-fr="Collaboration / Partenariat" data-en="Collaboration / Partnership">Collaboration / Partenariat</option>
              <option value="autre" data-fr="Autre" data-en="Other">Autre</option>
            </select>
          </div>
          <div class="form-group full">
            <label class="form-label" for="message">Message</label>
            <textarea class="form-textarea" id="message" placeholder="Bonjour Radhouane, je souhaite discuter d'une opportunité..."></textarea>
          </div>
        </div>
        <button class="btn-primary form-submit" onclick="sendMessage()">
          ✉ <span data-fr="Envoyer le message" data-en="Send message">Envoyer le message</span>
        </button>
        <p id="form-success" style="display:none;margin-top:1rem;padding:0.75rem 1rem;background:rgba(16,185,129,0.1);border:1px solid rgba(16,185,129,0.3);border-radius:8px;font-size:0.85rem;color:var(--green-light);" data-fr="✅ Message envoyé ! Je vous répondrai dans les plus brefs délais." data-en="✅ Message sent! I will get back to you as soon as possible.">✅ Message envoyé ! Je vous répondrai dans les plus brefs délais.</p>
      </div>
    </div>
  </div>
</section>

<!-- ===== FOOTER ===== -->
<footer>
  <div class="footer-inner">
    <a href="#" class="footer-logo">R<span>.</span>Zayoud</a>
    
    <ul class="footer-links">
      <li><a href="#about" data-fr="Profil" data-en="Profile">Profil</a></li>
      <li><a href="#projects" data-fr="Projets" data-en="Projects">Projets</a></li>
      <li><a href="#skills" data-fr="Compétences" data-en="Skills">Compétences</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    
    <p class="footer-copy" data-fr="© 2025 Radhouane Zayoud — Chef de Projets Photovoltaïques" data-en="© 2025 Radhouane Zayoud — Photovoltaic Project Manager">© 2025 Radhouane Zayoud — Chef de Projets Photovoltaïques</p>
  </div>
</footer>

<script>
// ===== LANGUAGE SYSTEM =====
let currentLang = 'fr';

function setLang(lang) {
  currentLang = lang;
  document.querySelectorAll('[data-' + lang + ']').forEach(el => {
    const text = el.getAttribute('data-' + lang);
    if (text) el.innerHTML = text;
  });
  document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
  document.querySelector('.lang-btn[onclick="setLang(\'' + lang + '\')"]').classList.add('active');
  document.documentElement.lang = lang;
}

// ===== MOBILE MENU =====
function toggleMenu() {
  const links = document.getElementById('navLinks');
  links.classList.toggle('open');
}

// Close menu on link click
document.querySelectorAll('.nav-links a').forEach(link => {
  link.addEventListener('click', () => {
    document.getElementById('navLinks').classList.remove('open');
  });
});

// ===== SCROLL ANIMATIONS =====
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
      
      // Animate skill bars
      if (entry.target.classList.contains('skill-item')) {
        const fill = entry.target.querySelector('.skill-fill');
        if (fill) {
          setTimeout(() => {
            fill.style.width = fill.dataset.width + '%';
          }, 200);
        }
      }
    }
  });
}, { threshold: 0.1, rootMargin: '0px 0px -40px 0px' });

document.querySelectorAll('.fade-up, .timeline-item, .skill-item').forEach(el => {
  observer.observe(el);
});

// ===== SKILL BARS ANIMATION =====
const skillObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      const fills = entry.target.querySelectorAll('.skill-fill[data-width]');
      fills.forEach((fill, i) => {
        setTimeout(() => {
          fill.style.width = fill.dataset.width + '%';
        }, i * 100);
      });
      skillObserver.unobserve(entry.target);
    }
  });
}, { threshold: 0.2 });

document.querySelectorAll('.skills-layout').forEach(el => skillObserver.observe(el));

// ===== PERFORMANCE RATIO BARS =====
const perfObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      const fills = entry.target.querySelectorAll('.perf-fill');
      fills.forEach(fill => {
        // Width already set inline
      });
    }
  });
}, { threshold: 0.1 });

document.querySelectorAll('.project-card').forEach(el => perfObserver.observe(el));

// ===== CIRCLE ANIMATIONS =====
const circleObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      const circles = entry.target.querySelectorAll('.circle-fill[data-pct]');
      circles.forEach((circle, i) => {
        const pct = parseInt(circle.dataset.pct);
        const circumference = 283;
        const offset = circumference - (pct / 100) * circumference;
        setTimeout(() => {
          circle.style.strokeDashoffset = offset;
        }, i * 200);
      });
      circleObserver.unobserve(entry.target);
    }
  });
}, { threshold: 0.3 });

document.querySelectorAll('.perf-circles').forEach(el => circleObserver.observe(el));

// ===== CONTACT FORM =====
function sendMessage() {
  const fname = document.getElementById('fname').value;
  const email = document.getElementById('email').value;
  const message = document.getElementById('message').value;
  
  if (!fname || !email || !message) {
    alert(currentLang === 'fr' ? 'Veuillez remplir tous les champs obligatoires.' : 'Please fill in all required fields.');
    return;
  }
  
  // Simulate send (replace with actual email service like EmailJS or Formspree)
  const success = document.getElementById('form-success');
  success.style.display = 'block';
  success.innerHTML = currentLang === 'fr' 
    ? '✅ Message envoyé ! Je vous répondrai dans les plus brefs délais.'
    : '✅ Message sent! I will get back to you as soon as possible.';
  
  // Reset form
  setTimeout(() => {
    ['fname', 'lname', 'company', 'email', 'message'].forEach(id => {
      document.getElementById(id).value = '';
    });
    document.getElementById('subject').value = '';
  }, 1000);
}

// ===== CV DOWNLOAD =====
function downloadCV() {
  alert(currentLang === 'fr' 
    ? '📄 Remplacez ce fichier par votre CV PDF réel.\nPlacer votre CV en tant que "cv-radhouane-zayoud.pdf" dans le dossier du projet.'
    : '📄 Replace this with your actual PDF CV.\nPlace your CV as "cv-radhouane-zayoud.pdf" in the project folder.'
  );
  // Real implementation:
  // const link = document.createElement('a');
  // link.href = './cv-radhouane-zayoud.pdf';
  // link.download = 'CV-Radhouane-Zayoud-Chef-Projets-PV.pdf';
  // link.click();
}

// ===== TIMELINE STAGGERED ANIMATION =====
const timelineItems = document.querySelectorAll('.timeline-item');
const timelineObserver = new IntersectionObserver((entries) => {
  entries.forEach((entry, i) => {
    if (entry.isIntersecting) {
      setTimeout(() => {
        entry.target.classList.add('visible');
      }, 100);
    }
  });
}, { threshold: 0.1 });

timelineItems.forEach(item => timelineObserver.observe(item));

// ===== SMOOTH PARALLAX HERO =====
window.addEventListener('scroll', () => {
  const scrollY = window.scrollY;
  const heroGrid = document.querySelector('.hero-grid');
  if (heroGrid && scrollY < window.innerHeight) {
    heroGrid.style.transform = `translateY(${scrollY * 0.3}px)`;
  }
});

// ===== INIT =====
document.addEventListener('DOMContentLoaded', () => {
  // Trigger visible items in viewport immediately
  setTimeout(() => {
    document.querySelectorAll('.fade-up').forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight) {
        el.classList.add('visible');
      }
    });
  }, 100);
});
</script>
</body>
</html>
