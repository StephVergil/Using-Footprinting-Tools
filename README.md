# Using Footprinting Tools

[Project](https://github.com/StephVergil/Using-Footprinting-Tools/blob/main/HW%204%20Using%20Footprinting%20Tools.docx)

## What are the IP addresses and name servers listed for the domains?

### gob.mx
- **IP Address:** N/A (Privacy and security settings may obscure the IP address.)
- **Name Servers:**
  - m.mx-ns.mx – 200.94.176.1
  - e.mx-ns.mx – 189.201.244.1
  - x.mx-ns.mx – 201.131.252.1
  - i.mx-ns.mx – 207.248.68.1
  - c.mx-ns.mx – 192.100.224.1, 2001:1258:0:0:0:0:0:1
  - o.mx-ns.mx – 200.23.1.1
- **Registrant, Administrative, and Technical Contact:** Network Information Center, S.A. de C.V. (Monterrey, Nuevo Leon, Mexico)

### tccd.edu
- **IP Address:** 64.28.255.100
- **Name Servers:**
  - pdns82.ultradns.net
  - pdns82.ultradns.com
  - pdns82.ultradns.org
  - pdns82.ultradns.biz
- **Administrative Contact:**
  - Name: Richard Sullivan  
  - Email: richard.sullivan@tccd.edu  
  - Phone: +1.817.515.1821  
  - Address: 1500 Houston, Fort Worth, TX 76102, USA
- **Technical Contact:**
  - Name: Suresh Venugopal  
  - Email: suresh.venugopal@tccd.edu  
  - Phone: +1.817.515.5800  
  - Address: 300 Trinity Campus Circle, Fort Worth, TX 76102, USA

### tarrantcountytx.gov
- **IP Address:** 192.84.52.206
- **Name Servers:**
  - cbru.br.ns.els-gms.att.net
  - cmtu.mt.ns.els-gms.att.net
  - ns3.tarrantcountytx.gov
  - ns4.tarrantcountytx.gov

### fbi.gov
- **IP Addresses:**
  - 104.16.148.244
  - 104.16.149.244
  - 2606:4700::6810:94f4 (IPv6)
  - 2606:4700::6810:95f4 (IPv6)
- **Name Servers:**
  - ns-cloud-e1.googledomains.com
  - ns-cloud-e2.googledomains.com
  - ns-cloud-e3.googledomains.com
  - ns-cloud-e4.googledomains.com

---

## How can the information from domain records be used?

### Hackers
- **Spearphishing:** Visible personal names and emails in domain records can be used to send fake emails and steal information.
- **Reconnaissance:** Exposed IPs and name servers help attackers map networks and identify vulnerabilities.
- **DDoS Attacks:** If IPs are available, attackers can target servers with DDoS attacks to disrupt services.

### Ethical Hackers
- **Vulnerability Testing:** Use IPs and name servers to locate and fix security flaws before exploitation.
- **Network Monitoring:** Track IP traffic to detect suspicious activity and respond to potential threats.
- **Incident Response:** Access to network details allows quick mitigation during cyberattacks.

---

## Domain Exposure Analysis

- **tccd.edu:** Most exposed, with detailed employee and network information, making it highly vulnerable to spearphishing and network attacks.
- **gob.mx:** Shares network data but no personal details, reducing phishing risk but remaining vulnerable to network-based attacks.
- **tarrantcountytx.gov:** Similar to gob.mx, sharing technical data while protecting personal details.
- **fbi.gov:** Most secure, offering minimal exploitable information, protecting against most common attacks.
