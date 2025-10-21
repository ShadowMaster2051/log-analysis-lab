# log-analysis-lab

## Issue 1

**Log Entries:**

```plaintext
2023-02-17 09:34:01 192.168.1.211 62.128.197.131 UDP 51820 Allow 1440
```

**Description of log entries:** Private IP using VPN to connect with foreign external IP.

**Reason for concern:** Private network device used for unauthorized purposes, potentially connecting to malicious site.

**Potential impact:** Breach of security protocols, data compromised, malware introduced. 

**Possible explanations:** User utlizing VPN to go outside private network, possibly to access Scottish/UK media, or for malicious purposes. 

## Issue 2

**Log Entries:**

```plaintext
2023-02-17 09:34:03 192.168.1.27 45.137.80.15 TCP 41284 Deny 48
```

**Description of log entries:** Firewall denied connection attempt to unknown external IP.

**Reason for concern:** Potential malicious site, fraud. 

**Potential impact:** Could be fraudulent, seeking payment information, or introduce malware. 

**Possible explanations:** Could be blocking unknown legitimate website, or the site is malicious and keeps a low profile.

## Issue 3

**Log Entries:**

```plaintext
2023-02-17 09:34:14 192.168.1.49 216.109.119.63 TCP 25 Allow 7421 
```

**Description of log entries:** Private IP using email to contact external IP.

**Reason for concern:** Potential fraud or malware, user utilizing private device for unauthorized purposes. 

**Potential impact:** Could indicate data exfiltration, or other compromise. Malware could be introduced. Violation of company policy. 

**Possible explanations:** User is sending email to an online job board using a private network device. 


## Issue 4

**Log Entries:**

```plaintext
2023-02-17 09:34:16 192.168.1.37 19.89.143.11 UDP 67 Allow 256
```

**Description of log entries:** Private IP attempting to contact external IP.

**Reason for concern:** Private network device attempting to contact IP belonging to Ford Motor Company.

**Potential impact:**  Data exfiltration/compromise, breach of secure data practices, unauthorized use. 

**Possible explanations:** User may be attempting to browse vehicles for sale using private network device. 

## Issue 5

**Log Entries:**

```plaintext
2023-02-17 09:36:44 192.168.1.80 185.151.204.30 TCP 48127 Deny 48
```

**Description of log entries:** Firewall denied private IP connection to external IP.

**Reason for concern:** Private network attempting to access European site. 

**Potential impact:**  Has the potenial to be malware, or a fradulent site. 

**Possible explanations:** Legitimate site blocked by firewall rules, misclassification of threat, legitimately malware.

## Issue 6

**Log Entries:**

```plaintext
2023-02-17 09:34:27 192.168.1.142 43.250.192.131 TCP 80 Allow 1203
```

**Description of log entries:** Private network attempting to access Amazon.com external IP.

**Reason for concern:** User attempting to access online retailer using private network device. 

**Potential impact:** Introduction of malware, data exfiltration or compromise. 

**Possible explanations:** User likely attempting to shop online using private network device.

## Issue 7

**Log Entries:**

```plaintext
2023-02-17 09:34:29 192.168.1.142 133.242.174.247 TCP 80 Allow 1149
```

**Description of log entries:** Private network device attempting to contact foreign IP over HTTP.

**Reason for concern:** User attempting to reach Japanese site could be responding to malware or phishing attack. 

**Potential impact:** Data exfiltration, indrocuction of malicious programs. Data security compromised. 

**Possible explanations:** User may be performing suspiciously, else attempting to acceess Japanese media or shopping. 

## Issue 8

**Log Entries:**

```plaintext
2023-02-17 09:34:50 fdf8:f53b:82e4::53 fdf8:f53b:82e4:0:1652:14ff:fe0b:b71c TCP 22 Deny 0
```

**Description of log entries:** .

**Reason for concern:** Potential misconfiguration, attempted communication with seemingly unknown private IP. 

**Potential impact:** Could indicate IP spoofing attempt or an attempt to exfiltrate data. 

**Possible explanations:** Misconfiguration, IP spoofing IvP6 address from threat actor.  

## Issue 9

**Log Entries:**

```plaintext
2023-02-17 09:35:08 192.168.1.68 157.240.26.35 TCP 443 Allow 3462
```

**Description of log entries:** User attempting to access Facebook on private network device. 

**Reason for concern:**  User accessing social media while on company private network. 

**Potential impact:** Data compromised or exfiltrated, social media policy breached.

**Possible explanations:** User accessing Facebook; Firewall rules have not included this site's IP to block. 

## Issue 10

**Log Entries:**

```plaintext
2023-02-17 09:35:09 192.168.1.68 31.13.92.20 TCP 443 Allow 4103
```

**Description of log entries:** User attempting to contact Facebook Ireland on private network device.

**Reason for concern:** User accessing foreign social media while on private company network. 

**Potential impact:** Could be responding to malware/social engineering attempt, data exfiltrateed or compromised. Breach of social media policy. 

**Possible explanations:** User could be attempting to access media unavailable in U.S., or engaging in malicious or unsafe practices. 




