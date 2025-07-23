# Wireshark Traffic Analysis 

This project focuses on analyzing a captured PCAP file using **Wireshark** to identify login traffic and extract sensitive credentials transmitted in cleartext.

#  Objectives

- Understand how network traffic reveals information.
- Use filters in Wireshark to isolate important packets.
- Extract **HTTP credentials** from unencrypted communication.
- Demonstrate real-world risks of insecure transmission.

##  Tools Used

- Wireshark (Packet Analyzer)
- PCAP File
- Display Filters (e.g. `http`, `http.request`, `frame contains`)

##  Key Steps

1. Loaded `.pcap` file into Wireshark.
2. Applied filters to identify `POST` login requests.
3. Inspected `Info` and `Line-Based Text Data` for username/password.
4. Extracted the credentials and documented findings.

##  Findings

- Captured `POST /login` HTTP requests.
- Extracted plaintext credentials:
Mastered filtering and packet inspection in Wireshark.
- Gained hands-on experience with HTTP traffic dissection.
- Understood how attackers can leverage unencrypted data.
