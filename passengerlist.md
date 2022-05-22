---
layout: template
---

# Passenger List

{% for item in site.data.titanic %}
-  {{item.Name}},{{item.Age}}
{% endfor %}