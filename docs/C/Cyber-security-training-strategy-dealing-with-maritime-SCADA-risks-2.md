---
layout: default
title: Importance of Cyber Security
parent: § Cyber security training strategy - dealing with maritime SCADA risks 
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

## Importance of Cyber Security
The contemporary era is very frequently referred to as “the information age”; cyber-attacks on the wider maritime industry (and especially on the relevant port IT systems) should no longer be considered hypothetical or simply the stuff of over-exaggerating analysts, resembling a fictional narrative. Probably a very strong “wake up” message was sent in June 2017, when the Maersk shipping company was hit by a cyber-attack from the purely destructive NotPetya virus (Boyes et all, 2020). The virus entered Maersk’s systems through a widely used piece of tax accounting software in Ukraine. Maersk was not the intended target for the attack, but the consequences for the company were very real. The virus spread through the company globally and made all their applications and data unavailable for several days. Real world operations, including its extremely important Rotterdam terminal, were seriously affected, or even completely crippled, with relevant financial losses being estimated at the level of $200-300 million. The Maersk story testifies how a system that fails in key ways becomes unusable, even if certain parts of it remain unaffected: Maersk's shipboard systems were fine, but there was no way to distribute their loads or take on new cargo (Dalaklis and Schröder-Hinrichs, 2019).

It is a self-explanatory fact that the NotPetya virus could attack the Maersk global network because it was loaded onto one unpatched computer operating in a single local office, which in turn was connected to the company’s global network. This incident shows the vulnerability of everyone to cyber-attacks: you do not even have to be the intended victim. On a positive note, Maersk could recover relatively quickly because it had already recognised that resilience and recovery processes are as important in terms of the wider Cyber Security framework as trying to prevent an attack. Being able to recover all your systems and data from secure backups within a very short timeframe of a successful cyber-attack will protect your business from potentially serious financial and the more important reputational damage. Spreading of viruses through the computer systems that are serving the wider needs of the maritime industry is just a small part of the complex equation. In other cyber security incidents, IT assets have been quite often infected with malware and in numerous occasions it has been recorded unintentional jamming or interference with wireless networks (Boyes et all, 2020).

In order to bring forward a widely accepted definition, “Cyber Security” can be described as “the collection of tools, policies, security concepts, security safeguards, guidelines, risk management approaches, actions, training, best practices, assurance and technologies that can be used to protect the cyber environment and organisation and user’s assets” (International Telecommunications Union (ITU), 2008). Within this definition, the “cyber environment” comprises the standalone computers and interconnected networks of both information and operational technology that use electronic, computer-based and wireless systems, including information, services, social and business functions that exist only in cyberspace. At the same time, the “organisation and user’s assets” includes connected and standalone computing devices, personnel, infrastructure, applications, services, telecommunication systems, and the totality of transmitted, processed or stored data in the cyber environment. Cyber security is not just about preventing hackers gaining access to systems and information. It also addresses the maintenance, integrity, confidentiality and availability of information and systems, ensuring business continuity and the continuing utility of cyber assets. Before moving to a different direction, it is worth clearly highlighting the fact that on board a modern ship there are numerous SCADA systems. With the help of Figure 2, an attempt to summarize all ICS that can be found on a modern vessel is taking place; a few indicative examples of interest are also listed next: Alarm and Monitoring System; Auxiliary Control System; Power Management System; Cargo Control System; Propulsion Control System; Ballast Automation System; Air Conditioning System; Anti–Heeling; Reefer Monitoring; Fire System; Main Engine Monitoring System. Furthermore, a representation of the IT environment supporting the conduct of a shipping company’s business and other activities, as well as how the use of these computers relates to maritime SCADA is provided.

![ICS on-board a vessel and the wider framework of maritime SCADA](https://statics.bsafes.com/images/papers/Cyber-security-training-strategy-dealing-with-maritime-SCADA-risks-fig-2.png)
*Figure 2* ICS on-board a vessel and the wider framework of maritime SCADA. Created by the authors, via adaption of certain slides from the presentation: Woudenberg, B. (2012). SCADA Right Now, Retrieved from https://slideplayer.com/slide/5703843/ June 2021

The main vulnerabilities that are related to SCADA systems are (Woudenberg, 2012; Nikitakos 2017): The adoption of standardized technologies with known vulnerabilities; The connectivity of many control systems via, through, within, or exposed to unsecured networks, networked portals, or mechanisms connected to unsecured networks (which includes the Internet); Implementation constraints of existing security technologies and practices within the existing control systems infrastructure (and its architectures); The connectivity of insecure remote devices in their connections to control systems; The widespread availability of technical information about control systems, most notably via publicly available and/or shared networked resources such as the Internet; Disrupt the operations of control systems by delaying or blocking the flow of information through the networks supporting the control systems, thereby denying availability of the networks to control systems’ operators and production control managers; Attempt, or succeed, at making unauthorized changes to programmed instructions within PLC, RTU, or DCS controllers, change alarm thresholds, or issue unauthorized commands to control station equipment; Send falsified information to control system operators either to disguise unauthorized changes or to initiate inappropriate actions; Modify or alter control system software or firmware such that the net effect produces unpredictable results (such as introducing a computer “time bomb”); Interfere with the operation and processing of safety systems; Many control systems are vulnerable to attacks of varying degrees. These attack attempts range from telephone line sweeps (a.k.a. “wardialing”), to wireless network sniffing (a.k.a. “wardriving”), to physical network port scanning, and to physical monitoring and intrusion (Nikitakos, 2017)

It is also necessary to mention that there are several types of exploiting maritime ICS/SCADA. A limited number of them is discussed next: **Direct physical damage to affected equipment and systems.** By exploiting an ICS, the controlled mechanism can fail with catastrophic results, damaging a single piece of equipment, interrupting a larger system, or disabling or destroying an entire ship; **Small-scale, local disruptions.** They can damage or interrupt individual systems or single ships within a single organization, without widespread impact beyond the affected function or service; **Injury or death to operators, passengers or the general public.** An incident can affect a single operator or a larger number of crewmembers or bystanders. Targeted attacks on a critical for safety equipment can result into a fire, or explosion that could injure or kill hundreds of people; **Catastrophic disruptions to the transportation system.** A vessel sunk in a shipping channel, an explosion at an oil or LNG facility, sabotage to canal locks, or a series of mishaps involving cargo container cranes in critical ports can have longterm impacts to the safety, stability and reliability of very crucial elements of the wider transportation system (Nikitakos, 2017; Boyes et al, 2020).

***

#### Table of Contents
{: .no_toc}
<ul><li> <a href="/docs/C/Cyber-security-training-strategy-dealing-with-maritime-SCADA-risks-1/">
Introduction</a></li><li> <a href="/docs/C/Cyber-security-training-strategy-dealing-with-maritime-SCADA-risks-2/">
Importance of Cyber Security</a></li><li> <a href="/docs/C/Cyber-security-training-strategy-dealing-with-maritime-SCADA-risks-3/">
Knowledge areas</a></li><li> <a href="/docs/C/Cyber-security-training-strategy-dealing-with-maritime-SCADA-risks-4/">
Proposed curriculum development</a></li><li> <a href="/docs/C/Cyber-security-training-strategy-dealing-with-maritime-SCADA-risks-5/">
Summary and Conclusion</a></li><li> <a href="/docs/C/Cyber-security-training-strategy-dealing-with-maritime-SCADA-risks-6/">
References</a></li></ul>

***

</div>
