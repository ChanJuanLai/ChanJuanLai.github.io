---
layout: article
title:  "信息可视化作品集"
date:   2018-01-06 22:07:50 +0800
categories: infovis tableau
image:
  teaser: quanguo.png
---
<body>
 <h1>下图是五大珠宝店在全国的分布图，可以清晰看出各省的分布情况。</h1>
 <div class='tableauPlaceholder' id='viz1515141049655' style='position: relative'><noscript><a href=''><img alt='全国分布图 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;WW&#47;WWWWYMHXJ&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;WWWWYMHXJ' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;WW&#47;WWWWYMHXJ&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1515141049655');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
 </body>
<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->