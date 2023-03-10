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
<li> <b>Security and Privacy in Smart Contract & Blockchain</b>, <em>M.Sc. Seminar</em>, Sep. 2021 <!--[<a href="#">pdf</a>] [<a href="#">link</a>]-->
<br>Supervisor: Hamid Reza Shahriari, Opponent: Reza Safabakhsh
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
This presentation's goal is to provide an in-depth analysis of the technical issues with smart contracts, which are made possible by blockchain technology, and call for user privacy and security safeguards.
</div></li></div>
  
  
<div id="2">
<li> <b>Design and Implementation a New Cryptography Algorithm</b>, <em>Technical Report</em>, Oct. 2020 - Feb. 2021 <!--[<a href="#">pdf</a>] [<a href="#">link</a>]-->
<br>Supervisor: Babak Sadeghyian
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
Designing a cryptographic algorithm can be one of the solutions in order to evaluate the level of knowledge of an active expert in the field of applied cryptography. In this project, we have designed a new algorithm using different parts of several encryption algorithms. In this project, the input of the algorithm is a 96-bit fragment. The structure used to do this project is a Feistel type 1 structure. After entering the parts into the algorithm, a part of it is affected by the function f and then it is XORed with the other part. Finally, the first round ends with the moving of the parts. This is done for twelve consecutive rounds. The f function used in this project is designed similarly to the Blowfish function. Also, another part of this project is related to the key part, where 96 bits of the main key are entered into the system. By applying the function on this key, a total of 36 subkeys are produced, which are used in 12 rounds. The function applied to the key is similar to the structure of the AES key function with a slight modification. Finally, this algorithm is implemented in OFB mode (both encryption and decryption), and avalanche, integrity, and NIST tests are performed on it. In addition, the number of lines of this algorithm is 344 lines in Python along with the codes related to the Avalanche test and completeness and OFB mode. This number of lines is defined without considering the codes related to NIST tests and tables.
</div></li></div>
  
  
<div id="3">
<li> <b>A Distributed System for Managing Warehouse Branches</b>, <em>Bachelor's thesis</em>, 2019 <!--[<a href="#">pdf</a>] [<a href="#">link</a>]-->
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
In this project, a distributed system for managing the input and output of items, and ultimately combining the inventory of products in separate warehouse branches in several places of the city, has been planned and implemented utilising the C# programming language and SQL Server database.
</div></li></div>
  
 
</ol>







<!-- 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
