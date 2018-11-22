# DNS_SEC

**How to run:**<br/>
python dnsserver.py<br/>
python dnssecclient.py

**Description**
Random domains and IP addresses are generated and stored in numpy records
1. dnsclient loops over 100 records randomly and sends the request to dnsserver to resolve the domain name
2. dnsserver receives request from client and asks dnssecserver to provide the ip address
3. it also verifies the signature of the domain name to make sure information is not altered on the way


