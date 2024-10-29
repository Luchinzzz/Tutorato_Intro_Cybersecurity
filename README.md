# :closed_lock_with_key: Computer Security Laboratory 
In this repository you can find all the slides presented during the laboratory lessons of the Introduzione alla Sicurezza Informatica course. The laboratory exercises were taken from "Computer Networking: a Top Down Approach (Pearson), J.F. Kurose, K.W. Ross", you can find all the labs [here](https://gaia.cs.umass.edu/kurose_ross/wireshark.php).

## :memo: Description 
Link to the Wireshark lab pdf:
*   [HTTP v8.1](/HTTP/Wireshark_HTTP_v8.1.pdf)
*   [TLS v8.1](TLS/Wireshark_TLS_v8.1.pdf)
*   [pcap files 8.1](http://gaia.cs.umass.edu/wireshark-labs/wireshark-traces-8.1.zip)

The slides are based on the resources in the [references section](#books-references). Links to the slides:
* [HTTP](https://gaia.cs.umass.edu/kurose_ross/ppt-8e/Chapter_2_v8.2.pptx)
* [TLS](/TLS/Security_Network_TLS.pdf)
* [NAC and Wireless Network Security](/NAC-WirelessSec/NAC_Wireless_sec.pdf)

OpenVPN and Wireguard guides:
*   [Wireguard](https://www.makeuseof.com/vpn-wireguard/)
*   [OpenVPN](https://www.cyberciti.biz/faq/ubuntu-18-04-lts-set-up-openvpn-server-in-5-minutes/)

# :gear:  Setup
For these labs you need Wireshak installed in your device. For Windows and Mac you can download the installer [here](https://www.wireshark.org/#download), for Linux, the commands are as follows

```
# Debian based
apt install wireshark

# From RPMs under Red Hat and alike
yum install wireshark wireshark-qt

# Red Hat based
dnf install wireshark

```
Wireshark is already installed in Kali Linux, if you want a VM with Kali there is a simple guide to help you creating one. 
If you are unable to run Wireshark on a live network connection, you can download a packet trace [here](http://gaia.cs.umass.edu/wireshark-labs/wireshark-traces.zip).

## :books: References

* Kurose, J. F., & Ross, K. W. (2021). Computer networking: a top-down approach (8th ed.). Pearson.
* Stallings, W. (2017). Network security essentials: applications and standards. Pearson Education, Inc.
* Gössi, C. (2023, March 14). TLS Essentials 10: TLS cipher suites explained. Youtube Video. [link](https://www.youtube.com/watch?app=desktop&v=mFdDap9A9-Q&ab_channel=CyrillG%C3%B6ssi)
