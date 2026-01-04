<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Visit a Friend - Epic Adventure Game</title>
<link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">
<link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
<style>
:root {
--primary-color: #5D5CDE;
--secondary-color: #ff6b6b;
--accent-color: #4ecdc4;
--cursor-primary: #5D5CDE;
--cursor-secondary: #4ecdc4;
--dark-bg: #0f0f23;
--darker-bg: #0a0a1a;
--light-text: #ffffff;
--gray-text: #e8e8f0;
--gradient-1: linear-gradient(135deg, #5D5CDE 0%, #4ecdc4 100%);
--gradient-2: linear-gradient(135deg, #ff6b6b 0%, #5D5CDE 100%);
--gradient-3: linear-gradient(135deg, #4ecdc4 0%, #00f2fe 100%);
--gradient-4: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
--gradient-5: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
--gradient-6: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
--gradient-7: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
--gradient-8: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
--neon-glow: 0 0 30px rgba(93, 92, 222, 0.8);
--glass-bg: rgba(255, 255, 255, 0.1);
--glass-border: rgba(255, 255, 255, 0.2);
--blur-strong: blur(20px);
--blur-medium: blur(10px);
--blur-light: blur(5px);
}

* {
margin: 0;
padding: 0;
box-sizing: border-box;
}

html {
scroll-behavior: smooth;
font-size: 16px;
overflow-x: hidden;
}

body {
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
background: var(--dark-bg);
color: var(--light-text);
overflow-x: hidden;
line-height: 1.6;
position: relative;
cursor: none;
}

/* Hide scrollbars but keep functionality */
::-webkit-scrollbar {
width: 0px;
background: transparent;
}

::-webkit-scrollbar-thumb {
background: transparent;
}

/* Site Loading Animation */
.site-loader {
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: #000000;
z-index: 99999;
display: flex;
align-items: center;
justify-content: center;
transition: all 1s ease;
}

.site-loader.loaded {
opacity: 0;
visibility: hidden;
}

.ripple-effect {
position: absolute;
width: 50px;
height: 50px;
border-radius: 50%;
background: radial-gradient(circle, var(--primary-color), var(--accent-color));
transform: scale(0);
opacity: 0.8;
}

/* Revolutionary Zero-delay Cursor System */
.cursor {
position: fixed;
width: 30px;
height: 30px;
pointer-events: none;
z-index: 9999;
visibility: hidden;
background-image:
linear-gradient(to right, var(--cursor-primary) 10px, transparent 0),
linear-gradient(to bottom, var(--cursor-primary) 10px, transparent 0),
linear-gradient(to left, var(--cursor-primary) 10px, transparent 0),
linear-gradient(to bottom, var(--cursor-primary) 10px, transparent 0),
linear-gradient(to right, var(--cursor-primary) 10px, transparent 0),
linear-gradient(to top, var(--cursor-primary) 10px, transparent 0),
linear-gradient(to left, var(--cursor-primary) 10px, transparent 0),
linear-gradient(to top, var(--cursor-primary) 10px, transparent 0);
background-repeat: no-repeat;
background-position: top left, top left, top right, top right, bottom left,
bottom left, bottom right, bottom right;
background-size: 20px 2px, 2px 20px, 20px 2px, 2px 20px, 20px 2px, 2px 20px,
20px 2px, 2px 20px;
transition: none;
transform-origin: center center;
animation: cursorRotate 2.4s linear infinite;
opacity: 0.2; /* Dimmed down significantly */
}

@keyframes cursorRotate {
0% { transform: rotate(0deg); }
100% { transform: rotate(180deg); }
}

.cursor-dot {
position: fixed;
width: 6px;
height: 6px;
pointer-events: none;
z-index: 9999;
background: var(--cursor-secondary);
border-radius: 50%;
visibility: hidden;
transition: none;
box-shadow: 0 0 2px rgba(78, 205, 196, 0.06);
}

.cursor.hover-active {
--cursor-color: var(--secondary-color);
transform: scale(1.5) rotate(360deg);
filter: drop-shadow(0 0 20px rgba(255, 107, 107, 0.6));
animation: cursorHoverRotate 0.6s ease-out forwards;
opacity: 0.3; /* Still dimmed even when hovering */
}

.cursor-dot.hover-active {
background: var(--secondary-color);
transform: scale(1.8);
box-shadow: 0 0 4px rgba(255, 107, 107, 0.08);
}

@keyframes cursorHoverRotate {
0% { transform: scale(1) rotate(0deg); }
100% { transform: scale(1.5) rotate(360deg); }
}

/* Interactive Background */
.interactive-background {
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 100%;
z-index: -15;
background: var(--dark-bg);
transition: all 0.8s ease;
}

.gradient-overlay {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
opacity: 0.7;
transition: all 0.3s ease;
pointer-events: none;
background: radial-gradient(600px circle at var(--mouse-x, 50%) var(--mouse-y, 50%),
rgba(93, 92, 222, 0.6) 0%,
rgba(255, 107, 107, 0.4) 25%,
rgba(78, 205, 196, 0.3) 50%,
transparent 70%);
}

.gradient-overlay-2 {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
opacity: 0.3;
transition: all 0.5s ease;
pointer-events: none;
background: radial-gradient(800px circle at var(--mouse-x, 50%) var(--mouse-y, 50%),
rgba(78, 205, 196, 0.3) 0%,
rgba(93, 92, 222, 0.2) 40%,
transparent 70%);
}

/* Premium Glassmorphism Top Navigation - Fixed */
.top-nav {
position: fixed;
top: 20px;
left: 50%;
transform: translateX(-50%);
background: rgba(15, 15, 35, 0.9); /* More opaque background */
backdrop-filter: var(--blur-strong);
border: 1px solid rgba(93, 92, 222, 0.5); /* More visible border */
border-radius: 25px;
padding: 15px 30px;
z-index: 9998;
display: flex;
align-items: center;
gap: 30px;
transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5); /* Stronger shadow */
}

.top-nav:hover {
transform: translateX(-50%) translateY(-2px);
box-shadow: 0 15px 50px rgba(93, 92, 222, 0.4);
background: rgba(15, 15, 35, 0.95); /* Even more opaque on hover */
}

.nav-logo-top {
font-size: 1.4rem;
font-weight: 900;
background: linear-gradient(45deg, #ffffff, #5D5CDE, #ff6b6b, #4ecdc4);
background-size: 400% 400%;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
text-decoration: none;
animation: gradientShift 4s ease-in-out infinite;
position: relative;
}

.nav-logo-top::after {
content: '';
position: absolute;
bottom: -5px;
left: 50%;
transform: translateX(-50%);
width: 0;
height: 2px;
background: var(--gradient-1);
transition: width 0.4s ease;
}

.nav-logo-top:hover::after {
width: 100%;
}

@keyframes gradientShift {
0% { background-position: 0% 50%; }
50% { background-position: 100% 50%; }
100% { background-position: 0% 50%; }
}

.nav-links-top {
display: flex;
align-items: center;
gap: 25px;
list-style: none;
}

.nav-link-top {
color: var(--gray-text);
text-decoration: none;
font-weight: 500;
padding: 10px 18px;
border-radius: 15px;
transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
position: relative;
overflow: hidden;
}

.nav-link-top::before {
content: '';
position: absolute;
top: 0;
left: -100%;
width: 100%;
height: 100%;
background: var(--gradient-1);
transition: left 0.4s ease;
z-index: -1;
}

.nav-link-top:hover::before,
.nav-link-top.active::before {
left: 0;
}

.nav-link-top:hover,
.nav-link-top.active {
color: var(--light-text);
transform: translateY(-3px) scale(1.05);
box-shadow: 0 10px 30px rgba(93, 92, 222, 0.3);
}

/* Horizontal Progress Navigation */
.progress-nav {
position: fixed;
top: 80px;
left: 50%;
transform: translateX(-50%);
width: 90%;
max-width: 800px;
height: 6px;
background: rgba(255, 255, 255, 0.1);
border-radius: 10px;
z-index: 9997;
overflow: hidden;
backdrop-filter: var(--blur-medium);
box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
}

.progress-fill {
height: 100%;
background: var(--gradient-1);
border-radius: 10px;
width: 0%;
transition: width 0.3s ease;
box-shadow: 0 0 20px rgba(93, 92, 222, 0.6);
position: relative;
}

.progress-fill::after {
content: '';
position: absolute;
top: 0;
right: 0;
width: 20px;
height: 100%;
background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.5));
border-radius: 10px;
}

/* Hero Section */
.hero {
height: 100vh;
position: relative;
overflow: hidden;
display: flex;
align-items: center;
justify-content: center;
background: radial-gradient(circle at 30% 20%, rgba(93, 92, 222, 0.6) 0%, transparent 50%),
radial-gradient(circle at 70% 80%, rgba(255, 107, 107, 0.5) 0%, transparent 50%),
radial-gradient(circle at 40% 70%, rgba(78, 205, 196, 0.5) 0%, transparent 50%),
linear-gradient(135deg, var(--dark-bg) 0%, var(--darker-bg) 100%);
}

.hero-animated-bg {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(45deg,
rgba(93, 92, 222, 0.1),
rgba(255, 107, 107, 0.1),
rgba(78, 205, 196, 0.1),
rgba(93, 92, 222, 0.1));
background-size: 400% 400%;
animation: heroBackgroundShift 12s ease-in-out infinite;
z-index: 1;
}

@keyframes heroBackgroundShift {
0%, 100% { background-position: 0% 50%; }
25% { background-position: 100% 0%; }
50% { background-position: 100% 100%; }
75% { background-position: 0% 100%; }
}

.hero-particles {
position: absolute;
width: 100%;
height: 100%;
overflow: hidden;
z-index: 2;
}

.particle {
position: absolute;
background: radial-gradient(circle, rgba(93, 92, 222, 0.8), transparent);
border-radius: 50%;
animation: float 20s linear infinite;
pointer-events: none;
}

@keyframes float {
0% {
transform: translateY(100vh) translateX(0) rotate(0deg) scale(0);
opacity: 0;
}
5% {
opacity: 1;
transform: translateY(95vh) translateX(10px) rotate(18deg) scale(1);
}
95% {
opacity: 1;
transform: translateY(5vh) translateX(100px) rotate(342deg) scale(1);
}
100% {
transform: translateY(-5vh) translateX(200px) rotate(360deg) scale(0);
opacity: 0;
}
}

.hero-content {
position: relative;
z-index: 10;
text-align: center;
max-width: 1000px;
padding: 2rem;
transform: translateY(20px);
opacity: 0;
animation: heroContentReveal 1.5s ease 0.5s forwards;
}

@keyframes heroContentReveal {
to {
transform: translateY(0);
opacity: 1;
}
}

.hero-badge {
display: inline-flex;
align-items: center;
gap: 0.8rem;
padding: 1rem 2rem;
background: var(--glass-bg);
backdrop-filter: var(--blur-strong);
border: 1px solid var(--glass-border);
border-radius: 50px;
font-size: 1rem;
margin-bottom: 2rem;
color: var(--accent-color);
font-weight: 600;
animation: badgeGlow 3s ease-in-out infinite;
transition: transform 0.4s ease;
}

.hero-badge:hover {
transform: scale(1.05);
background: rgba(93, 92, 222, 0.2);
}

.hero-badge i {
font-size: 1.3rem;
color: var(--primary-color);
animation: iconSpin 4s linear infinite;
}

@keyframes iconSpin {
0% { transform: rotateY(0deg); }
100% { transform: rotateY(360deg); }
}

@keyframes badgeGlow {
0%, 100% { box-shadow: 0 0 10px rgba(93, 92, 222, 0.3); }
50% { box-shadow: 0 0 30px rgba(93, 92, 222, 0.7); }
}

.hero-title {
font-size: clamp(3.5rem, 10vw, 7rem);
font-weight: 900;
margin-bottom: 1.5rem;
background: linear-gradient(45deg, #ffffff, #5D5CDE, #ff6b6b, #4ecdc4, #ffd700);
background-size: 400% 400%;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
animation: gradientShift 4s ease-in-out infinite;
line-height: 1.1;
letter-spacing: -2px;
transition: transform 0.4s ease;
}

.hero-title:hover {
transform: scale(1.02);
}

.hero-subtitle {
font-size: clamp(1.3rem, 3.5vw, 2rem);
color: var(--gray-text);
margin-bottom: 3rem;
max-width: 700px;
margin-left: auto;
margin-right: auto;
font-weight: 400;
line-height: 1.6;
}

.play-now-btn {
display: inline-flex;
align-items: center;
gap: 1rem;
padding: 1.8rem 3.5rem;
font-size: 1.4rem;
font-weight: 700;
text-decoration: none;
color: var(--light-text);
background: var(--gradient-1);
border-radius: 50px;
position: relative;
overflow: hidden;
transition: all 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94);
box-shadow: 0 15px 40px rgba(93, 92, 222, 0.6);
text-transform: uppercase;
letter-spacing: 1px;
cursor: pointer;
border: none;
z-index: 1;
}

.play-now-btn::before {
content: '';
position: absolute;
top: 0;
left: -100%;
width: 100%;
height: 100%;
background: var(--gradient-2);
transition: left 0.5s ease;
z-index: -1;
}

.play-now-btn::after {
content: '';
position: absolute;
top: 50%;
left: 50%;
width: 0;
height: 0;
background: rgba(255, 255, 255, 0.3);
border-radius: 50%;
transform: translate(-50%, -50%);
transition: all 0.6s ease;
z-index: -1;
}

.play-now-btn:hover::before {
left: 0;
}

.play-now-btn:hover::after {
width: 300px;
height: 300px;
}

.play-now-btn:hover {
transform: translateY(-8px) scale(1.08);
box-shadow: 0 25px 60px rgba(93, 92, 222, 0.8);
}

.play-btn-icon {
font-size: 1.6rem;
animation: pulse 2s infinite;
}

@keyframes pulse {
0%, 100% { transform: scale(1); }
50% { transform: scale(1.15); }
}

/* Section Base Styles */
.section {
position: relative;
padding: 10rem 0;
overflow: hidden;
}

.section-animated-bg {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(135deg,
rgba(93, 92, 222, 0.2),
rgba(78, 205, 196, 0.15),
rgba(255, 107, 107, 0.15),
rgba(93, 92, 222, 0.2));
background-size: 400% 400%;
animation: sectionBackgroundShift 15s ease-in-out infinite;
z-index: 1;
}

@keyframes sectionBackgroundShift {
0%, 100% { background-position: 0% 50%; }
33% { background-position: 100% 0%; }
66% { background-position: 100% 100%; }
}

.container {
max-width: 1200px;
margin: 0 auto;
padding: 0 2rem;
position: relative;
z-index: 5;
}

.section-title {
text-align: center;
margin-bottom: 5rem;
}

.section-badge {
display: inline-flex;
align-items: center;
gap: 0.8rem;
padding: 0.8rem 2rem;
background: var(--glass-bg);
backdrop-filter: var(--blur-strong);
border: 1px solid var(--glass-border);
border-radius: 50px;
font-size: 1rem;
margin-bottom: 1.5rem;
color: var(--accent-color);
font-weight: 600;
animation: sectionBadgeFloat 6s ease-in-out infinite;
transition: transform 0.4s ease;
}

.section-badge:hover {
transform: scale(1.05);
background: rgba(93, 92, 222, 0.2);
}

@keyframes sectionBadgeFloat {
0%, 100% { transform: translateY(0); }
50% { transform: translateY(-10px); }
}

.section-badge i {
font-size: 1.2rem;
color: var(--primary-color);
animation: badgeIconRotate 8s linear infinite;
}

@keyframes badgeIconRotate {
0% { transform: rotateY(0deg); }
100% { transform: rotateY(360deg); }
}

.section-heading {
font-size: clamp(3rem, 6vw, 5rem);
font-weight: 900;
margin-bottom: 1.5rem;
background: linear-gradient(45deg, #ffffff, #5D5CDE, #4ecdc4);
background-size: 300% 300%;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
animation: gradientShift 5s ease-in-out infinite;
}

.section-subtitle {
font-size: 1.3rem;
color: var(--gray-text);
max-width: 700px;
margin: 0 auto;
font-weight: 400;
line-height: 1.7;
}

/* Statistics Section */
.stats-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
gap: 3rem;
margin-top: 5rem;
}

.stat-card {
background: var(--glass-bg);
backdrop-filter: var(--blur-strong);
border: 1px solid var(--glass-border);
border-radius: 25px;
padding: 3.5rem 2.5rem;
text-align: center;
transition: all 0.6s cubic-bezier(0.25, 0.46, 0.45, 0.94);
position: relative;
overflow: hidden;
}

.stat-card::before {
content: '';
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: conic-gradient(from 0deg, transparent, var(--primary-color), transparent);
animation: cardRotate 6s linear infinite;
opacity: 0;
transition: opacity 0.4s ease;
z-index: -1;
}

@keyframes cardRotate {
100% { transform: rotate(360deg); }
}

.stat-card::after {
content: '';
position: absolute;
top: 50%;
left: 50%;
width: 0;
height: 0;
background: radial-gradient(circle, rgba(93, 92, 222, 0.1), transparent);
border-radius: 50%;
transform: translate(-50%, -50%);
transition: all 0.6s ease;
z-index: -1;
}

.stat-card:hover::before {
opacity: 0.15;
}

.stat-card:hover::after {
width: 200px;
height: 200px;
}

.stat-card:hover {
transform: translateY(-15px) scale(1.05);
box-shadow: 0 30px 60px rgba(93, 92, 222, 0.6);
border-color: var(--primary-color);
background: rgba(93, 92, 222, 0.15);
}

.stat-icon {
font-size: 4rem;
color: var(--primary-color);
margin-bottom: 1.5rem;
animation: statIconFloat 4s ease-in-out infinite;
filter: drop-shadow(0 0 20px rgba(93, 92, 222, 0.7));
transition: transform 0.4s ease;
}

@keyframes statIconFloat {
0%, 100% { transform: translateY(0); }
50% { transform: translateY(-10px); }
}

.stat-card:hover .stat-icon {
transform: scale(1.2) rotateY(360deg);
}

.stat-number {
font-size: 3.5rem;
font-weight: 900;
color: var(--light-text);
display: block;
margin-bottom: 0.8rem;
background: linear-gradient(45deg, #ffffff, #5D5CDE);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
}

.stat-label {
font-size: 1.1rem;
color: var(--gray-text);
text-transform: uppercase;
letter-spacing: 1px;
font-weight: 600;
}

/* About Section */
.about-content-wrapper {
text-align: center;
margin-bottom: 5rem;
position: relative;
z-index: 5;
}

.about-content h2 {
font-size: clamp(2.5rem, 5vw, 4rem);
margin-bottom: 2.5rem;
background: var(--gradient-1);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
font-weight: 800;
line-height: 1.2;
}

.about-description {
max-width: 1000px;
margin: 0 auto;
}

.about-description p {
font-size: 1.3rem;
color: var(--gray-text);
margin-bottom: 2.5rem;
line-height: 1.8;
font-weight: 400;
}

.about-bottom-section {
display: grid;
grid-template-columns: 1fr 1fr;
gap: 5rem;
align-items: start;
margin-top: 5rem;
position: relative;
z-index: 5;
}

.about-features {
display: grid;
gap: 2rem;
}

.about-feature {
display: flex;
align-items: center;
gap: 1.5rem;
padding: 1.5rem;
background: var(--glass-bg);
backdrop-filter: var(--blur-medium);
border-radius: 15px;
transition: all 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94);
border: 1px solid transparent;
position: relative;
overflow: hidden;
}

.about-feature::before {
content: '';
position: absolute;
top: 0;
left: -100%;
width: 100%;
height: 100%;
background: linear-gradient(90deg, transparent, rgba(93, 92, 222, 0.1), transparent);
transition: left 0.6s ease;
}

.about-feature:hover::before {
left: 100%;
}

.about-feature:hover {
background: rgba(93, 92, 222, 0.2);
transform: translateX(15px) scale(1.03);
border-color: var(--primary-color);
box-shadow: 0 15px 40px rgba(93, 92, 222, 0.5);
}

.about-feature i {
font-size: 2rem;
color: var(--primary-color);
flex-shrink: 0;
transition: transform 0.4s ease;
}

.about-feature:hover i {
transform: rotateY(360deg) scale(1.2);
}

.about-feature h4 {
font-size: 1.2rem;
margin-bottom: 0.5rem;
font-weight: 700;
color: var(--light-text);
}

.about-feature p {
color: var(--gray-text);
margin: 0;
font-size: 1rem;
font-weight: 400;
}

.about-image {
position: relative;
border-radius: 25px;
overflow: hidden;
transition: all 0.6s cubic-bezier(0.25, 0.46, 0.45, 0.94);
width: 100%;
max-width: 600px;
box-shadow: 0 30px 80px rgba(0, 0, 0, 0.5);
}

.about-image::before {
content: '';
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(45deg, rgba(93, 92, 222, 0.2), transparent, rgba(255, 107, 107, 0.2));
z-index: 2;
opacity: 0;
transition: opacity 0.4s ease;
}

.about-image:hover::before {
opacity: 1;
}

.about-image:hover {
transform: scale(1.05);
box-shadow: 0 40px 100px rgba(93, 92, 222, 0.6);
}

.about-image img {
width: 100%;
height: auto;
object-fit: cover;
border-radius: 25px;
max-height: 500px;
transition: transform 0.6s ease;
}

.about-image:hover img {
transform: scale(1.1);
}

/* Gallery Section */
.carousel-section {
height: 500vh;
position: relative;
overflow: hidden;
}

.gallery-animated-bg {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(135deg,
rgba(255, 107, 107, 0.1),
rgba(78, 205, 196, 0.15),
rgba(93, 92, 222, 0.1),
rgba(255, 107, 107, 0.1));
background-size: 400% 400%;
animation: galleryBackgroundShift 20s ease-in-out infinite;
z-index: 1;
}

@keyframes galleryBackgroundShift {
0%, 100% { background-position: 0% 50%; }
20% { background-position: 100% 0%; }
40% { background-position: 100% 100%; }
60% { background-position: 0% 100%; }
80% { background-position: 0% 0%; }
}

.carousel-header {
height: 100vh;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
text-align: center;
position: relative;
z-index: 10;
}

.carousel-title {
font-size: clamp(3rem, 6vw, 5rem);
font-weight: 900;
margin-bottom: 1.5rem;
background: linear-gradient(45deg, #ffffff, #5D5CDE, #4ecdc4, #ff6b6b, #ffd700);
background-size: 400% 400%;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
animation: gradientShift 6s ease-in-out infinite;
transition: transform 0.4s ease;
}

.carousel-title:hover {
transform: scale(1.05);
}

.carousel-subtitle {
font-size: clamp(1.3rem, 3.5vw, 2rem);
color: var(--gray-text);
margin-bottom: 8rem;
font-weight: 400;
line-height: 1.6;
}

.scroll-indicator {
position: absolute;
bottom: 4rem;
left: 50%;
transform: translateX(-50%);
display: flex;
flex-direction: column;
align-items: center;
gap: 2rem;
color: var(--gray-text);
font-size: 1.1rem;
animation: bounce 3s infinite;
font-weight: 500;
}

@keyframes bounce {
0%, 20%, 50%, 80%, 100% {
transform: translateX(-50%) translateY(0);
}
40% {
transform: translateX(-50%) translateY(-20px);
}
60% {
transform: translateX(-50%) translateY(-10px);
}
}

.scroll-arrow {
font-size: 2.5rem;
color: var(--primary-color);
filter: drop-shadow(0 0 15px rgba(93, 92, 222, 0.8));
animation: arrowPulse 2s ease-in-out infinite;
}

@keyframes arrowPulse {
0%, 100% { transform: scale(1); }
50% { transform: scale(1.2); }
}

.gallery-section {
height: 400vh;
display: flex;
align-items: center;
justify-content: center;
position: relative;
}

.gallery-container {
position: sticky;
top: 50vh;
transform: translateY(-50%);
perspective: 2000px;
perspective-origin: center center;
width: 100%;
height: 100vh;
display: flex;
align-items: center;
justify-content: center;
}

.gallery-wheel {
position: relative;
width: 600px;
height: 600px;
transform-style: preserve-3d;
animation: rotateGallery linear;
animation-timeline: scroll(root);
animation-range: 15% 85%;
}

@keyframes rotateGallery {
0% { transform: rotateY(0deg) rotateX(0deg); }
50% { transform: rotateY(-900deg) rotateX(15deg); }
100% { transform: rotateY(-1800deg) rotateX(0deg); }
}

.gallery-item {
position: absolute;
width: 550px;
height: 500px;
left: 50%;
top: 50%;
transform-origin: center center;
background: rgba(15, 15, 30, 0.95);
border-radius: 25px;
overflow: hidden;
box-shadow: 0 40px 100px rgba(0, 0, 0, 0.8), 0 0 0 1px rgba(93, 92, 222, 0.7);
transition: all 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94);
backdrop-filter: var(--blur-strong);
border: 2px solid rgba(93, 92, 222, 0.8);
cursor: pointer;
}

.gallery-item::before {
content: '';
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(45deg, rgba(93, 92, 222, 0.1), transparent, rgba(255, 107, 107, 0.1));
z-index: 1;
opacity: 0;
transition: opacity 0.4s ease;
}

.gallery-item:hover::before {
opacity: 1;
}

.gallery-item:hover {
transform: translate(-50%, -50%) translateZ(300px) scale(1.2);
border-color: var(--primary-color);
box-shadow: 0 60px 150px rgba(93, 92, 222, 0.8);
}

.gallery-item:nth-child(1) { transform: translate(-50%, -50%) rotateY(0deg) translateZ(800px); }
.gallery-item:nth-child(2) { transform: translate(-50%, -50%) rotateY(51.43deg) translateZ(800px); }
.gallery-item:nth-child(3) { transform: translate(-50%, -50%) rotateY(102.86deg) translateZ(800px); }
.gallery-item:nth-child(4) { transform: translate(-50%, -50%) rotateY(154.29deg) translateZ(800px); }
.gallery-item:nth-child(5) { transform: translate(-50%, -50%) rotateY(205.71deg) translateZ(800px); }
.gallery-item:nth-child(6) { transform: translate(-50%, -50%) rotateY(257.14deg) translateZ(800px); }
.gallery-item:nth-child(7) { transform: translate(-50%, -50%) rotateY(308.57deg) translateZ(800px); }

.item-image {
width: 100%;
height: 420px;
object-fit: cover;
display: block;
border-radius: 25px 25px 0 0;
transition: all 0.6s ease;
position: relative;
z-index: 2;
}

.gallery-item:hover .item-image {
transform: scale(1.05);
filter: brightness(1.1) saturate(1.2);
}

.item-info {
padding: 20px 30px;
text-align: center;
background: linear-gradient(135deg, rgba(10, 10, 25, 0.98) 0%, rgba(93, 92, 222, 0.3) 100%);
border-radius: 0 0 25px 25px;
border-top: 1px solid rgba(93, 92, 222, 0.6);
height: 80px;
display: flex;
flex-direction: column;
justify-content: center;
position: relative;
z-index: 2;
}

.item-title {
font-size: 22px;
font-weight: 800;
margin-bottom: 5px;
background: linear-gradient(45deg, #ffffff, #5D5CDE, #4ecdc4);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
transition: all 0.3s ease;
}

.gallery-item:hover .item-title {
transform: scale(1.05);
}

.item-subtitle {
font-size: 14px;
color: var(--gray-text);
font-style: italic;
font-weight: 400;
transition: all 0.3s ease;
}

.gallery-item:hover .item-subtitle {
color: var(--light-text);
}

/* Features Section */
.features-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
gap: 3rem;
margin-top: 5rem;
position: relative;
z-index: 5;
}

.feature-card {
background: var(--glass-bg);
backdrop-filter: var(--blur-strong);
border: 1px solid var(--glass-border);
border-radius: 25px;
padding: 3.5rem;
text-align: center;
transition: all 0.6s cubic-bezier(0.25, 0.46, 0.45, 0.94);
position: relative;
overflow: hidden;
}

.feature-card::before {
content: '';
position: absolute;
top: -50%;
left: -50%;
width: 200%;
height: 200%;
background: conic-gradient(from 0deg, transparent, var(--primary-color), transparent);
animation: featureRotate 8s linear infinite;
opacity: 0;
transition: opacity 0.4s ease;
}

@keyframes featureRotate {
100% { transform: rotate(360deg); }
}

.feature-card::after {
content: '';
position: absolute;
top: 50%;
left: 50%;
width: 0;
height: 0;
background: radial-gradient(circle, rgba(93, 92, 222, 0.1), transparent);
border-radius: 50%;
transform: translate(-50%, -50%);
transition: all 0.6s ease;
z-index: -1;
}

.feature-card:hover::before {
opacity: 0.15;
}

.feature-card:hover::after {
width: 300px;
height: 300px;
}

.feature-card:hover {
transform: translateY(-15px) scale(1.05);
box-shadow: 0 30px 60px rgba(93, 92, 222, 0.6);
border-color: var(--primary-color);
background: rgba(93, 92, 222, 0.15);
}

.feature-icon {
font-size: 4.5rem;
color: var(--primary-color);
margin-bottom: 2rem;
animation: featureIconFloat 5s ease-in-out infinite;
filter: drop-shadow(0 0 20px rgba(93, 92, 222, 0.8));
transition: all 0.4s ease;
}

@keyframes featureIconFloat {
0%, 100% { transform: translateY(0); }
50% { transform: translateY(-15px); }
}

.feature-card:hover .feature-icon {
transform: scale(1.2) rotateY(360deg);
}

.feature-title {
font-size: 1.6rem;
font-weight: 700;
margin-bottom: 1.5rem;
background: linear-gradient(45deg, #ffffff, #5D5CDE);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
}

.feature-description {
color: var(--gray-text);
line-height: 1.8;
font-size: 1.1rem;
font-weight: 400;
}

/* Contact Section */
.contact-container {
max-width: 700px;
margin: 0 auto;
text-align: center;
position: relative;
z-index: 5;
}

.contact-content {
background: var(--glass-bg);
backdrop-filter: var(--blur-strong);
border: 1px solid var(--glass-border);
border-radius: 35px;
padding: 5rem;
margin-top: 4rem;
position: relative;
overflow: hidden;
transition: all 0.6s ease;
}

.contact-content::before {
content: '';
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(45deg, rgba(93, 92, 222, 0.1), transparent, rgba(255, 107, 107, 0.1));
opacity: 0;
transition: opacity 0.4s ease;
}

.contact-content:hover::before {
opacity: 1;
}

.contact-content:hover {
transform: scale(1.02);
box-shadow: 0 30px 80px rgba(93, 92, 222, 0.5);
background: rgba(93, 92, 222, 0.1);
}

.contact-avatar {
width: 150px;
height: 150px;
border-radius: 50%;
margin: 0 auto 2.5rem;
overflow: hidden;
border: 3px solid var(--primary-color);
box-shadow: 0 0 30px rgba(93, 92, 222, 0.8);
transition: all 0.6s ease;
position: relative;
}

.contact-avatar::before {
content: '';
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(45deg, transparent, rgba(93, 92, 222, 0.3), transparent);
animation: avatarShine 3s ease-in-out infinite;
}

@keyframes avatarShine {
0% { transform: translateX(-100%); }
100% { transform: translateX(100%); }
}

.contact-avatar:hover {
transform: scale(1.1) rotateY(360deg);
box-shadow: 0 0 50px rgba(93, 92, 222, 1);
}

.contact-avatar img {
width: 100%;
height: 100%;
object-fit: cover;
transition: transform 0.6s ease;
}

.contact-avatar:hover img {
transform: scale(1.1);
}

.contact-name {
font-size: 2.5rem;
margin-bottom: 0.8rem;
background: linear-gradient(45deg, #ffffff, #5D5CDE, #4ecdc4);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
font-weight: 800;
}

.contact-role {
color: var(--gray-text);
margin-bottom: 3rem;
font-size: 1.3rem;
font-weight: 400;
}

.contact-email {
display: inline-flex;
align-items: center;
gap: 1.5rem;
padding: 1.8rem 2.5rem;
background: rgba(93, 92, 222, 0.2);
backdrop-filter: var(--blur-medium);
border-radius: 20px;
font-size: 1.3rem;
color: var(--light-text);
text-decoration: none;
transition: all 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94);
border: 1px solid var(--primary-color);
font-weight: 500;
position: relative;
overflow: hidden;
}

.contact-email::before {
content: '';
position: absolute;
top: 0;
left: -100%;
width: 100%;
height: 100%;
background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
transition: left 0.6s ease;
}

.contact-email:hover::before {
left: 100%;
}

.contact-email:hover {
background: rgba(93, 92, 222, 0.4);
transform: translateY(-8px) scale(1.05);
box-shadow: 0 20px 50px rgba(93, 92, 222, 0.7);
}

.contact-email i {
font-size: 1.8rem;
color: var(--primary-color);
transition: transform 0.4s ease;
}

.contact-email:hover i {
transform: rotateY(360deg) scale(1.2);
}

/* Footer */
.footer {
background: linear-gradient(135deg, var(--darker-bg) 0%, var(--dark-bg) 100%);
padding: 5rem 0 2rem;
margin-top: 5rem;
position: relative;
overflow: hidden;
}

.footer::before {
content: '';
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 1px;
background: var(--gradient-1);
box-shadow: 0 0 20px rgba(93, 92, 222, 0.5);
}

.footer-content {
max-width: 1200px;
margin: 0 auto;
padding: 0 2rem;
text-align: center;
position: relative;
z-index: 5;
}

.footer-social {
display: flex;
justify-content: center;
gap: 2rem;
margin-bottom: 3rem;
flex-wrap: wrap;
}

.social-link {
display: flex;
align-items: center;
justify-content: center;
width: 60px;
height: 60px;
background: var(--glass-bg);
backdrop-filter: var(--blur-strong);
border: 1px solid var(--glass-border);
border-radius: 50%;
color: var(--light-text);
text-decoration: none;
font-size: 1.5rem;
transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
position: relative;
overflow: hidden;
}

.social-link::before {
content: '';
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: var(--gradient-1);
opacity: 0;
transition: opacity 0.3s ease;
border-radius: 50%;
}

.social-link::after {
content: '';
position: absolute;
top: 50%;
left: 50%;
width: 0;
height: 0;
background: rgba(255, 255, 255, 0.3);
border-radius: 50%;
transform: translate(-50%, -50%);
transition: all 0.4s ease;
}

.social-link:hover::before {
opacity: 1;
}

.social-link:hover::after {
width: 80px;
height: 80px;
}

.social-link:hover {
transform: translateY(-8px) scale(1.1) rotate(360deg);
box-shadow: 0 15px 40px rgba(93, 92, 222, 0.6);
border-color: var(--primary-color);
}

.social-link i {
position: relative;
z-index: 2;
transition: transform 0.4s ease;
}

.social-link:hover i {
transform: scale(1.2);
}

.footer-copyright {
color: var(--gray-text);
font-size: 1rem;
border-top: 1px solid rgba(255, 255, 255, 0.1);
padding-top: 2rem;
font-weight: 400;
position: relative;
}

.footer-copyright::before {
content: '';
position: absolute;
top: 0;
left: 50%;
transform: translateX(-50%);
width: 100px;
height: 1px;
background: var(--gradient-1);
box-shadow: 0 0 10px rgba(93, 92, 222, 0.5);
}

.footer-copyright strong {
color: var(--light-text);
font-weight: 600;
background: var(--gradient-1);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
}

/* Game Modal */
.game-modal {
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: rgba(0, 0, 0, 0.98);
backdrop-filter: var(--blur-strong);
z-index: 10000;
display: none;
align-items: center;
justify-content: center;
padding: 2rem;
animation: modalFadeIn 0.6s ease;
}

@keyframes modalFadeIn {
from {
opacity: 0;
backdrop-filter: blur(0px);
}
to {
opacity: 1;
backdrop-filter: var(--blur-strong);
}
}

.game-modal.active {
display: flex;
}

.game-container {
width: 100%;
max-width: 1400px;
height: 95vh;
background: linear-gradient(135deg, var(--dark-bg) 0%, var(--darker-bg) 100%);
border-radius: 25px;
overflow: hidden;
position: relative;
border: 2px solid var(--primary-color);
box-shadow: 0 0 80px rgba(93, 92, 222, 0.8);
transform: scale(0.8);
animation: modalGrowIn 0.6s ease 0.2s forwards;
}

@keyframes modalGrowIn {
to {
transform: scale(1);
}
}

.game-header {
display: flex;
justify-content: space-between;
align-items: center;
padding: 1.5rem 2.5rem;
background: rgba(10, 10, 26, 0.9);
backdrop-filter: var(--blur-medium);
border-bottom: 1px solid var(--glass-border);
}

.game-title {
font-size: 1.4rem;
font-weight: 700;
background: var(--gradient-1);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
}

.game-controls-header {
display: flex;
gap: 1rem;
align-items: center;
}

.game-control-btn {
width: 40px;
height: 40px;
border-radius: 50%;
border: 2px solid;
display: flex;
align-items: center;
justify-content: center;
font-size: 1.2rem;
cursor: pointer;
transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
background: var(--glass-bg);
backdrop-filter: var(--blur-medium);
position: relative;
overflow: hidden;
}

.game-control-btn::before {
content: '';
position: absolute;
top: 50%;
left: 50%;
width: 0;
height: 0;
border-radius: 50%;
transform: translate(-50%, -50%);
transition: all 0.3s ease;
}

.green-flag {
color: #4ecdc4;
border-color: #4ecdc4;
}

.green-flag::before {
background: rgba(78, 205, 196, 0.3);
}

.green-flag:hover::before {
width: 60px;
height: 60px;
}

.green-flag:hover {
transform: scale(1.1) rotate(360deg);
box-shadow: 0 0 20px rgba(78, 205, 196, 0.7);
}

.red-stop {
color: #ff6b6b;
border-color: #ff6b6b;
}

.red-stop::before {
background: rgba(255, 107, 107, 0.3);
}

.red-stop:hover::before {
width: 60px;
height: 60px;
}

.red-stop:hover {
transform: scale(1.1) rotate(360deg);
box-shadow: 0 0 20px rgba(255, 107, 107, 0.7);
}

.pause-btn {
color: #ffd700;
border-color: #ffd700;
}

.pause-btn::before {
background: rgba(255, 215, 0, 0.3);
}

.pause-btn:hover::before {
width: 60px;
height: 60px;
}

.pause-btn:hover {
transform: scale(1.1) rotate(360deg);
box-shadow: 0 0 20px rgba(255, 215, 0, 0.7);
}

.game-close {
font-size: 1.8rem;
cursor: pointer;
color: var(--gray-text);
transition: all 0.4s ease;
background: none;
border: none;
padding: 5px;
border-radius: 50%;
}

.game-close:hover {
color: var(--light-text);
transform: rotate(180deg) scale(1.2);
background: rgba(255, 107, 107, 0.2);
}

.game-content {
position: relative;
z-index: 10;
height: calc(100% - 80px);
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
text-align: center;
padding: 3rem;
}

.game-iframe-container {
width: 100%;
height: 100%;
max-width: 1000px;
max-height: 700px;
position: relative;
border-radius: 15px;
overflow: hidden;
box-shadow: 0 0 50px rgba(93, 92, 222, 0.6);
}

.game-iframe {
width: 100%;
height: 100%;
border: none;
border-radius: 15px;
opacity: 0;
transition: opacity 0.5s ease;
}

.game-iframe.loaded {
opacity: 1;
}

/* Enhanced Loading Screen */
.loading-overlay {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background: linear-gradient(135deg,
var(--dark-bg) 0%,
var(--darker-bg) 50%,
var(--dark-bg) 100%);
background-size: 400% 400%;
animation: loadingBackgroundShift 8s ease-in-out infinite;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
z-index: 1000;
transition: opacity 0.8s ease-out, visibility 0.8s ease-out;
overflow: hidden;
border-radius: 15px;
}

@keyframes loadingBackgroundShift {
0%, 100% { background-position: 0% 50%; }
50% { background-position: 100% 50%; }
}

.loading-overlay.hidden {
opacity: 0;
visibility: hidden;
}

.loading-particles {
position: absolute;
width: 100%;
height: 100%;
overflow: hidden;
z-index: 1;
}

.loading-particle {
position: absolute;
background: radial-gradient(circle, rgba(78, 205, 196, 0.8), rgba(93, 92, 222, 0.6), transparent);
border-radius: 50%;
animation: loadingParticleFloat linear infinite;
backdrop-filter: blur(2px);
border: 1px solid rgba(255, 255, 255, 0.2);
}

@keyframes loadingParticleFloat {
from {
transform: translateY(100vh) scale(0);
opacity: 0;
}
10% {
opacity: 1;
}
90% {
opacity: 1;
}
to {
transform: translateY(-100px) scale(1);
opacity: 0;
}
}

.loading-content {
text-align: center;
color: white;
position: relative;
z-index: 10;
max-width: 90vw;
padding: 2rem;
background: var(--glass-bg);
border-radius: 20px;
backdrop-filter: var(--blur-medium);
border: 1px solid var(--glass-border);
box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
animation: contentFadeIn 1s ease-out;
}

@keyframes contentFadeIn {
from {
opacity: 0;
transform: translateY(50px);
}
to {
opacity: 1;
transform: translateY(0);
}
}

.loading-title {
font-size: 3rem;
font-weight: 900;
margin-bottom: 1rem;
background: linear-gradient(45deg, #ffffff, #4ecdc4, #5D5CDE, #ff6b6b);
background-size: 400% 400%;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
background-clip: text;
animation: titleGlow 3s ease-in-out infinite, gradientShift 4s ease-in-out infinite;
text-shadow: 0 0 20px rgba(255, 255, 255, 0.5);
letter-spacing: 2px;
}

@keyframes titleGlow {
0%, 100% {
filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.8));
transform: scale(1);
}
50% {
filter: drop-shadow(0 0 25px rgba(78, 205, 196, 0.9));
transform: scale(1.05);
}
}

.loading-subtitle {
font-size: 1.4rem;
margin-bottom: 2rem;
color: var(--gray-text);
font-weight: 400;
animation: subtitlePulse 2s ease-in-out infinite;
}

@keyframes subtitlePulse {
0%, 100% {
opacity: 0.85;
transform: translateY(0);
}
50% {
opacity: 1;
transform: translateY(-2px);
}
}

.scratch-logo {
width: 120px;
height: 120px;
margin: 1rem auto;
animation: logoFloat 2s ease-in-out infinite;
background-image: url('https://upload.wikimedia.org/wikipedia/commons/f/fb/Scratch_3.0_logo.png');
background-size: contain;
background-repeat: no-repeat;
background-position: center;
filter: drop-shadow(0 4px 8px rgba(0,0,0,0.3));
}

@keyframes logoFloat {
0%, 20%, 50%, 80%, 100% {
transform: translateY(0);
}
40% {
transform: translateY(-20px);
}
60% {
transform: translateY(-10px);
}
}

.loading-spinner {
width: 60px;
height: 60px;
border: 4px solid rgba(255,255,255,0.3);
border-top: 4px solid var(--primary-color);
border-radius: 50%;
animation: spin 1s linear infinite;
margin: 0 auto 1.5rem;
}

@keyframes spin {
0% { transform: rotate(0deg); }
100% { transform: rotate(360deg); }
}

.loading-progress {
width: 300px;
height: 6px;
background: rgba(255,255,255,0.2);
border-radius: 3px;
overflow: hidden;
margin: 1rem auto;
}

.loading-progress-bar {
width: 0%;
height: 100%;
background: var(--gradient-1);
border-radius: 3px;
transition: width 0.3s ease-out;
box-shadow: 0 0 10px rgba(93, 92, 222, 0.7);
animation: progressGradientShift 2s ease-in-out infinite;
}

@keyframes progressGradientShift {
0% { background-position: 0% 0%; }
50% { background-position: 100% 0%; }
100% { background-position: 0% 0%; }
}

/* Responsive Design */
@media (max-width: 1024px) {
.top-nav {
padding: 12px 20px;
gap: 20px;
}

.nav-links-top {
gap: 15px;
}

.nav-link-top {
padding: 8px 14px;
font-size: 0.9rem;
}

.about-bottom-section {
grid-template-columns: 1fr;
gap: 4rem;
}

.features-grid {
grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
gap: 2.5rem;
}

.gallery-item {
width: 450px;
height: 380px;
}

.gallery-item:nth-child(1) { transform: translate(-50%, -50%) rotateY(0deg) translateZ(650px); }
.gallery-item:nth-child(2) { transform: translate(-50%, -50%) rotateY(51.43deg) translateZ(650px); }
.gallery-item:nth-child(3) { transform: translate(-50%, -50%) rotateY(102.86deg) translateZ(650px); }
.gallery-item:nth-child(4) { transform: translate(-50%, -50%) rotateY(154.29deg) translateZ(650px); }
.gallery-item:nth-child(5) { transform: translate(-50%, -50%) rotateY(205.71deg) translateZ(650px); }
.gallery-item:nth-child(6) { transform: translate(-50%, -50%) rotateY(257.14deg) translateZ(650px); }
.gallery-item:nth-child(7) { transform: translate(-50%, -50%) rotateY(308.57deg) translateZ(650px); }
}

@media (max-width: 768px) {
.top-nav {
top: 15px;
padding: 10px 15px;
gap: 15px;
}

.nav-logo-top {
font-size: 1.2rem;
}

.nav-links-top {
gap: 10px;
}

.nav-link-top {
padding: 6px 10px;
font-size: 0.8rem;
}

.progress-nav {
top: 65px;
width: 95%;
}

.carousel-section {
height: 350vh;
}

.gallery-item {
width: 380px;
height: 320px;
}

.gallery-item:nth-child(1) { transform: translate(-50%, -50%) rotateY(0deg) translateZ(500px); }
.gallery-item:nth-child(2) { transform: translate(-50%, -50%) rotateY(51.43deg) translateZ(500px); }
.gallery-item:nth-child(3) { transform: translate(-50%, -50%) rotateY(102.86deg) translateZ(500px); }
.gallery-item:nth-child(4) { transform: translate(-50%, -50%) rotateY(154.29deg) translateZ(500px); }
.gallery-item:nth-child(5) { transform: translate(-50%, -50%) rotateY(205.71deg) translateZ(500px); }
.gallery-item:nth-child(6) { transform: translate(-50%, -50%) rotateY(257.14deg) translateZ(500px); }
.gallery-item:nth-child(7) { transform: translate(-50%, -50%) rotateY(308.57deg) translateZ(500px); }

.stats-grid {
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 2rem;
}

.features-grid {
grid-template-columns: 1fr;
gap: 2rem;
}

.feature-card {
padding: 2.5rem;
}

.contact-content {
padding: 3rem;
}

.footer-social {
gap: 1.5rem;
}

.social-link {
width: 50px;
height: 50px;
font-size: 1.3rem;
}

.loading-progress {
width: 250px;
}

.scratch-logo {
width: 90px;
height: 90px;
}
}

@media (max-width: 480px) {
.carousel-section {
height: 300vh;
}

.gallery-item {
width: 320px;
height: 280px;
}

.gallery-item:nth-child(1) { transform: translate(-50%, -50%) rotateY(0deg) translateZ(420px); }
.gallery-item:nth-child(2) { transform: translate(-50%, -50%) rotateY(51.43deg) translateZ(420px); }
.gallery-item:nth-child(3) { transform: translate(-50%, -50%) rotateY(102.86deg) translateZ(420px); }
.gallery-item:nth-child(4) { transform: translate(-50%, -50%) rotateY(154.29deg) translateZ(420px); }
.gallery-item:nth-child(5) { transform: translate(-50%, -50%) rotateY(205.71deg) translateZ(420px); }
.gallery-item:nth-child(6) { transform: translate(-50%, -50%) rotateY(257.14deg) translateZ(420px); }
.gallery-item:nth-child(7) { transform: translate(-50%, -50%) rotateY(308.57deg) translateZ(420px); }

.contact-content {
padding: 2rem;
}

.footer-social {
gap: 1rem;
}

.social-link {
width: 45px;
height: 45px;
font-size: 1.2rem;
}

.loading-progress {
width: 200px;
}
}

/* Reduced motion preferences */
@media (prefers-reduced-motion: reduce) {
.gradient-overlay,
.gradient-overlay-2 {
transition: none;
animation: none;
}

.hero-animated-bg,
.section-animated-bg,
.gallery-animated-bg {
animation: none;
}

.cursor {
animation: none;
}

.particle,
.loading-particle {
animation: none;
}

.hero-badge i,
.section-badge i {
animation: none;
}

.stat-icon,
.feature-icon {
animation: none;
}
}
</style>
</head>
<body>
<!-- Site Loading Animation -->
<div class="site-loader" id="site-loader">
<div class="ripple-effect" id="ripple-effect"></div>
</div>

<!-- Interactive Background -->
<div class="interactive-background">
<div class="gradient-overlay"></div>
<div class="gradient-overlay-2"></div>
</div>

<!-- Zero-delay Cursor -->
<div class="cursor" id="cursor"></div>
<div class="cursor-dot" id="cursor-dot"></div>

<!-- Premium Glassmorphism Top Navigation -->
<nav class="top-nav" id="top-nav">
<a href="#home" class="nav-logo-top">Visit a Friend</a>
<ul class="nav-links-top">
<li><a href="#home" class="nav-link-top active">Home</a></li>
<li><a href="#stats" class="nav-link-top">Stats</a></li>
<li><a href="#about" class="nav-link-top">About</a></li>
<li><a href="#gallery" class="nav-link-top">Gallery</a></li>
<li><a href="#features" class="nav-link-top">Features</a></li>
<li><a href="#contact" class="nav-link-top">Contact</a></li>
</ul>
</nav>

<!-- Horizontal Progress Navigation -->
<div class="progress-nav">
<div class="progress-fill" id="progress-fill"></div>
</div>

<!-- Main Content -->
<main class="main">
<!-- Hero Section -->
<section class="hero" id="home">
<div class="hero-animated-bg"></div>
<div class="hero-particles" id="hero-particles"></div>

<div class="hero-content">
<div class="hero-badge">
<i class='bx bx-joystick'></i>
Epic Adventure Game
</div>

<h1 class="hero-title">Visit a Friend</h1>

<p class="hero-subtitle">
Experience a unique handcrafted adventure RPG where every choice matters, time runs out, and your decisions determine survival in this remarkable Scratch masterpiece.
</p>

<button class="play-now-btn" id="play-btn">
<i class='bx bx-play play-btn-icon'></i>
Play Now
</button>
</div>
</section>

<!-- Statistics Section -->
<section class="section" id="stats">
<div class="section-animated-bg"></div>
<div class="container">
<div class="section-title">
<div class="section-badge">
<i class='bx bx-bar-chart-alt-2'></i>
Game Statistics
</div>
<h2 class="section-heading">Incredible Numbers</h2>
<p class="section-subtitle">See the amazing statistics behind this epic adventure game</p>
</div>

<div class="stats-grid">
<div class="stat-card">
<i class='bx bx-group stat-icon'></i>
<span class="stat-number" data-target="500">0</span>
<p class="stat-label">Community Views</p>
</div>
<div class="stat-card">
<i class='bx bx-time stat-icon'></i>
<span class="stat-number" data-target="600">0</span>
<p class="stat-label">Hours Spent</p>
</div>
<div class="stat-card">
<i class='bx bx-code-block stat-icon'></i>
<span class="stat-number" data-target="30000">0</span>
<p class="stat-label">Scratch Blocks</p>
</div>
<div class="stat-card">
<i class='bx bx-brush stat-icon'></i>
<span class="stat-number" data-target="4000">0</span>
<p class="stat-label">Hand-Drawn Sprites</p>
</div>
</div>
</div>
</section>

<!-- About Section -->
<section class="section" id="about">
<div class="section-animated-bg"></div>
<div class="container">
<div class="about-content-wrapper">
<div class="about-content">
<div class="section-badge">
<i class='bx bx-scroll'></i>
About the Game
</div>
<h2>A Handcrafted RPG Adventure</h2>
</div>

<div class="about-description">
<p>
Visit a Friend is a unique adventure RPG where every choice matters and time is your enemy. Navigate through multiple endings based on your decisions, with each path leading to dramatically different outcomes.
</p>
<p>
This handcrafted masterpiece features over 4,000 hand-drawn sprites and 30,000+ Scratch blocks, creating an immersive world where player choice affects survival. Race against time as you solve puzzles, battle challenging bosses, and make critical decisions.
</p>
<p>
Every sprite, every environment, and every interaction has been meticulously crafted by hand, giving the game a distinctive aesthetic that sets it apart from other Scratch projects.
</p>
</div>
</div>

<div class="about-bottom-section">
<div class="about-features">
<div class="about-feature">
<i class='bx bx-time-five'></i>
<div>
<h4>Time-Critical Decisions</h4>
<p>Every second counts in your survival journey</p>
</div>
</div>
<div class="about-feature">
<i class='bx bx-palette'></i>
<div>
<h4>Hand-Drawn Art</h4>
<p>Unique artistic style with thousands of sprites</p>
</div>
</div>
<div class="about-feature">
<i class='bx bx-shuffle'></i>
<div>
<h4>Multiple Endings</h4>
<p>Your choices shape the story outcome</p>
</div>
</div>
</div>

<div class="about-image">
<img src="https://pfst.cf2.poecdn.net/base/image/7488566c15a0356ef37587c0c200fbf2efa148b95c6c5257f2869bd4f27e9503?w=478&h=357" alt="Visit a Friend Game Screenshot">
</div>
</div>
</div>
</section>

<!-- Gallery Section -->
<section class="carousel-section" id="gallery">
<div class="gallery-animated-bg"></div>
<div class="carousel-header">
<div class="section-badge">
<i class='bx bx-images'></i>
Game Gallery
</div>
<h2 class="carousel-title">Experience the Journey</h2>
<p class="carousel-subtitle">Immersive 3D Game Gallery • Scroll-Driven Magic</p>

<div class="scroll-indicator">
<span>Scroll to explore</span>
<i class='bx bx-down-arrow-alt scroll-arrow'></i>
</div>
</div>

<div class="gallery-section">
<div class="gallery-container">
<div class="gallery-wheel">
<div class="gallery-item">
<img src="https://pfst.cf2.poecdn.net/base/image/20c1fc5f2a8634ef72a899484a6556b46e3d2b6b925c21f2473b2072b6488e92?w=1210&h=909" alt="The Shop" class="item-image">
<div class="item-info">
<h3 class="item-title">The Shop</h3>
<p class="item-subtitle">Essential supplies for survival</p>
</div>
</div>

<div class="gallery-item">
<img src="https://pfst.cf2.poecdn.net/base/image/822bbc9abd253f80bbea7f911df369a4ddac96831833a122440089bdd6d151dc?w=1209&h=901" alt="The Outside" class="item-image">
<div class="item-info">
<h3 class="item-title">The Outside</h3>
<p class="item-subtitle">Take in the fresh air</p>
</div>
</div>

<div class="gallery-item">
<img src="https://pfst.cf2.poecdn.net/base/image/33298cc1db50fd21daf7c3bb2754427cbe614e3f138a5b480c6b7b39ed657be0?w=482&h=355" alt="Friend's Room" class="item-image">
<div class="item-info">
<h3 class="item-title">Friend's Room</h3>
<p class="item-subtitle">A cozy place filled with memories</p>
</div>
</div>

<div class="gallery-item">
<img src="https://pfst.cf2.poecdn.net/base/image/ab4ef859e6059227424f4f5319df2398ddf4ce01634a1d573f0a632120ffa5b8?w=1204&h=914" alt="Boss Battle" class="item-image">
<div class="item-info">
<h3 class="item-title">Boss Battle</h3>
<p class="item-subtitle">Face the ultimate challenge</p>
</div>
</div>

<div class="gallery-item">
<img src="https://pfst.cf2.poecdn.net/base/image/d2570a0d14d3aaaacddcd3c9d9980016b00a0a75bd3f84ade3e9470131253df9?w=1213&h=909" alt="The Cave" class="item-image">
<div class="item-info">
<h3 class="item-title">The Cave</h3>
<p class="item-subtitle">Where mysteries live</p>
</div>
</div>

<div class="gallery-item">
<img src="https://pfst.cf2.poecdn.net/base/image/f8c290e60c15f1fde3210a57c463223cbdfceb49bf796acb32c77e62f11e2e8a?w=475&h=354" alt="Golden Discovery" class="item-image">
<div class="item-info">
<h3 class="item-title">Golden Discovery</h3>
<p class="item-subtitle">Hold E to take the treasure</p>
</div>
</div>

<div class="gallery-item">
<img src="https://pfst.cf2.poecdn.net/base/image/90a63298e67eca8d28c2493f845b290d077f6b9bfd30b6d79638d6d45ab27d75?w=469&h=345" alt="Meeting Friends" class="item-image">
<div class="item-info">
<h3 class="item-title">Meeting Friends</h3>
<p class="item-subtitle">Thanks for coming over</p>
</div>
</div>
</div>
</div>
</div>
</section>

<!-- Features Section -->
<section class="section" id="features">
<div class="section-animated-bg"></div>
<div class="container">
<div class="section-title">
<div class="section-badge">
<i class='bx bx-star'></i>
Game Features
</div>
<h2 class="section-heading">What Makes It Special</h2>
<p class="section-subtitle">Discover the incredible features that make Visit a Friend an unforgettable experience</p>
</div>

<div class="features-grid">
<div class="feature-card">
<i class='bx bx-git-branch feature-icon'></i>
<h3 class="feature-title">Multiple Endings</h3>
<p class="feature-description">Experience different outcomes based on your choices. Every decision you make leads to unique story paths and dramatically different endings.</p>
</div>

<div class="feature-card">
<i class='bx bx-timer feature-icon'></i>
<h3 class="feature-title">Time-Based Gameplay</h3>
<p class="feature-description">Race against time to complete your objectives. Strategic time management is crucial as every second counts in your survival.</p>
</div>

<div class="feature-card">
<i class='bx bx-shield-quarter feature-icon'></i>
<h3 class="feature-title">Challenging Boss Fights</h3>
<p class="feature-description">Face formidable bosses that require strategy, skill, and quick thinking. Each encounter tests your mastery of the game mechanics.</p>
</div>

<div class="feature-card">
<i class='bx bx-palette feature-icon'></i>
<h3 class="feature-title">Handcrafted Sprites</h3>
<p class="feature-description">Every single sprite in the game is hand-drawn, creating a unique artistic style that sets this adventure apart from other Scratch games.</p>
</div>

<div class="feature-card">
<i class='bx bx-heart feature-icon'></i>
<h3 class="feature-title">Choice-Driven Survival</h3>
<p class="feature-description">Your decisions directly impact your character's survival. Think carefully - wrong choices can lead to game over in this intense RPG experience.</p>
</div>

<div class="feature-card">
<i class='bx bx-group feature-icon'></i>
<h3 class="feature-title">Community Engagement</h3>
<p class="feature-description">Join an active community of players sharing strategies, experiences, and discoveries. Connect with fellow adventurers on this epic journey.</p>
</div>
</div>
</div>
</section>

<!-- Contact Section -->
<section class="section" id="contact">
<div class="section-animated-bg"></div>
<div class="container">
<div class="section-title">
<div class="section-badge">
<i class='bx bx-user'></i>
Meet the Developer
</div>
<h2 class="section-heading">Behind the Magic</h2>
<p class="section-subtitle">Get to know the creative mind behind Visit a Friend</p>
</div>

<div class="contact-container">
<div class="contact-content">
<div class="contact-avatar">
<img src="https://pfst.cf2.poecdn.net/base/image/8033769d6b4da2dcbe660d6a195e72544cfbd422c8d25d936f2db29e1679c45a?w=55&h=56" alt="Cyscination Profile">
</div>

<h3 class="contact-name">Cyscination</h3>
<p class="contact-role">Game Developer & Creative Director</p>

<div style="margin-bottom: 2rem;">
<h4 style="margin-bottom: 1.5rem; font-size: 1.3rem; color: var(--light-text);">Get in Touch</h4>
<a href="mailto:cyscination@gmail.com" class="contact-email">
<i class='bx bx-envelope'></i>
cyscination@gmail.com
</a>
</div>
</div>
</div>
</div>
</section>
</main>

<!-- Footer -->
<footer class="footer">
<div class="footer-content">
<div class="footer-social">
<a href="https://github.com/cyscination" class="social-link" title="GitHub">
<i class='bx bxl-github'></i>
</a>
<a href="https://discord.gg/visitafriend" class="social-link" title="Discord">
<i class='bx bxl-discord-alt'></i>
</a>
<a href="https://instagram.com/cyscination" class="social-link" title="Instagram">
<i class='bx bxl-instagram'></i>
</a>
<a href="https://twitter.com/cyscination" class="social-link" title="Twitter">
<i class='bx bxl-twitter'></i>
</a>
<a href="https://youtube.com/cyscination" class="social-link" title="YouTube">
<i class='bx bxl-youtube'></i>
</a>
<a href="mailto:cyscination@gmail.com" class="social-link" title="Email">
<i class='bx bx-envelope'></i>
</a>
</div>
<div class="footer-copyright">
Copyright © 2025 <strong>Visit a Friend</strong>. Crafted with passion by <strong>Cyscination</strong>.
</div>
</div>
</footer>

<!-- Game Modal -->
<div class="game-modal" id="game-modal">
<div class="game-container">
<div class="game-header">
<h3 class="game-title">Visit a Friend - Scratch Game</h3>
<div class="game-controls-header">
<div class="game-control-btn green-flag" id="green-flag" title="Start Game">
<i class='bx bx-play'></i>
</div>
<div class="game-control-btn red-stop" id="red-stop" title="Stop Game">
<i class='bx bx-stop'></i>
</div>
<div class="game-control-btn pause-btn" id="pause-btn" title="Pause/Resume">
<i class='bx bx-pause'></i>
</div>
</div>
<button class="game-close" id="game-close">
<i class='bx bx-x'></i>
</button>
</div>

<div class="game-content">
<div class="game-iframe-container">
<div class="loading-overlay" id="loading-overlay">
<div class="loading-particles" id="loading-particles"></div>
<div class="loading-content">
<div class="loading-title">Visit a Friend</div>
<div class="loading-subtitle">Preparing your adventure...</div>
<div class="scratch-logo"></div>
<div class="loading-spinner"></div>
<div class="loading-progress">
<div class="loading-progress-bar" id="loading-progress-bar"></div>
</div>
</div>
</div>

<iframe
class="game-iframe"
id="game-iframe"
src=""
allowfullscreen>
</iframe>
</div>
</div>
</div>
</div>

<script>
// Advanced Site Loading Animation
function initSiteLoader() {
const siteLoader = document.getElementById('site-loader');
const rippleEffect = document.getElementById('ripple-effect');

// Create multiple ripples for enhanced effect
for (let i = 0; i < 3; i++) {
const ripple = rippleEffect.cloneNode(true);
ripple.style.animationDelay = `${i * 0.2}s`;
siteLoader.appendChild(ripple);
}

// Animate ripple expansion
gsap.set(rippleEffect, { scale: 0, opacity: 0.8 });
gsap.to(rippleEffect, {
scale: 60,
opacity: 0,
duration: 1.8,
ease: "power2.out",
onComplete: () => {
siteLoader.classList.add('loaded');
document.body.style.overflow = 'auto';
setTimeout(initializeWebsite, 300);
}
});
}

// Revolutionary Zero-delay Cursor System
const cursor = document.getElementById('cursor');
const cursorDot = document.getElementById('cursor-dot');
const gradientOverlay = document.querySelector('.gradient-overlay');
const gradientOverlay2 = document.querySelector('.gradient-overlay-2');

let mouseX = 0, mouseY = 0;
let cursorX = 0, cursorY = 0;
let cursorDotX = 0, cursorDotY = 0;
let isOverTarget = false;

function updateCursor() {
// Zero delay for perfect tracking
cursorX = mouseX;
cursorY = mouseY;
cursorDotX = mouseX;
cursorDotY = mouseY;

cursor.style.left = cursorX - 15 + 'px';
cursor.style.top = cursorY - 15 + 'px';
cursorDot.style.left = cursorDotX - 3 + 'px';
cursorDot.style.top = cursorDotY - 3 + 'px';

requestAnimationFrame(updateCursor);
}

document.addEventListener('mousemove', (e) => {
mouseX = e.clientX;
mouseY = e.clientY;

// Show cursors instantly
cursor.style.visibility = 'visible';
cursorDot.style.visibility = 'visible';

// Update interactive background with enhanced smoothness
const x = (mouseX / window.innerWidth) * 100;
const y = (mouseY / window.innerHeight) * 100;
gradientOverlay.style.setProperty('--mouse-x', x + '%');
gradientOverlay.style.setProperty('--mouse-y', y + '%');
gradientOverlay2.style.setProperty('--mouse-x', x + '%');
gradientOverlay2.style.setProperty('--mouse-y', y + '%');
});

updateCursor();

// Enhanced cursor interactions with better effects
const interactiveElements = document.querySelectorAll(
'button, a, .stat-card, .feature-card, .gallery-item, .about-feature, .nav-link-top, .contact-email, .play-now-btn, .hero-badge, .section-badge, .social-link, .game-control-btn'
);

interactiveElements.forEach(element => {
element.addEventListener('mouseenter', () => {
isOverTarget = true;
cursor.classList.add('hover-active');
cursorDot.classList.add('hover-active');

// Enhanced scale animation
gsap.to(cursor, {
scale: 1.5,
duration: 0.3,
ease: "power2.out"
});
});

element.addEventListener('mouseleave', () => {
isOverTarget = false;
cursor.classList.remove('hover-active');
cursorDot.classList.remove('hover-active');

// Reset scale
gsap.to(cursor, {
scale: 1,
duration: 0.3,
ease: "power2.out"
});
});
});

// Advanced Navigation Progress
function updateNavigationProgress() {
const scrollTop = window.pageYOffset;
const docHeight = document.body.scrollHeight - window.innerHeight;
const scrollPercent = Math.min((scrollTop / docHeight) * 100, 100);

gsap.to('#progress-fill', {
width: scrollPercent + '%',
duration: 0.1,
ease: "none"
});
}

// Enhanced Active Navigation Links
function updateActiveNavLink() {
const sections = document.querySelectorAll('section[id]');
const navLinks = document.querySelectorAll('.nav-link-top');

let current = '';
sections.forEach(section => {
const sectionTop = section.offsetTop - 150;
const sectionHeight = section.clientHeight;
if (window.pageYOffset >= sectionTop && window.pageYOffset < sectionTop + sectionHeight) {
current = section.getAttribute('id');
}
});

navLinks.forEach(link => {
link.classList.remove('active');
if (link.getAttribute('href') === '#' + current) {
link.classList.add('active');
}
});
}

// Enhanced Hero Particles with more variety
function createParticles() {
const particlesContainer = document.getElementById('hero-particles');
if (!particlesContainer) return;

const particleCount = 100;
const colors = [
'rgba(93, 92, 222, 0.8)',
'rgba(255, 107, 107, 0.7)',
'rgba(78, 205, 196, 0.8)',
'rgba(255, 215, 0, 0.6)'
];

for (let i = 0; i < particleCount; i++) {
const particle = document.createElement('div');
particle.className = 'particle';
particle.style.left = Math.random() * 100 + '%';
const size = Math.random() * 20 + 3;
particle.style.width = size + 'px';
particle.style.height = size + 'px';
particle.style.background = `radial-gradient(circle, ${colors[i % colors.length]}, transparent)`;
particle.style.animationDelay = (i * 0.2 + Math.random() * 15) + 's';
particle.style.animationDuration = (Math.random() * 10 + 15) + 's';

particlesContainer.appendChild(particle);
}
}

// Enhanced Stats Counter Animation with better timing
function animateCounters() {
const counters = document.querySelectorAll('.stat-number');
const cards = document.querySelectorAll('.stat-card');

cards.forEach((card, index) => {
gsap.to(card, {
delay: index * 0.2,
duration: 0.8,
y: 0,
opacity: 1,
ease: "power2.out"
});
});

counters.forEach((counter, index) => {
const target = parseInt(counter.getAttribute('data-target'));


gsap.to({ value: 0 }, {
value: target,
duration: 2.5,
delay: index * 0.3,
ease: "power2.out",
onUpdate: function() {
counter.textContent = Math.floor(this.targets()[0].value).toLocaleString() + '+';
}
});
});
}

// Stats observer with enhanced trigger
const statsSection = document.getElementById('stats');
if (statsSection) {
const statsObserver = new IntersectionObserver((entries) => {
entries.forEach(entry => {
if (entry.isIntersecting && entry.intersectionRatio > 0.3) {
setTimeout(animateCounters, 300);
statsObserver.disconnect();
}
});
}, { threshold: [0.3, 0.5, 0.7] });

statsObserver.observe(statsSection);
}

// Enhanced Game Modal System
const playBtn = document.getElementById('play-btn');
const gameModal = document.getElementById('game-modal');
const gameClose = document.getElementById('game-close');
const gameIframe = document.getElementById('game-iframe');
const loadingOverlay = document.getElementById('loading-overlay');
const loadingProgressBar = document.getElementById('loading-progress-bar');

const greenFlag = document.getElementById('green-flag');
const redStop = document.getElementById('red-stop');
const pauseBtn = document.getElementById('pause-btn');

let loadingTimeout;
let currentProgress = 0;
let targetProgress = 0;
let isPaused = false;

const turbowarpUrl = 'https://turbowarp.org/975276757/embed';

// Enhanced loading screen with particles
function createLoadingParticles() {
const particlesContainer = document.getElementById('loading-particles');
if (!particlesContainer) return;

particlesContainer.innerHTML = '';
const particleCount = 60;
const colors = [
'rgba(78, 205, 196, 0.8)',
'rgba(93, 92, 222, 0.7)',
'rgba(255, 107, 107, 0.6)',
'rgba(255, 215, 0, 0.5)'
];

for (let i = 0; i < particleCount; i++) {
const particle = document.createElement('div');
particle.className = 'loading-particle';

const size = Math.random() * 80 + 40;
const leftPosition = Math.random() * 100;
const duration = Math.random() * 15 + 10;
const color = colors[i % colors.length];

particle.style.cssText = `
width: ${size}px;
height: ${size}px;
left: ${leftPosition}%;
animation-duration: ${duration}s;
animation-delay: ${Math.random() * 3}s;
background: radial-gradient(circle, ${color}, transparent);
border: 1px solid rgba(255, 255, 255, 0.2);
`;

particlesContainer.appendChild(particle);
}
}

function updateProgress(newProgress) {
targetProgress = Math.min(newProgress, 100);

gsap.to({ progress: currentProgress }, {
progress: targetProgress,
duration: 0.5,
ease: "power2.out",
onUpdate: function() {
currentProgress = this.targets()[0].progress;
loadingProgressBar.style.width = currentProgress + '%';
}
});
}

function simulateProgress() {
const stages = [20, 35, 50, 65, 80, 95];
stages.forEach((progress, index) => {
setTimeout(() => updateProgress(progress), (index + 1) * 1000);
});
}

function hideLoadingScreen() {
updateProgress(100);
setTimeout(() => {
loadingOverlay.classList.add('hidden');
gameIframe.classList.add('loaded');
}, 800);
}

// Enhanced game controls with better feedback
function startGame() {
try {
const iframeDoc = gameIframe.contentDocument || gameIframe.contentWindow.document;
const greenFlagBtn = iframeDoc.querySelector('.green-flag, [class*="green-flag"], [title*="green flag" i]');
if (greenFlagBtn) {
greenFlagBtn.click();
gsap.to(greenFlag, { scale: 0.8, duration: 0.1, yoyo: true, repeat: 1 });
}
} catch (e) {
console.log('Unable to control game directly');
}
}

function stopGame() {
try {
const iframeDoc = gameIframe.contentDocument || gameIframe.contentWindow.document;
const stopBtn = iframeDoc.querySelector('.stop-button, [class*="stop"], [title*="stop" i]');
if (stopBtn) {
stopBtn.click();
gsap.to(redStop, { scale: 0.8, duration: 0.1, yoyo: true, repeat: 1 });
}
} catch (e) {
console.log('Unable to control game directly');
}
}

function pauseGame() {
isPaused = !isPaused;
pauseBtn.innerHTML = isPaused ? '<i class="bx bx-play"></i>' : '<i class="bx bx-pause"></i>';
gsap.to(pauseBtn, { scale: 0.8, duration: 0.1, yoyo: true, repeat: 1 });
}

if (greenFlag) greenFlag.addEventListener('click', startGame);
if (redStop) redStop.addEventListener('click', stopGame);
if (pauseBtn) pauseBtn.addEventListener('click', pauseGame);

// Enhanced play button with better animation
if (playBtn) {
playBtn.addEventListener('click', () => {
// Button click animation
gsap.to(playBtn, {
scale: 0.95,
duration: 0.1,
yoyo: true,
repeat: 1,
ease: "power2.inOut"
});

setTimeout(() => {
gameModal.classList.add('active');
document.body.style.overflow = 'hidden';

// Ensure cursor is visible when modal opens
cursor.style.visibility = 'visible';
cursorDot.style.visibility = 'visible';

gameIframe.src = turbowarpUrl;
createLoadingParticles();

// Reset states
currentProgress = 0;
targetProgress = 0;
loadingProgressBar.style.width = '0%';
loadingOverlay.classList.remove('hidden');
gameIframe.classList.remove('loaded');

gameIframe.addEventListener('load', () => {
clearTimeout(loadingTimeout);
updateProgress(85);
setTimeout(hideLoadingScreen, 2000);
});

simulateProgress();
loadingTimeout = setTimeout(hideLoadingScreen, 12000);
}, 200);
});
}

function closeGameModal() {
gameModal.classList.remove('active');
document.body.style.overflow = 'auto';
gameIframe.src = '';
clearTimeout(loadingTimeout);
}

if (gameClose) gameClose.addEventListener('click', closeGameModal);

gameModal.addEventListener('click', (e) => {
if (e.target === gameModal) closeGameModal();
});

// Enhanced smooth scrolling with better easing
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
anchor.addEventListener('click', function (e) {
e.preventDefault();
const target = document.querySelector(this.getAttribute('href'));
if (target) {
gsap.to(window, {
duration: 1.4,
scrollTo: { y: target, offsetY: 80 },
ease: "power2.inOut"
});
}
});
});

// Enhanced keyboard navigation
document.addEventListener('keydown', (e) => {
if (e.key === 'Escape' && gameModal && gameModal.classList.contains('active')) {
closeGameModal();
}
});

// Enhanced ripple click effects
document.querySelectorAll('button, .nav-link-top, .contact-email, .gallery-item, .social-link').forEach(element => {
element.addEventListener('click', function(e) {
const ripple = document.createElement('span');
const rect = this.getBoundingClientRect();
const size = Math.max(rect.width, rect.height) * 1.5;
const x = e.clientX - rect.left - size / 2;
const y = e.clientY - rect.top - size / 2;

ripple.style.cssText = `
position: absolute;
width: ${size}px;
height: ${size}px;
left: ${x}px;
top: ${y}px;
background: radial-gradient(circle, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0.1));
border-radius: 50%;
transform: scale(0);
animation: enhancedRipple 0.8s ease-out;
pointer-events: none;
z-index: 1000;
`;

this.appendChild(ripple);

setTimeout(() => {
ripple.remove();
}, 800);
});
});

// Enhanced ripple animation
const rippleStyle = document.createElement('style');
rippleStyle.textContent = `
@keyframes enhancedRipple {
0% {
transform: scale(0);
opacity: 1;
}
50% {
opacity: 0.8;
}
100% {
transform: scale(1);
opacity: 0;
}
}
`;
document.head.appendChild(rippleStyle);

// Master scroll event handler with enhanced performance
let ticking = false;
function handleScroll() {
if (!ticking) {
requestAnimationFrame(() => {
updateNavigationProgress();
updateActiveNavLink();
ticking = false;
});
ticking = true;
}
}

window.addEventListener('scroll', handleScroll, { passive: true });

// Enhanced initialization on page load
function initializeWebsite() {
createParticles();
updateNavigationProgress();
updateActiveNavLink();

// Enhanced initial animations with better timing
const timeline = gsap.timeline();

timeline
.from('.hero-content', {
y: 80,
opacity: 0,
duration: 1.2,
ease: "power2.out"
})
.from('.top-nav', {
y: -60,
opacity: 0,
duration: 0.8,
ease: "power2.out"
}, "-=0.8")
.from('.progress-nav', {
scaleX: 0,
duration: 0.8,
ease: "power2.out"
}, "-=0.4")
.from('.hero-particles .particle', {
scale: 0,
opacity: 0,
duration: 1,
stagger: 0.02,
ease: "power2.out"
}, "-=1");

console.log('🚀 Visit a Friend - Ultimate Website v4.0 loaded successfully!');
console.log('✨ Features: Zero-delay Cursor, Enhanced Animations, Perfect Hover Effects');
}

// Start the enhanced loading animation
document.addEventListener('DOMContentLoaded', () => {
document.body.style.overflow = 'hidden';
setTimeout(initSiteLoader, 200);
});

// Enhanced error handling and performance optimization
window.addEventListener('error', (e) => {
console.warn('Non-critical error handled:', e.message);
});

// Enhanced performance monitoring
let lastScrollTime = 0;
const throttleScroll = (func, limit) => {
let inThrottle;
return function() {
const args = arguments;
const context = this;
if (!inThrottle) {
func.apply(context, args);
inThrottle = true;
setTimeout(() => inThrottle = false, limit);
}
}
};

// Apply throttling to scroll handler
window.addEventListener('scroll', throttleScroll(handleScroll, 8), { passive: true });

// Enhanced resize handler for responsive behavior
let resizeTimeout;
window.addEventListener('resize', () => {
clearTimeout(resizeTimeout);
resizeTimeout = setTimeout(() => {
updateNavigationProgress();
}, 250);
});

// Enhanced touch support for mobile devices
let touchStartX = 0;
let touchStartY = 0;

document.addEventListener('touchstart', (e) => {
touchStartX = e.touches[0].clientX;
touchStartY = e.touches[0].clientY;
}, { passive: true });

document.addEventListener('touchmove', (e) => {
// Enable custom touch behaviors if needed
}, { passive: true });

// Enhanced accessibility improvements
document.addEventListener('keydown', (e) => {
// Enhanced keyboard navigation
switch(e.key) {
case 'Tab':
// Custom tab navigation enhancements
break;
case 'Enter':
case ' ':
if (e.target.tagName === 'A' || e.target.tagName === 'BUTTON') {
e.target.click();
}
break;
}
});

// Final performance optimization
const performanceObserver = new PerformanceObserver((list) => {
list.getEntries().forEach((entry) => {
if (entry.entryType === 'measure') {
console.log(`Performance: ${entry.name} took ${entry.duration}ms`);
}
});
});

try {
performanceObserver.observe({ entryTypes: ['measure'] });
} catch (e) {
// Performance API not supported
}

</script>
</body>
</html>
