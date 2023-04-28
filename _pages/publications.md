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
<li> <b>A Method for Protecting Privacy of IoT-Based Healthcare Data</b>, <em>Master's Thesis</em>, March 2023 <!--[<a href="#">pdf</a>] [<a href="#">link</a>]-->
<br>Supervisor: Hamid Reza Shahriari, Opponent: Ehsan Nazerfard, Morteza Amini
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
One of the most significant and widespread uses of machine learning models is in remote medical environments, where it is necessary for hospital cloud service providers to gather patient healthcare information in order to integrate, correct, and control patients' health statuses by doctors or to sell this data to researchers for analysis. Additionally, these data are given to machine learning algorithms as training data in order to develop a model to classify patient data, identify any potential diseases, and make the model publicly accessible to researchers, medical professionals, and patients under the name of API. Machine learning models are susceptible to membership inference attacks, which violate the privacy of training data, according to recent studies. In actuality, the goal of this attack is to infer a data record's membership in the training dataset. The goal of this research is to provide a defense scheme against this attack so that machine learning algorithms are taught using tokens that match the features of the data records rather than having access to the main training data directly. The security of the tokens that are stored in the dataset and correspond to each feature of the data records determines the security of the proposed schema. Since the production of these tokens is based on the difficulty of the discrete logarithm problem in the elliptic curve, the security can be proven. Also, this architecture can be used and applied in the Internet of Things environments because it has lightweight calculations. The model's accuracy is the same when the proposed scheme is applied to the data set and when it is not, according to the evaluation results of the proposed scheme.
</div></li></div>
  
  
<div id="2">
<li> <b>A Secure and Efficient Scheme for Mutual Authentication for Integrity of Exchanged Data in IoMT</b>, <em><a href="https://csicc2023.csi.org.ir/Home">CSICC 2023</a></em>, Jan. 2023 <!--[<a href="#">pdf</a>]--> [<a href="https://ieeexplore.ieee.org/document/10105398">link</a>]
<br>Mahmoud Faraji, Hamid Reza Shahriari, Mahdi Nikooghadam
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
The emergence of pandemic diseases like Covid-19 in recent years has made it more important for Internet of Medical Things (IoMT) environments to build contact between patients and medical staff in order to control their health state. Patients will be able to send their healthcare data to the cloud server of the medical service provider in remote medical environments through sensors connected to their smart devices, such as watches or smartphones. However, patients' worries surrounding their data privacy protection are still present. In order to ensure the security and privacy of patients' healthcare data in remote medical environments, a number of different schemes have been proposed by researchers. However, these schemes have not been able to take all security requirements into account such as perfect forward secrecy or replay attacks. Consequently, in this study, we have proposed a secure and effective protocol to safeguard the privacy of patients' medical data when it is sent to the server. This protocol entails two components: mutual authentication of the patient and the server of the medical service provider, as well as the integrity of the exchanged data. Also, our scheme satisfies security requirements such as perfect forward secrecy and replay attacks and other requirements and is resistant to well-known attacks. Following this, we used the Scyther tool to formally analyze our proposed scheme. The results showed that the scheme is secure, and in the section on performance analysis, we demonstrated that the proposed scheme performs better than comparable schemes.
</div></li></div>
  
  
<div id="3">
<li> <b>Security and Privacy in Blockchain Smart Contracts</b>, <em>Master's Seminar</em>, Sep. 2021 <!--[<a href="#">pdf</a>] [<a href="#">link</a>]-->
<br>Supervisor: Hamid Reza Shahriari, Opponent: Reza Safabakhsh
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
This presentation's goal is to provide an in-depth analysis of the technical issues with smart contracts, which are made possible by blockchain technology, and call for user privacy and security safeguards.
</div></li></div>
  
  
<div id="4">
<li> <b>Design and Implementation a New Cryptography Algorithm</b>, <em>Technical Report</em>, Oct. 2020 - Feb. 2021 <!--[<a href="#">pdf</a>]--> [<a href="https://github.com/mahmoudfaraji/MScDocuments/tree/main/TechnicalReports/newCryptoAlgorithm">link</a>]
<br>Supervisor: Babak Sadeghyian
<div class='button' data-content="toggle-text"><a href="#1">abstract</a></div>
<div class='abstract'>
Designing a cryptographic algorithm can be one of the solutions in order to evaluate the level of knowledge of an active expert in the field of applied cryptography. In this project, we have designed a new algorithm using different parts of several encryption algorithms. In this project, the input of the algorithm is a 96-bit fragment. The structure used to do this project is a Feistel type 1 structure. After entering the parts into the algorithm, a part of it is affected by the function f and then it is XORed with the other part. Finally, the first round ends with the moving of the parts. This is done for twelve consecutive rounds. The f function used in this project is designed similarly to the Blowfish function. Also, another part of this project is related to the key part, where 96 bits of the main key are entered into the system. By applying the function on this key, a total of 36 subkeys are produced, which are used in 12 rounds. The function applied to the key is similar to the structure of the AES key function with a slight modification. Finally, this algorithm is implemented in OFB mode (both encryption and decryption), and avalanche, integrity, and NIST tests are performed on it. In addition, the number of lines of this algorithm is 344 lines in Python along with the codes related to the Avalanche test and completeness and OFB mode. This number of lines is defined without considering the codes related to NIST tests and tables.
</div></li></div>
  
  
<div id="5">
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
