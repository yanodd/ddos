
---

# Notes on DDoS

---

## detection

- baseline(s) detection
    - various baselines calculated
    - abnormalities detected
- host-based detection
    - multi-threshold detection per DST host
    - trending attacks (e.g amplification flavors)
    - various popular misuses (e.g. TCP SYN, fragments etc)
    - per protocol / total traffic (bits/packets)
- employ fast detection all around

---

## mitigation - CS

![ICloud Signalling](http://138.otenet.gr/cs.jpg)

---

## mitigation - procedure

- auto-mitigation fires first w/ basic rules
- engineer adapts mitigation countermeasures to mitigate attack vectors
- indicative countermeasure list
    - TCP floods (SYN/RST etc)
    - all known amplification attacks
    - application-specific (e.g. DNS, HTTP, SIP etc)
    - zombies
    - black/white L3/L4 lists
    - payload (L7)
    - location policing
    more... 

---
