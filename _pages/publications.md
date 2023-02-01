---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
  $(document).ready(function () {
    $(".abstract").hide();
    $(".button").on("click", function () {
        $(this).next(".abstract").slideToggle(400);
    });
});
</script>


<style>
.abstract{text-align:justify; }
.button{ text-align:justify; }
</style>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}



<ol reversed>

<div id="1">
<li> <b>A Distributed System for Managing Warehouse Branches</b>, <em>Bachelor's thesis</em>, 2019 <!--[<a href="#">pdf</a>] [<a href="#">link</a>]-->
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>

</div></li></div>
</ol>







<!-- 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
