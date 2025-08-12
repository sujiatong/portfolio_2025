---
layout: default
title: "Projects"
---

# All Projects

## Table of Contents

<details>

   <summary>Contents</summary>

1. [layout: default
title: "Projects"](#layout-default-title-projects)

</details>

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }}) — {{ project.excerpt }}
{% endfor %}
