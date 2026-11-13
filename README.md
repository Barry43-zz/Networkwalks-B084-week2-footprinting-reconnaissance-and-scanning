# Networkwalks-B084-week2-footprinting-reconnaissance-and-scanning
<!DOCTYPE html>

<html lang="en">



<head>

</head>



<body>



<header>



<h1>PENETRATION TESTING REPORT</h1>



<p>Footprinting & Network Scanning Assessment</p>



<p>Cybersecurity | Ethical Hacking | Security Assessment</p>



<span class="badge">TECHNICAL SECURITY REPORT</span>



<br>




Download / Print Report

</button>



</header>





<nav>



<a href="#overview">Overview</a>

<a href="#scope">Scope</a>

<a href="#tools">Tools</a>

<a href="#activities">Activities</a>

<a href="#findings">Findings</a>

<a href="#evidence">Evidence</a>

<a href="#conclusion">Conclusion</a>



</nav>





<div class="container">





<!-- ASSESSMENT INFORMATION -->



<section class="section" id="overview">



<h2>01. Assessment Information</h2>



<div class="info-grid">



<div class="info-card">

<strong>Penetration Tester</strong>

Vincent Goodluck

</div>



<div class="info-card">

<strong>Assessment Type</strong>

Footprinting & Network Scanning

</div>



<div class="info-card">

<strong>Operating System</strong>

Kali Linux / Windows

</div>



<div class="info-card">

<strong>Assessment Date</strong>

11/13/2026

</div>



<div class="info-card">

<strong>Testing Environment</strong>

VirtualBox / Local Network

</div>



<div class="info-card">



</div>



</div>



</section>





<!-- EXECUTIVE SUMMARY -->



<section class="section">



<h2>02. Executive Summary</h2>



<p>

This penetration testing report documents practical

cybersecurity activities involving reconnaissance,

footprinting, information gathering and network scanning.

</p>



<p>

The assessment demonstrates the use of industry-standard

cybersecurity tools to collect information about an

authorized target and identify active devices within

an authorized network.

</p>



<p>

The primary objective is to understand the security

assessment process, document observations and identify

potential security risks.

</p>



</section>





<!-- SCOPE -->



<section class="section" id="scope">



<h2>03. Scope of Assessment</h2>



<h3>Activities Covered</h3>



<ul>



<li>Reconnaissance and information gathering</li>



<li>Domain footprinting</li>



<li>DNS enumeration</li>



<li>Web technology identification</li>



<li>HTTP header inspection</li>



<li>Network discovery</li>



<li>Host identification</li>



<li>Risk assessment</li>



</ul>



<h3>Testing Limitations</h3>



<p>

The assessment is limited to information gathering

and network discovery activities. Exploitation and

vulnerability validation are not included unless

separately authorized and documented.

</p>



</section>





<!-- TOOLS -->



<section class="section" id="tools">



<h2>04. Tools & Technologies Used</h2>



<table>



<tr>

<th>Tool</th>

<th>Purpose</th>

</tr>



<tr>

<td>Kali Linux</td>

<td>Penetration testing environment</td>

</tr>



<tr>

<td>WHOIS</td>

<td>Domain registration information gathering</td>

</tr>



<tr>

<td>WhatWeb</td>

<td>Web technology fingerprinting</td>

</tr>



<tr>

<td>Nslookup</td>

<td>DNS information gathering</td>

</tr>



<tr>

<td>cURL</td>

<td>HTTP response header inspection</td>

</tr>



<tr>

<td>Wafw00f</td>

<td>Web Application Firewall detection</td>

</tr>



<tr>

<td>DNSRecon</td>

<td>DNS enumeration</td>

</tr>



<tr>

<td>Nmap</td>

<td>Network discovery and scanning</td>

</tr>



<tr>

<td>Zenmap</td>

<td>Graphical network scanning interface</td>

</tr>



</table>



</section>





<!-- ACTIVITIES -->



<section class="section" id="activities">



<h2>05. Activities Performed</h2>



<h3>5.1 Reconnaissance & Footprinting</h3>



<p>

Reconnaissance involves gathering publicly available

information about an authorized target.

</p>



<p>

The tools used during this phase help identify domain

registration details, DNS records, web technologies

and HTTP response information.

</p>



<h3>5.2 Network Scanning & Discovery</h3>



<p>

Network scanning was performed to identify active

hosts within the authorized local network.

</p>



<p>

Zenmap was used to visualize discovered hosts and

understand the network environment.

</p>



<h3>5.3 Findings Analysis</h3>



<p>

Information gathered during reconnaissance and

scanning was reviewed to identify potential

security concerns.

</p>



</section>





<!-- FINDINGS -->



<section class="section" id="findings">



<h2>06. Risk Assessment & Findings</h2>



<p>

The following table provides examples of observations

that may arise during reconnaissance and network scanning.

Replace these with your actual verified results.

</p>



<table>



<tr>

<th>#</th>

<th>Finding</th>

<th>Potential Impact</th>

<th>Severity</th>

</tr>



<tr>

<td>01</td>

<td>Web technology information exposed</td>

<td>May assist technology fingerprinting</td>

<td><span class="severity medium">MEDIUM</span></td>

</tr>



<tr>

<td>02</td>

<td>Server IP address identifiable</td>

<td>Provides infrastructure information</td>

<td><span class="severity low">LOW</span></td>

</tr>



<tr>

<td>03</td>

<td>HTTP technical information exposed</td>

<td>May assist further enumeration</td>

<td><span class="severity low">LOW</span></td>

</tr>



<tr>

<td>04</td>

<td>WAF technology identifiable</td>

<td>Reveals security architecture details</td>

<td><span class="severity low">LOW</span></td>

</tr>



<tr>

<td>05</td>

<td>DNS infrastructure information exposed</td>

<td>Helps build an infrastructure profile</td>

<td><span class="severity medium">MEDIUM</span></td>

</tr>



<tr>

<td>06</td>

<td>Multiple active network hosts discovered</td>

<td>Unknown devices may require investigation</td>

<td><span class="severity medium">MEDIUM</span></td>

</tr>



</table>



<br>



<p>

<strong>Important:</strong> These observations are not

automatically confirmed vulnerabilities. Additional

authorized validation is required before classifying

them as security vulnerabilities.

</p>



</section>





<!-- RECOMMENDATIONS -->



<section class="section">



<h2>07. Security Recommendations</h2>



<ul>



<li>

Regularly review publicly exposed web technologies.

</li>



<li>

Keep CMS platforms and plugins updated.

</li>



<li>

Review HTTP security headers.

</li>



<li>

Maintain proper DNS configurations.

</li>



<li>

Configure and monitor Web Application Firewalls.

</li>



<li>

Perform regular internal network discovery.

</li>



<li>

Investigate unknown devices on the network.

</li>



<li>

Maintain updated network documentation.

</li>



<li>

Perform security testing only with proper authorization.

</li>



</ul>



</section>





<!-- EVIDENCE -->



<section class="section" id="evidence">



<h2>08. Screenshots & Evidence</h2>



<p>

Supporting screenshots should be included to demonstrate

the commands executed and the results obtained.

</p>



<div class="evidence">



<h3>WHOIS Information Gathering</h3>






<p class="placeholder">

WHOIS command output

</p>



</div>





<div class="evidence">



<h3>WhatWeb Technology Identification</h3>



<img src="screenshots/whatweb.png"

alt="WhatWeb Screenshot">



<p class="placeholder">

WhatWeb command output

</p>



</div>





<div class="evidence">



<h3>DNS Enumeration</h3>



<img src="screenshots/dnsrecon.png"

alt="DNSRecon Screenshot">



<p class="placeholder">

DNSRecon command output

</p>



</div>





<div class="evidence">



<h3>Zenmap Network Scanning</h3>



<img src="screenshots/zenmap.png"

alt="Zenmap Screenshot">



<p class="placeholder">

Zenmap network discovery results

</p>



</div>



</section>





<!-- CONCLUSION -->



<section class="section" id="conclusion">



<h2>09. Conclusion</h2>



<p>

This project provided practical exposure to

reconnaissance, footprinting and network scanning

using cybersecurity tools.

</p>



<p>

Through these activities, I developed a better

understanding of how security professionals gather

information, identify network devices, analyze

observations and document potential risks.

</p>



<p>

The project also highlights the importance of

authorization, evidence collection and professional

security reporting.

</p>



</section>





<!-- DISCLAIMER -->



<section class="section">



<h2>10. Disclaimer</h2>



<div class="disclaimer">



<p>

This report is intended strictly for educational

purposes and authorized cybersecurity assessments.

</p>



<p>

All testing activities must be conducted only

against systems and networks owned by the tester

or where explicit permission has been obtained.

</p>



<p>

Unauthorized scanning, access or testing of

third-party systems is prohibited.

</p>



</div>



</section>





</div>





<footer>



<p>

<strong>Penetration Testing Report</strong>

</p>



<p>

Cybersecurity | Ethical Hacking | Network Security

</p>



<p>

Prepared by: YOUR NAME

</p>



<p>

© 2026 | Educational Cybersecurity Project

</p>



</footer>





</body>



</html>
