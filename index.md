---
title: Home
---

<div> 
    <img src="{{ "/images/ixia.png" | absolute_url }}" alt="github octocat" style="width:100%;" >    
</div>

## This is a sample API documentation project with GitHub. 

### The tutorials explain some of the IxNetwork feature configurations with sample scripts.


<div class="toc" markdown="1">

## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>



> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)


