---
layout: default
title: I. EMERGING THREATS HAVE UPENDED DATA BREACH NOTIFICATION LAWS
parent: § Comment - The Necessary Evolution of State Data Breach Notification Laws - Keeping Pace with New Cyber Threats Quantum Decryption and the Rapid Expansion of Technology  
grand_parent: C
nav_order: 20 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

     -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}

.youtube-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
}
.youtube-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>

<div class="dont-break-out" markdown="1">

1. TOC
{:toc}

## I. EMERGING THREATS HAVE UPENDED DATA BREACH NOTIFICATION LAWS
A myriad of exploited threat vectors have emerged in the two decades since California passed the first data breach notification law. Most recently, the proliferation of ransomware, and, in particular, double extortion ransomware, has emerged as a scourge to society. Ransomware “is an ever-evolving form of malware designed to encrypt files on a device, rendering any files and systems that rely on them unusable,” unless a ransom is paid in exchange for a decryption key.<sup>2</sup> In the case of double extortion ransomware, threat actors go beyond encrypting data in place by also exporting victim data for sale or threatening

***
<sup>1</sup>. Phillip Harmon, *Data Breach Notification Laws and the Quantum Decryption Problem,* 79 WASH. & LEE L. REV. 471, 479 (2022). 
{: .fs-2}
<sup>2</sup>. *Ransomware 101*, STOP RANSOMWARE, https://perma.cc/V5TA-9HMS.
{: .fs-2}
***

publication as blackmail.<sup>3</sup> In 2019, a group of cyber-criminal pioneers, known as the “Maze” group, instigated the first published double extortion case involving Allied Universal, a security staffing company based in the United States.<sup>4</sup> News articles in 2019 called this a “game-changing blackmail model.”<sup>5</sup> In the case of Allied Universal, Maze reportedly stole 7 GB worth of data prior to executing their encryption tactics to encrypt the Allied Universal network.<sup>6</sup> Maze then approached their victim demanding 300 bitcoins, valued at approximately $2.6 million at the time.<sup>7</sup> When the victim refused to pay, Maze published 700 MB of data on a Russian hacking forum on the dark web.<sup>8</sup> This reflected approximately “10% of the [data] stolen” and, after posting, Maze contacted the information security magazine, *Bleeping Computer,* to share information about the heist.<sup>9</sup> Maze, in writing to Bleeping Computer, claimed it was “writing to you because we have breached Allied Universal security firm (aus.com), downloaded data and executed Maze ransomware in their network.”<sup>10</sup>

Cyber-criminal gangs soon began to follow Maze’s method of double extortion. Groups began offering “ransomware-as-a-service” or RaaS, with threat groups offering malware and infrastructure in exchange for a fee or profit

***
<sup>3</sup>. See Janus Agcaoili et al., *Ransomware Double Extortion and Beyond: REvil, Clop, and Conti,* TREND MICRO (June 15, 2021), https://perma.cc/Q5VG77D9; *Ransomware 101, supra* note 2; *see also* Brian Stack, *Here’s How Much Your Personal Information Is Selling for on the Dark Web*, EXPERIAN (Dec. 6, 2017), https://perma.cc/9SFW-Q4AN (describing the ten most common pieces of information sold on the dark web with prices that range from $1 to $2,000). 
{: .fs-2}
<sup>4</sup>. *Ransomware Evolved: Double Extortion*, CHECK POINT RSCH. (Apr. 16, 2020), https://perma.cc/4VWZ-G3RM. 
{: .fs-2}
<sup>5</sup>. Muhammad Hamza Shahid, *Ransomware Adopts a Game-Changing Blackmail Model for Information Theft,* INFO SEC. (July 24, 2020), https://perma.cc/5M9V-7R6E. 
{: .fs-2}
<sup>6</sup>. *Id*.
{: .fs-2}
<sup>7</sup>. *Id*. 
{: .fs-2}
<sup>8</sup>. *Id*. 
{: .fs-2}
<sup>9</sup>. Lawrence Abrams, *Allied Universal Breached by Maze Ransomware, Stolen Data Leaked,* BLEEPING COMPUT. (Nov. 21, 2019, 10:48 PM), https://perma.cc/38VJ-ELBG (explaining that Bleeping Computer received an email signed “Maze Crew” reporting the theft and stating that Maze group “always exfiltrate[s], or steal[s], a victim’s files” before it encrypts any computer). 
{: .fs-2}
<sup>10</sup>. *Id*.
{: .fs-2}
***

sharing.<sup>11</sup> Cyber-criminal cartels—cyber criminals operating Soprano’s-style gang families—began to emerge, both locking data and stealing it.<sup>12</sup>

The threat actors employ sophisticated tactics to execute their malicious activity, often utilizing software scripts to execute the removal of data and utilizing anti-forensic techniques to hide their tracks.<sup>13</sup> For example, the PYSA ransomware operation uses a PowerShell script set to execute across a victim’s network, gathering up any file that hits on search terms such as “SSN,” “bank*statement,” or “W-2.”<sup>14</sup> A PowerShell “is a cross-platform task automation solution made up of a command-line shell, a scripting language, and a configuration management framework.”<sup>15</sup> In other words, it is an automated line of coding designed by non-malicious or malicious software coders to execute a function on a device. In the case of PYSA, or a similar threat actor group, after entering a victim organization’s environment undetected, they run a PowerShell script to gather up and remove documents from the victim network for later use on a shame website.<sup>16</sup> The PowerShell script runs automatically, canvassing files using search terms and ultimately exporting a subset of data to the threat actor.<sup>17</sup>

Using a script results in potential “access” to thousands of files across the entirety of an organization’s servers. In many instances, it may be impossible to discern whether these files were ever viewed by a real person or just technically modified using a software script. Similarly, there are often limits on an organization’s knowledge of whether the data accessed by the

***
<sup>11</sup>. Stu Sjouwerman, *Ransomware Gangs: Who Are They and How to Stop Them,* FORBES (Sept. 27, 2021, 9:15 AM), https://perma.cc/BS7U-JTXA (noting the “U.S. government has elevated ransomware threats to a level of priority similar to that of terrorism”). 
{: .fs-2}
<sup>12</sup>. *See id*. (“The FBI is monitoring more than 100 active ransomware gangs . . . .”).
{: .fs-2}
<sup>13</sup>. Lawrence Abrams, *Ransomware Gang’s Script Shows Exactly the Files They’re After,* BLEEPING COMPUT. (Aug. 24, 2021, 2:16 PM) [hereinafter Abrams, *Ransomware Gang*] , https://perma.cc/9R85-CPDT. 
{: .fs-2}
<sup>14</sup>. *Id*. 
{: .fs-2}
<sup>15</sup>. *What Is Powershell?*, MICROSOFT (Oct. 5, 2021), https://perma.cc/ES7S-ZT5B. 
{: .fs-2}
<sup>16</sup>. *See Abrams, Ransomware Gang, supra* note 13. 
{: .fs-2}
<sup>17</sup>. *Id*.
{: .fs-2}
***

script left the network. If the modified or accessed files contain personal identifying information, the question becomes whether this automated script access is enough to trigger a data breach notification to an individual.

These new threat tactics removing data by automated means using software scriptingmust be reconciled with data breach notification laws that were written in a much simpler time of cybercrime. As discussed in Part III, these laws were not drafted with these largescale automated searches in mind.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/C/Comment-The-Necessary-Evolution-of-State-Data-Breach-Notification-Laws-Keeping-Pace-with-New-Cyber-Threats-Quantum-Decryption-and-the-Rapid-Expansion-of-Technology-1/">
INTRODUCTION</a></li><li> <a href="/docs/C/Comment-The-Necessary-Evolution-of-State-Data-Breach-Notification-Laws-Keeping-Pace-with-New-Cyber-Threats-Quantum-Decryption-and-the-Rapid-Expansion-of-Technology-2/">
I. EMERGING THREATS HAVE UPENDED DATA BREACH NOTIFICATION LAWS</a></li><li> <a href="/docs/C/Comment-The-Necessary-Evolution-of-State-Data-Breach-Notification-Laws-Keeping-Pace-with-New-Cyber-Threats-Quantum-Decryption-and-the-Rapid-Expansion-of-Technology-3/">
II. STATE DATA BREACH STATUTES FAIL TO ADDRESS AUTOMATED WIDESPREAD ACCESS AND UNCLEAR ACQUISITION</a></li><li> <a href="/docs/C/Comment-The-Necessary-Evolution-of-State-Data-Breach-Notification-Laws-Keeping-Pace-with-New-Cyber-Threats-Quantum-Decryption-and-the-Rapid-Expansion-of-Technology-4/">
III. EVOLUTION OF TECHNOLOGY, INCLUDING QUANTUM COMPUTING, REQUIRES CHANGES TO THE CURRENT STATE DATA BREACH NOTIFICATION REGIME</a></li><li> <a href="/docs/C/Comment-The-Necessary-Evolution-of-State-Data-Breach-Notification-Laws-Keeping-Pace-with-New-Cyber-Threats-Quantum-Decryption-and-the-Rapid-Expansion-of-Technology-5/">
IV. THE PUSH FOR FEDERAL LEGISLATION TO UNIFY A NOTICE STANDARD AND ADDRESS THESE CONCERNS</a></li></ul>

***

</div>
