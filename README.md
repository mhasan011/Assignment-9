# Honeypots Used:

Dionaea "mhn-honeypot-1"

Snort "mhn-honeypot-2"

# Issues encountered:
Needed to configure mnemosyne file to establish communication between the honeypots and the mhn-admin server.

# Data Collected:

Total Attacks: 2030

Top 5 IPs:

  35.225.59.177 (366 attacks) (USA)
  
  162.243.160.49 (61 attacks) (USA)
  
  104.248.6.137 (59 attacks)  (USA)
  
  188.166.3.86 (52 attacks)  (Netherlands)
  
  104.248.29.221 (44 attacks)  (USA)



Top 5 Ports:

8088 (524 times)

23 (122 times)

445 (100 times)

5060 (88 times)

81 (37 times)



TOP 5 Honey Pots:

dionaea (1,761 attacks)

snort (269 attacks)



TOP 5 Sensors:

mhn-honeypot-1 (1,761 attacks)

mhn-honeypot-2 (269 attacks)



TOP 5 Attacks Signatures:

ET DROP Dshield Block Listed Source group 1 (132 times)

ET COMPROMISED Known Compromised or Hostile Host Traffic TCP group 15 (10 times)

ET CINS Active Threat Intelligence Poor Reputation IP TCP group 70 (9 times)

ET SCAN Suspicious inbound to mySQL port 3306 (9 times)

ET SCAN Sipvicious User-Agent Detected (friendly-scanner) (9 times)

# Malware Collected: 
I didn't find the malwares yet. However, I am gonna keep up the honeypots couple of hours more. If I find any malware, I'll update here.


Update: I found some for snort(honeypot-2) but didn't get dor dionaea yet. I attaced a screenshot.

# Sessions JSON:

/session.json

# Unresolved Issues: NONE
