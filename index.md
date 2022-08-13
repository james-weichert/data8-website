---
layout: home
title: Home
nav_order: 1
nav_exclude: false
permalink: index.html
seo:
  type: Course
  name: Just the Class
---

# Introduction to Computational Thinking with Data &#x1f4ca;

{: .mb-2 }
UC Berkeley, Summer 2022
{: .mb-2 .fs-6 .text-grey-dk-000 }

{: .mb-2 }
**Instructors:** James Weichert (<a>jweichert@berkeley.edu</a>), Will Furtado (<a>willfurtado@berkeley.edu</a>)
{: .mb-0 .fs-5 .text-grey-dk-000 }
<!--{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>-->

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}
