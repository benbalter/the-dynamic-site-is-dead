---
---

{% for participant in site.participants %}
<div class="participant">
  <img src="{{ participant.img }}" /><br />
  {{ participant.name }}<br />
  <a href="https://twitter.com/{{ participant.twitter }}">@{{ participant.twitter }}</a>
</div>
{% endfor %}
