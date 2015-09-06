Supermicro IPMI/BMC Cleartext Password Scanner v20140622 by 1N3
https://crowdshield.com
Usage: sh supermicro_scan.sh <CIDR|IP|showdan> [proxy]

ABOUT:
Supermicro’s implementation of IPMI/BMC allows remote, unauthenticated attackers to
request the file PSBlock via port 49152. This plain text password file contains IPMI
username and password information. This script allows users to scan their networks
check for vulnerable systems that require patching.

USAGE:
./supermicro_scan.sh 74.200.8.237 - Single host scan
./supermicro_scan.sh 74.200.0.0/16 proxy - Subnet scan with proxy
./supermicro_scan.sh showdan - Search for vulnerable servers on ShowdanHQ

