---
layout: base
---
<div class="wrapper">
    <header>
        {% if site.compass.me %}
        <div class="logo-container">
          <a class="logo" href="{{ page.baseurl }}" style="background-image: url('{{ site.baseurl }}{{ site.compass.me }}')"></a>
        </div>
        {% endif %}

        {% if site.compass.author %}
        <div class="author-container"><h1>{{ site.compass.author }}</h1></div>
        {% endif %}
        
	<div class="tagline-container"><p>
	


	</p></div>
    </header>
    <main>
      {% if site.compass.include_content %}
      <div class="content">
        {% include Person-content.html %}
      </div>
      {% endif %}
</div>

