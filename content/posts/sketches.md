+++
date = '2025-11-01T18:57:52+01:00'
draft = false
title = 'From sketch to viz'
+++
In this presentation, I share how I come up with ideas and what inspires me. It’s basically about how things never quite go the way I expect them to.

<!--more-->

<style>
table {
  width: 100%;
  border-collapse: collapse;
  table-layout: fixed;  /* keeps columns aligned */
}

table td {
  text-align: left;
  vertical-align: top;
  padding: 0.5rem;
}

/* 👇 apply a fixed size only to cells that have an image */
table td:has(img) {
  height: 300px;        /* fixed height for image cells */
}

/* make text cells auto-height */
table td:not(:has(img)) {
  height: auto;
}

/* image styling */
table img {
  width: 100%;
  max-width: 250px;
  height: 100%;
  max-height: 100%;
  object-fit: contain;    
  background-color: #f8f8f8;
  border-radius: 6px;
  display: block;
  margin: 0 auto;
}

/* general image styling in posts */
.post-content img {
  display: block;
  max-width: 100%;
  height: auto;
  margin: 1rem auto;
  border-radius: 5px;
  box-shadow: 0 3px 12px rgba(0,0,0,.1);
}

.screenshot-collage {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  justify-content: center;
  margin: 2rem 0;
}

.screenshot-collage img {
  max-width: 300px;              /* smaller size */
  height: auto;                  /* keep proportions */
  object-fit: contain;           /* no cropping */
  border-radius: 10px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.25);
  background-color: #fff;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.screenshot-collage img.tilt-left {
  transform: rotate(-4deg);
}

.screenshot-collage img.tilt-right {
  transform: rotate(3deg);
}

.highlight {
  background-color: #fff59d;   /* or your brand color */
  padding: 0.2em 0.4em;
  border-radius: 3px;
}



/* Optional: responsive tweak */
@media (max-width: 600px) {
  .screenshot-collage img {
    width: 100%;
    max-width: 300px;
  }
}
</style>

## 1. Think about the problem your reader might have

When I started my Political Science master’s in Poland, my entrance exam was an oral test on… Polish politics. I passed, but only after cramming a 700-page book in a month and memorizing every politician, party, and scandal.

I’m a visual thinker, so I tried to picture this chaos of parties bumping into each other in my head because everything online looked like… this 👇 and made me even more confused.

<img src="/website/images/lewica-0.png" alt="Sketch" style="width:400px; border-radius:8px; display:block; margin:1rem auto;">

Fast-forward to 2025: when I learned my friend was writing a big piece about Polish politics, I convinced his newsroom they needed a visualization because, honestly, outside the academic bubble, no one remembers what parties even existed in the ’90s. I figured a good way to show the past is to make it *look* like the past. And when you google “history of political parties,” everything you see is… the US, of course. So this was supposed to inspire me:

<img src="/website//images/us-election.jpg" alt="election" style="width:1000px; border-radius:8px; display:block; margin:1rem auto;">

Now here’s what the process looked like:

| Sketch | Adding data | Refining the SVG | Final outcome |
|---|---|---|---|
| ![Sketch](/website/images/lewica-1.jpeg) | ![Wireframe](/website/images/lewica-2.png) | ![Mockup](/website/images/lewica-3.jpeg) | ![Final](/website/images/lewica-4.png) |
|Once I had a vague idea of the structure, I started with a pencil and a highlighter. | Then I scraped a bunch of Wikipedia pages with election results to feel my sketch with data. I could’ve also just copy-pasted into spreadsheets. | A Sankey template from Flourish became an SVG, then took a trip to Illustrator to get cleaned up and styled. | Now compare it to the inspiration. You might think: “Well, at least she tried.” Exactly. Things never go the way you plan but no one knows your original plan anyway, so who cares! |

## 2. Don’t be shy, ask people you admire for advice

When I’m totally out of ideas, I go to people who are better than me. You won’t be as brilliant as someone who has shipped hundreds of projects, but you *can* borrow their experience.

Here is a couple of examples of how people spark ideas for me.

**<a href="https://x.com/zhoyoyo" target="_blank">Youyou Zhou**</a>, a graphic reporter at WaPo, helped me with sabotage project.

| ![Sketch](/website/images/sb1.png) | <video src="/website/images/wp.mp4" autoplay muted loop playsinline style="max-width:100%; border-radius:8px;"></video> | ![Sketch](/website/images/sb3.jpeg) | <video src="/website/images/vs.mp4" autoplay muted loop playsinline style="max-width:100%; border-radius:8px;"></video>|
|---|---|---|---|
| I needed to tell a long, winding story full of unfamiliar names. This is what I showed Youyou. | She suggested a subtle moving-camera effect, like some WaPo author did to guide the reader through his piece. | Here’s a quick mock-up that shows how the motion helps you keep track of who’s who. | And yes, I absolutely stole that trick for my  **<a href="https://vsquare.org/crossing-nato-lines-tracing-the-arson-sabotage-russia-gru-explosive-parcel-bombs/" target="_blank">piece!**</a>|

**<a href = "https://www.facebook.com/kate.mamyan" target="_blank">Katya Mamyan**</a>, a data journalist from Armenia, helped me shape an idea for a radar diagram on political preferences in Poland.

| ![Sketch](/website/images/radar.jpeg) | ![Sketch](/website/images/radar2.jpeg) | ![Sketch](/website/images/radar4.png) | ![Sketch](/website/images/radar3.png) |
|---|---|---|---|
| Katya’s sketch. | My version with story-specific data. | A radar diagram built in Flourish. | Final print-ready version. |

**People are happy when they can help you; you’re happy because you learn something new. Everyone is happy and that's beautiful!**

## 3. “Exposure” is nice. Turning what you see into a project is better.

A lot of people will tell you that visual exposure is important. I’d say when you see something interesting, immediately think about how you could weave it into something you’ve worked on or plan to.

| ![Sketch](/website/images/dh-24.jpeg) | ![Sketch](/website/images/narko1.jpeg) | ![Sketch](/website/images/narko2.jpg) |
|---|---|---|
| The Dataharvest conference invites an artist to capture moments from the workshops. The caricatures are gorgeous, I’ve wanted to bring that idea into one of my stories ever since I saw them. | For <a href = "https://vsquare.org/faster-than-pizza-delivery-polands-online-drug-market-telegram-parcel-lockers-inpost-blik-police/" target = "_blank">a story about drugs</a>, we hired an illustrator and I sent this brief. | And here’s what the illustrator came up with.

## 4. Finally, find people who believe in your ideas and support you.

<div class="screenshot-collage">
  <img src="/website/images/shot1.png" alt="Screenshot 1" class="tilt-left">
  <img src="/website/images/shot2.png" alt="Screenshot 2" class="tilt-right">
  <img src="/website/images/shot3.png" alt="Screenshot 3" class="tilt-left">
  <img src="/website/images/shot4.png" alt="Screenshot 4" class="tilt-right">
  <img src="/website/images/shot6.png" alt="Screenshot 6" class="tilt-right">
  <img src="/website/images/shot7.png" alt="Screenshot 7" class="tilt-left">
  <img src="/website/images/shot8.png" alt="Screenshot 8" class="tilt-right">
</div>

<span class="highlight">Also, don't forget to tell them when you ***really*** love their work!</span>

**A little action often sparks a lot of momentum. Email me if you think I can help you with anything: nst.morozova13@gmail.com**
