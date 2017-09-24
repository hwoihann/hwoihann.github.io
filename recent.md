---
layout: base
---
<div class="wrapper">
    <header>
        {% if site.compass.logo %}

<div class="logo-container">

</div>
        {% endif %}

        <div class="author-container"><h1>Recent</h1></div>
        
        <div class="tagline-container"></div>

<p style="font-family:serif;">
</p>

    </header>
    <main>
      {% if site.compass.include_content %}
      <div class="content">
        {% include Recent-content.html %}
      </div>
      {% endif %}
</div>

