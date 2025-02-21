---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% include mermaid-cv.md %}

# Education

* Ph.D. in United Graduate School of Agricultural Science, Tokyo University of Agriculture and Technology, 2013
* M.S. in Graduate School of Agriculture, Tokyo University of Agriculture and Technology, 2010  
* B.S. in Faculty of Agriculture, Tokyo University of Agriculture and Technology, 2007  

---

# Fellowship

* 2018-2021     JSPS Research Fellowships for Young Scientists, PD  

---

# Academic Positions

* 2025-present  Associate Professor, Graduate School of Agriculture, Kyoto University
* 2021-2025     Assistant Professor, Graduate School of Agriculture, Kyoto University
* 2017-2018     Program-Specific Assistant Professor, Graduate School of Agriculture, Kyoto University  

---

# Part-time Lecturer

* 2015-2017     Faculty of Education, Tokyo Gakugei University  

---

# Honors and Prizes

* 2020     Japan Ethological Society Award  

---

# Presentation Awards

* 2012     Poster Award, Japan Ethological Society  
* 2007     Award for The Best Presentation, Department of Biological Production, Faculty of Agriculture, Tokyo University of Agriculture and Technology  

---

# Competitive Grants

* 2021-(2026) Grant-in-Aid for Early-Career Scientists, Japan Society for the Promotion of Science (Research Project No. 21K14863)
* 2018-2021   Grant-in-Aid for JSPS Fellows, Japan Society for the Promotion of Science (Research Project No. 18J01880)  
* 2017-2018   Grant-in-Aid for Research Activity Start-up, Japan Society for the Promotion of Science (Research Project No. 17H06796)

---

# Publications

Total: {{ site.publications | size }}

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
