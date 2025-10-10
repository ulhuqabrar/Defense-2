# STRIKE – Execute the Impossible

[Live Demo](https://abrarhackathon02.netlify.app)

---

## Project Overview

I built **STRIKE** as an interactive web platform to simulate a futuristic tech bootcamp experience. My goal with hackathon was to create a visually immersive and engaging environment where learners could explore advanced programming like DSA (Data Structures & Algorithms), and GenAI concepts.  

My main focus was on combining modern UI design, animations, and responsive layouts using only HTML and CSS.

---

## Features I Implemented

### Navy Radar Loader
I created an animated radar interface with rotating sweep and blip markers. This serves as a high-tech preloader, keeping users engaged while the main content loads.

### Hero Section
I designed 3D-style floating elements that feels like depth and motion. The hero section features a bold title, tagline, and a call-to-action button.

### Mission Objectives
I structured six key learning goals, each with an image, number label, and short description:
1. Master the algorithms
2. Deploy AI systems
3. Gain tactical advantage
4. Achieve mission success
5. Build intelligent systems
6. Become a tech commander  

 Made sure the layout was responsive and visually appealing.

### Operation Modules
Designed module cards for:
- **DSA OPS:** Array & String Manipulation, Linked Lists & Trees, Dynamic Programming, Graph Algorithms, System Design Patterns.
- **GENAI OPS:** Transformer Architecture, Prompt Engineering, Fine-tuning LLMs, Vector Databases, AI Agent Development.  

These cards clearly display module details and match the site’s futuristic theme.

### Elite Commanders
I also added profiles for instructors including name, role, biography, image, and social media links. This helped establish credibility and made the interface more engaging.

### Dynamic Statistics Tape
I implemented an infinite horizontal scrolling tape. I faced challenges ensuring smooth looping and seamless repetition, which I solved by duplicating contenr.

### Enrollment Form
I built a responsive enrollment form that collects name, profession, email, and mobile number while showing the course price. I styled it to match the dark, glassmorphic theme of the site.

---

## Challenges I Faced

- **Responsive Layouts:** Ensuring elements like headings and hero elements didn't overflow required careful use of `min-width`, `max-width`, and `inline-block` for dynamic content sizing.  
- **Animations:** Making floating elements, radar sweep, and scrolling tape feel smooth without performance drops was tricky. I optimized by using CSS animations and avoiding heavy JS.  
- **Glassmorphic Styling:** I had to balance blur, opacity, and shadow effects for readability while maintaining a futuristic aesthetic.

---

## Technologies I Used

- **HTML** – Semantic markup
- **CSS** – Flexbox/Grid, Glassmorphism, Animations
- **Responsive Design** – Mobile and desktop-friendly
- **Hosting** – [Netlify.com](https://app.netlify.com)

---

## How I Built Yhem

1. Set up the HTML structure for hero, objectives, modules, commanders, stats tape, and enrollment form.
2. Styled each section with CSS, implementing glassmorphic elements, responsive layouts, and animations.
3. Built the radar loader animation and floating geometric elements using only CSS.
4. Tested responsiveness across different screen sizes and fixed overflow issues by adjusting `inline-block` and `max-width`.
5. Deployed the finished site to Netlify for public access.

---

## Screenshots

**Hero Section**  
![Hero Section](./assets/screenshots/hero.png)

**Mission Objectives**  
![Mission Objectives](./assets/screenshots/mission.png)

**Operation Modules**  
![Modules](./assets/screenshots/modules.png)

**Elite Commanders**  
![Commanders](./assets/screenshots/commanders.png)

---

## What I Learned

- Advanced CSS techniques including glassmorphism and 3D floating animations.
- Responsive design strategies for text and image overflow.
- Designing a professional UI while keeping it lightweight and smooth.
- How to structure content for readability and engagement.

---

## Next Steps

- Adding backend integration for enrollment form submissions.
- Implementing more interactive animations for modules.
- Making the site fully mobile-optimized with enhanced touch interactions.

---
