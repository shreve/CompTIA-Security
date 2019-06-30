Threats, Attacks, and Vulnerabilities
=====================================

This section covers different ways an information system can be
attacked, how to detect compromises, and the impact of these actions.

## 1.1. Given a scenario, analyze indicators of compromise and determine the type of malware.

This section covers various types of malware and their attributes.

### Types of Malware

* **Viruses** propogate by attaching themselves to other pieces of
  executable code.
* **Worms** penetrate systems or networks and replicate themselves
  inside.
* **Polymorphic** malware modifies its own code so that it cannot be
  detected by antivirus software.
* **Armored** malware is built to be difficult to decompile so that it
  cannot be analyzed by security researchers.
* **Crypto-malware** encrypts useful files so that the victim cannot
  access them.
* **Ransomware** is crypto-malware that asks for a ransom in exchange
  for the decryption key.
* **Trojans** disguise themselves as useful software. They may or may
  not actually perform their cover use.
* **Rootkits** are software designed to modify the operating
  system. They were originally created as a tool for error recovery or
  other applications like DRM, but were adopted into malware.
* **Keyloggers** log all of a user's keystrokes. This kind of software
  is only considered malware if the user is unaware of it and not
  under the user's control.
* **Adware** is software which displays advertisements to the
  user. This software is considered malware if the user has not agreed
  to view the advertisements.
* **Spyware** is software which reports on the activities of the user
  to another party. This can be legitimate like anti-cheating spyware
  in video games, but is often malware intended to steal the victim's
  information.
* **Bots** are remotely-controlled software. If the control software
  is controlling many bots, that is referred to as a botnet. These may
  be legitimate, like in the case of installing operating systems on
  many devices, or malware if the bots are malicious.
* **RAT** stands for remote access trojan. These trojans are designed
  specifically to grant remote access to a computer without the
  victim's knowledge.
* **Logic Bomb** refers to a malicious piece of code that lies dormant
  until some logical condition is met.
* **Backdoors** are methods for alternative access to a program for
  use in the event that regular access has been revoked.

### Examples

* [WannaCry](https://en.wikipedia.org/wiki/WannaCry_ransomware_attack)
  (May 2017) ransomware cryptoworm exploited a vulnerability in
  Windows to encrypt whole systems and demand a ransom paid in Bitcoin.
* [CryptoLocker](https://en.wikipedia.org/wiki/CryptoLocker)
  (September 2013) ransomware trojan that targets Windows and
  propogated via email attachments and botnets.
* [Sobig](https://en.wikipedia.org/wiki/Sobig) (August 2003) trojan
  worm that infected millions of Windows computers disguised in email
  attachments
* [Zotob](https://en.wikipedia.org/wiki/Zotob) (August 2005) worm that
  was estimated to cost an average of $97,000 and 80 hours to cleanup
  per company affected.

### Indicators of Compromise

All sorts of abnormal activity can be an indicator of compromise:
network activity, disk activity, database activity, etc. No one attack
will trigger unusual activity in all of these areas, but careful
monitoring of these aspects will likely detect most of them, and could
potentially catch an intrusion or attack before any real harm is done.

## 1.2. Compare and contrast types of attacks.

This section covers attacks at various levels of the software stack
from the software itself to the infrastructure it runs on to the
people developing and administrating the software.

### Social Engineering

Social engineering is an attack on the human element. It generally
involves deceiving a human with priviledged access to software or data
the attacker wants. Good social engineers know how to exploit average
human behavior and emotions to gain access to what they want.

The best way to prevent social engineering attacks is to make sure the
entire team is aware of social engineering and how these types of
attacks can be implemented. Everyone should know the process for
validating someone's identity and authorization. Proving one's
credentials and not holding doors open should become standard faire.

Here are some types of social engineering attacks:

* **Phishing** is when an attacker pretends to be a trusted authority
  to gain some desired information. The most common phishing is
  fraudulent emails linking to a fake login page to gain the victim's
  credentials for another software.
* **Spear Phishing** is phishing targeting a specific group.
* **Whaling** is spear phishing high-value people within an
  organization like C-level executives. These are typically
  hand-crafted for a single target.
* **Vishing** is phishing that takes place over the phone or VoIP.
* **Tailgating** is following behind someone with legitimate
  credentials to gain access to a restricted area. This relies on the
  typical behavior of holding doors open for those behind you to be
  polite.
* **Impersonation** can be used in many different contexts to gain
  someone's trust in order to get valuable information from
  them. Offline they can pretend to be a boss, a tech support agent,
  a contractor with the company or some other person that should be
  helped. Online, attackers can impersonate the user's browser or
  operating system with crafted popups and alerts.
* **Dumpster Diving** is going through the target's trash in order to
  find valuable information.
* **Shoulder Surfing** is obtaining information by surreptitiously
  observing the target. This is typically things like watching them
  input their ATM pin or type in a password.
* A **Hoax** can weaken security by convincing users to take actions
  that put them at risk.
* **Watering Hole Attack** refers to targeting a website known to be
  frequented by the real target.

#### Examples

* [Naoki
  Hiroshima](https://medium.com/@N/how-i-lost-my-50-000-twitter-username-24eb09e026dd)
  (January 2014)
  had his valuable twitter handle stolen after an attacker executed a
  successful impersonation attack against his GoDaddy account.
* [CCleaner](https://www.ccleaner.com/news/blog/2017/9/18/security-notification-for-ccleaner-v5336162-and-ccleaner-cloud-v1073191-for-32-bit-windows-users)
  (2017-2018) was the target of a watering hole attack actually
  targeting for security-minded individuals.
* Mr. Robot (2015) (S01E05) Elliot creates a fake Wikipedia article
  featuring his picture to pretend to be a tech billionaire in order
  to pressure an employee at a data warehouse facility to give him
  access to the building.


### Application / Service Attacks

### Wireless Attacks

### Cryptographic Attacks

## 1.3. Explain threat actor types and attributes.

## 1.4. Explain penetration testing concepts.

## 1.5. Explain vulnerability scanning concepts.

## 1.6. Explain the impact associated with types of vulnerabilities.
