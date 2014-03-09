---
participants:
  - name: Danny Chapman
    twitter: dannychapman
    img: http://github.com/dannychapman.png
  - name: Ben Balter
    twitter: benbalter
    img: http://github.com/benbalter.png
  - name: Jessica Teal
    twitter: tealmedia
    img: "https://media.licdn.com/media/p/2/000/020/11e/28a9538.jpg"
  - name: Julie Herron
    twitter: slowdripcrazy
    img: "https://pbs.twimg.com/profile_images/378800000124267527/51b541fc6bac159f49b4c7821f47b7a3.jpeg"

---

{% for participant in page.participants %}
<div class="participant">
  <img src="{{ participant.img }}" /><br />
  {{ participant.name }}<br />
  <a href="https://twitter.com/{{ participant.twitter }}">@{{ participant.twitter }}</a>
</div>
{% endfor %}
