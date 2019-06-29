Threats, Attacks, and Vulnerabilities
=====================================

This section covers different ways an information system can be
attacked, how to detect compromises, and the impact of these actions.

## 1.1. Given a scenario, analyze indicators of compromise and determine the type of malware.

This section covers various types of malware and their attributes.

### Definitions

**Viruses** operate by attaching themselves to other pieces of
executable code. When the other code is ran, the virus will do it's
nefarious work as well as spread to other executables. Antivirus
software commonly searches for repeated bits of code found in viruses,
so malware developers have created **polymorphic** code which changes
itself in order to be harder to detect. These developers have also
created **armored** malware, which has been made harder to
decompile. Without the ability to decompile, security researchers
can't find these code signatures for detecting malware.

**Crypto-malware** encrypts files so that the victim cannot access
them. If the intention is to ask for money in exchange for the
decryption key, this is called **Ransomware**. If no ransom is
requested, or if it is not paid, these files, potentially entire
systems, will be unrecoverable.

A **Worm** is malware designed to penetrate systems or networks and
replicate themselves inside. The difference between a worm and a virus
is that a worm does not need to attach itself to another execuable in
order to run.

A **Trojan** hides it's malicious behavior with some non-malicious
behavior.

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

## 1.2. Compare and contrast types of attacks.

## 1.3. Explain threat actor types and attributes.

## 1.4. Explain penetration testing concepts.

## 1.5. Explain vulnerability scanning concepts.

## 1.6. Explain the impact associated with types of vulnerabilities.
