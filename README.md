# 🦠 NotPetya Ransomware Attack – Cybersecurity Case Study

## 📌 Overview

This project presents an in-depth analysis of the **NotPetya cyberattack**, one of the most destructive ransomware incidents in modern history. Originating in Ukraine in June 2017, NotPetya quickly spread across global networks, impacting corporations, government agencies, and critical infrastructure worldwide.

Unlike typical ransomware, NotPetya was designed to **cause damage, not collect ransom** — making it a **wiper disguised as ransomware**. This assignment explores its origin, propagation method, payload behavior, and global impact, while offering insight into how similar attacks can be prevented in the future.

---

## 📄 Contents

- `NotPetya_Case_Analysis.pdf`  
  *Detailed writeup describing the attack, timeline, and impact.*  
- `Presentation_Slides.pdf` *(Optional)*  
  *Slide deck used for class presentation or training purposes.*  

---

## 🧬 Attack Breakdown

- **Initial Vector**: Compromised Ukrainian accounting software (*MeDoc*) pushed malware via a software update
- **Propagation**: Leveraged **EternalBlue** exploit (MS17-010) and **Mimikatz-style credential harvesting**
- **Payload**: Encrypted MFT (Master File Table), rendered machines inoperable
- **Ransom**: Demanded payment in Bitcoin, but recovery was virtually impossible
- **Key Behavior**:
  - No real intention to decrypt files
  - Rapid lateral movement in networks
  - Impacted patched and unpatched systems alike

---

## 🌍 Global Impact

- Estimated **$10 billion in damages**
- Major companies affected:
  - Maersk (shipping)
  - Merck (pharmaceuticals)
  - FedEx (logistics)
  - Rosneft (energy)
- Disrupted global supply chains and critical infrastructure

---

## 🧠 Lessons Learned

- Patch management is **critical**: NotPetya exploited an existing vulnerability (EternalBlue) that had been patched by Microsoft months earlier
- **Network segmentation** could have contained lateral movement
- **Third-party software supply chains** are high-risk vectors
- Regular **offline backups** and tested incident response plans can reduce impact

---

## 🔐 Cybersecurity Concepts Covered

- Ransomware vs. wipers  
- Lateral movement techniques (SMB, credential reuse)  
- Vulnerability exploitation (EternalBlue)  
- Incident response best practices  
- Supply chain compromise

---

## 💬 Personal Reflection

Analyzing the NotPetya attack deepened my understanding of **nation-state cyber warfare**, supply chain vulnerabilities, and how quickly threats can escalate when core security controls are missing. It highlighted how critical it is for companies — even those outside of targeted regions — to adopt **global security awareness** and **zero trust principles**.

As someone pursuing a career in cybersecurity, this case reinforced the importance of **patching, visibility, and resilience** — foundational elements in defending against modern threats.

---

## 🧷 References

- [US-CERT Alert on NotPetya](https://www.cisa.gov/news-events/alerts/2017/notpetya-malware)  
- [Wired: The Untold Story of NotPetya](https://www.wired.com/story/notpetya-cyberattack-ukraine-russia-code-crashed-the-world/)  
- [Microsoft MS17-010 Patch](https://technet.microsoft.com/en-us/library/security/ms17-010.aspx)

---

## 🙋‍♂️ About Me

I’m Jordan Butler, a cybersecurity learner with a background in education and leadership. This research was completed as part of my bootcamp training and reflects my growing focus on real-world threat analysis, detection, and prevention.
