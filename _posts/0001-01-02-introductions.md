---
---

{% for participant in site.participants %}
<div class="participant">
  <img src="{{ participant.img }}" /><br />
  <h5>{{ participant.name }}</h5>
  <span class="twitter"><a href="https://twitter.com/{{ participant.twitter }}">@{{ participant.twitter }}</a></span>
</div>
{% endfor %}
