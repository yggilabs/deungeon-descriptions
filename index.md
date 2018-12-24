---
layout: default
---
# Dungeon Descriptions
{% for dungeon in site.data.dungeons %}
## {{ dungeon.name }}
**Descriptions** --- {{ dungeon.desc | join: ", " }}
**Tags** --- {{ dungeon.tags | join: ", " }}
{% endfor %}
