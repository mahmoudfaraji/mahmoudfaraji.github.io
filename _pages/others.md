---
layout: archive
title: "Others"
permalink: /others/
author_profile: true
---


<a href="/others"  class='header-color'>Research Experiences</a>
----
### APA AUT CERT (<a href="https://apa.aut.ac.ir/en" target="_Blank">https://apa.aut.ac.ir/en</a>):
<ul class='onecol' markdown='1'>
  <li> Research Assistant at AUT CERT Lab. - (<i style='font-size: 0.8em;'>June 2021 - Now </i>)
    <ul>
      <li>
        <p style='text-align: justify;'> "Web & Mobile Application Security Analysis" with Professor <a href="https://aut.ac.ir/cv/2102/%d8%a8%d8%a7%d8%a8%da%a9%20%d8%b5%d8%a7%d8%af%d9%82%db%8c%d8%a7%d9%86" target="_Blank">Babak Sadeghiyan</a></p>
        <p style='text-align: justify;'> In this lab, we analyze the security vulnerabilities of web and mobile applications with static and dynamic oriented and we provide awareness to business owners of the existence of security bugs that we have identified based on the OWASP standard and for improve and fix these vulnerabilities give them advice.</p>
      </li>
    </ul>
  </li>
</ul>

### Amirkabir University of Technology (Tehran Polytechnic) (AUT): 
<ul class='onecol' markdown='1'>
<li> Research Assistant at Security Analysis Lab. - (<i style='font-size: 0.8em;'>Sep. 2021 - Now </i>)
<ul>
<li>
<p style='text-align: justify;'> "A Method for Protecting Privacy of IoT Healthcare Data Against Machine Learning Attack" M.Sc. thesis with Professor <a href="https://aut.ac.ir/~shahriari" target="_Blank">Hamid Reza Shahriari</a></p>
<p style='text-align: justify;'> Machine learning models leak information about the individual data records on which they were trained. <a href="https://www.comp.nus.edu.sg/~reza/" target="_Blank">Reza Shokri</a> et al.[<a href="#Ref_1">1</a>] focus on the basic membership inference attack: given a data record and black-box access to a model, determine if the record was in the model's training dataset. To perform membership inference against a target model, they make adversarial use of machine learning and train their own inference model to recognize differences in the target model's predictions on the inputs that it trained on versus the inputs that it did not train on. They empirically evaluate their inference techniques on classification models trained by commercial "machine learning as a service" providers such as Google and Amazon. Using realistic datasets and classification tasks, including a hospital discharge dataset whose membership is sensitive from the privacy perspective, they show that these models can be vulnerable to membership inference attacks. So, in this lab, we are looking to find a way to protect healthcare data privacy in IoT which causes the data to be stored anonymously and enter the training stage of machine learning algorithms so that these machine learning algorithms do not understand the original data. Also, this solution must be lightweight for IoT environment.</p>
</li>
<p style='padding-left: 30px;'>
<img style='border: 3px solid #111;width: 600px;' alt="Membership Inference Attack" src="/images/membership inference attack.png">
<h3 style='padding-left: 30px;font-size: 0.6em;'> Picture Reference = [<a href="#Ref_2">2</a>]</h3>
</p>
   </ul>
  </li>
</ul>


<a href="#"  class='header-color'>Technical Reports</a>
---------
### Amirkabir University of Technology (Tehran Polytechnic) (AUT):
<ul class='onecol' markdown='1'>
  <li> Project Report for Applied Cryptography (Graduate Course), (+Oral Presentation) [In Persian] - (<i style='font-size: 0.8em;'> Oct. 2020 - Feb. 2021</i>)
    <ul>
      <li>
        <p style='text-align: justify;'> "Design and Implementation a New Cryptography Algorithm" with Professor <a href="https://aut.ac.ir/cv/2102/%d8%a8%d8%a7%d8%a8%da%a9%20%d8%b5%d8%a7%d8%af%d9%82%db%8c%d8%a7%d9%86" target="_Blank">Babak Sadeghiyan</a></p>
        <p style='text-align: justify;'> Designing a cryptographic algorithm can be one of the solutions in order to evaluate the level of knowledge of an active expert in the field of applied cryptography. In this project, we have designed a new algorithm using different parts of several encryption algorithms. In this project, the input of the algorithm is a 96-bit fragment. The structure used to do this project is a Feistel type 1 structure. After entering the parts into the algorithm, a part of it is affected by the function f and then it is XORed with the other part. Finally, the first round ends with the moving of the parts. This is done for twelve consecutive rounds. The f function used in this project is designed similarly to the Blowfish function. Also, another part of this project is related to the key part, where 96 bits of the main key are entered into the system. By applying the function on this key, a total of 36 subkeys are produced, which are used in 12 rounds. The function applied to the key is similar to the structure of the AES key function with a slight modification. Finally, this algorithm is implemented in OFB mode (both encryption and decryption), and avalanche, integrity, and NIST tests are performed on it. In addition, the number of lines of this algorithm is 344 lines in Python along with the codes related to the Avalanche test and completeness and OFB mode. This number of lines is defined without considering the codes related to NIST tests and tables.</p>
      </li>
<p style='padding-left: 30px;'> Overview:</p>
<img style='border: 3px solid #111;width: 600px;' alt="Cryptography Algorithm" src="/images/Cryptography Alg. pic1.png">
<p style='font-size: 0.6em;'> More details and code: <a href="https://github.com/mahmoudfaraji/MScDocuments/tree/main/TechnicalReports/newCryptoAlgorithm">New Cryptography Algorithm</a></p>
</ul>
</li>
</ul>



<a style='font-size: 0.7em;' href="#" class='header-color'>References</a>
----
<div style='font-size: 0.6em;'>
<p id="Ref_1">
[1].<a href="https://ieeexplore.ieee.org/abstract/document/7958568" target="_Blank">https://ieeexplore.ieee.org/abstract/document/7958568</a>
</p>
<p id="Ref_2">
[2].<a href="https://ieeexplore.ieee.org/abstract/document/8634878" target="_Blank">https://ieeexplore.ieee.org/abstract/document/8634878</a>
</p>


