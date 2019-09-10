---
title: Visualize
section: Visualize
permalink: /visualize/
layout: page
---

<h1 class="py-4">Collection Statistics</h1>

{%- assign items = site.data.digital_all_collections -%}
<div class="row">
  <div class="col-md-8">

    {% include index/objects.html %}
    {% include index/time.html %}
    
    </div>
  <div class="col-md-4">  

    {% include index/subjects.html %}
    {% include index/locations-sm.html %}

  </div>

  
</div>
