---
layout: home
title: Home
nav_order: 1
nav_exclude: false
permalink: index.html
seo:
  type: Course
  name: Data 8 Fall 2022
---

# Data 8: Foundations of Data Science

{: .mb-2 }
UC Berkeley, Fall 2022
{: .mb-2 .fs-6 .text-grey-dk-000 }

{: .mb-2 }
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role flex">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}


### Darkmode Test

<form>
  <button onclick="darkMode()">Darkmode</button>
</form>

  function darkMode() {
    jtd.setTheme("dark");
  }

<script>

</script>
