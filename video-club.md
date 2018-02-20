---
layout: default
---

<h1>Video Club</h1>
<div>
  Every wednesday we get together to watch a video over lunch.
</div>
<div class="video-club">
  {% for video in site.data.video_club %}
    <article>

      <h1>{{ video.title }}</h1>
      <h3>{{ video.presenter }}</h3>
      <div class="entry">
        <div class="watched-date">
          {{ video.date }}
        </div>
        <a href="{{ video.video_url }}">
          watch at: {{ video.video_url }}
        </a>
      </div>
    </article>
  {% endfor %}
</div>