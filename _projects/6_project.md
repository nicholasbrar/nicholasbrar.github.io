---
layout: page
title: Chess Pulse
description: Using the Chess.com API to extract more useful stats and improvement insights.
img: assets/img/projects/chess/chess_overview.png
importance: 1
category: fun
images:
  slider: true
---

I'm using the **Chess.com API** to pull my games and try to extract more useful information for improvement—better stats, strengths and weaknesses, and progress over time. This is **very much in progress**: I'm building out dashboards and views that go beyond what the site gives you by default.

Screenshots below show an overview of recent activity, speed/rating profile, and search so far.

<style>
.chess-stats-slider swiper-container {
  max-height: 50vh;
  margin-left: auto;
  margin-right: auto;
}
.chess-stats-slider swiper-slide {
  max-height: 50vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
.chess-stats-slider swiper-slide figure,
.chess-stats-slider swiper-slide picture {
  max-height: 50vh;
  margin: 0;
}
.chess-stats-slider swiper-container img {
  object-fit: contain;
  max-height: 50vh;
  width: auto;
  height: auto;
  margin: 0 auto;
  display: block;
}
</style>
<div class="row justify-content-sm-center mt-4 chess-stats-slider">
    <div class="col-sm-12 col-md-6 col-lg-4">
        <swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" rewind="true">
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/chess/chess_overview.png" title="Chess overview" class="img-fluid rounded z-depth-1" %}</swiper-slide>
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/chess/chess_speed_profile.png" title="Speed and rating profile" class="img-fluid rounded z-depth-1" %}</swiper-slide>
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/chess/chess_search.png" title="Search" class="img-fluid rounded z-depth-1" %}</swiper-slide>
        </swiper-container>
        <div class="caption">
            Chess.com API project—overview, speed/rating profile, and search (work in progress).
        </div>
    </div>
</div>
