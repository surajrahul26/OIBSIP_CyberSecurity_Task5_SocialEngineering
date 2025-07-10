# Social Engineering Attacks: Phishing, Pretexting & Baiting  
**Author:** Suraj Vishwakarma 
**Date:** 10 July 2025 

---

## 1. Introduction  
I was struck by how just **one phone call** led to a massive breach at Qantas—up to **6 million customers** had their personal data exposed through a vishing attack at a third-party call centre. This reminded me that our **human responses**, not just firewalls, are often the weakest link :contentReference[oaicite:1]{index=1}.

---

## 2. Types of Social Engineering Attacks  

### 2.1 Phishing  
- *Definition:* Bulk emails or SMS/messages that lure you into revealing credentials or clicking dodgy links.  
- *Example:* A fake “VPN” email tricked Twitter staff into giving up login details—led to high‑profile account takeovers in July 2020 :contentReference[oaicite:2]{index=2}.

### 2.2 Spear‑Phishing & Whaling  
- Targeted attacks aimed at specific individuals, usually execs.  
- In Twitter's hack, attackers phoned select staff, impersonated IT, and stole multi‑factor auth codes :contentReference[oaicite:3]{index=3}.

### 2.3 Vishing & Smishing  
- Voice (via phone) or SMS-based phishing.  
- Qantas breach was classic vishing—attackers spoofed a voice to access a vendor system :contentReference[oaicite:4]{index=4}.

### 2.4 Pretexting  
- Creating a fake identity or scenario to manipulate someone.  
- Example: Posing as IT helpdesk staff is a common pretext.

### 2.5 Baiting  
- Physical traps like infected USB drives left in break rooms—studies show almost everyone picks them up.

---

## 3. Case Studies  

### 🛫 Qantas Vishing Attack (July 2025)  
- **What happened:** A scammer impersonated staff to a Manila-based call centre, then accessed Salesforce platform with 6 million customer records :contentReference[oaicite:5]{index=5}.  
- **Impact:**
  - **Data exposed:** names, emails, phones, birthdates, frequent‑flyer numbers (no financial data).
  - **Consequences:** Reputation damage, regulatory investigations, customer alerts, share-price dip :contentReference[oaicite:6]{index=6}.

### 🐦 Twitter Phone-Spear Phishing (July 2020)  
- **What happened:** Attackers targeted specific Twitter staff, sent them to fake VPN and harvested credentials, bypassed MFA, accessed account tools, posted Bitcoin scams :contentReference[oaicite:7]{index=7}.  
- **Impact:**
  - High‑profile accounts hijacked; ~12.86 BTC (≈$117k) stolen; deep reputational hit.  
  - At least three arrests made :contentReference[oaicite:8]{index=8}.

---

## 4. Impact Analysis

| Case    | Data Stolen                                     | Reputational & Operational Consequences                  |
|---------|--------------------------------------------------|----------------------------------------------------------|
| Qantas  | 6M names, emails, phones, birthdates, miles     | Regulatory scrutiny; brand trust weakened; stock drop   |
| Twitter | Admin credentials + account control + BTC scam  | Massive public embarrassment; service locks & tweets paused |

---

## 5. Prevention Strategies  

### 5.1 Human-Centric Training  
- **Regular drills:** Simulated phishing, vishing, USB baiting.  
- **Role‑based awareness:** Teach call‑centre staff to verify callers via callback policies.

### 5.2 Technical Controls  
- **Email & SMS filtering** with AI support.  
- **MFA with phishing-resistant options** (e.g. FIDO keys).  
- **Endpoint detection & response (EDR)** and threat-intel feeds.

### 5.3 Verification Policies  
- Enforce strict caller ID validation for any unusual request.  
- Implement “call‑back” rules for high‑risk operations.

### 5.4 Vendor & Supply‑Chain Management  
- Thorough vetting for third-party call centres.  
- Regular audits and tabletop exercises with vendors.

### 5.5 Incident Response & Assurance  
- Quick isolation protocols for suspected breaches.  
- Clear customer communication rituals.

---

## 6. Conclusion  
What struck me most is that **software isn’t the sole defense**—even the most secure systems can fall if **humans are deceived**. With attackers now using AI-driven tools, deepfake voices, and highly tailored scams, our best defense is **ongoing awareness, layered verification, and zero‑blame training culture**.

---

## 7. References  
*Cite each source above using inline numbers or footnotes linking the news and papers I used.*

---

::contentReference[oaicite:9]{index=9}

::contentReference[oaicite:10]{index=10}
