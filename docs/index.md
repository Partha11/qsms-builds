---
layout: default
---

{% if site.remote_theme %}
  Theme loaded: {{ site.remote_theme }}
{% else %}
  ⚠️ THEME FAILED TO LOAD ⚠️
  Debug info:
  - Plugins: {{ site.plugins | join: ", " }}
  - GitHub Metadata: {{ site.github | jsonify }}
{% endif %}