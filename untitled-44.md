# DNS \(Domain Name System\)

Some other [Network Layer](untitled-14.md) features which are related to IP Routing are DNS, ARP & PING.

* Domain Name System is a method which TCP/IP uses which lets the computers find the IP Address of a specified listed hostname.
* It was developed for the ease of both computers \(who understands only numbers while communicating\) & Humans who are comfortable in remembering Names as compared to Numbers. 

    Hence, DNS resolves names into the matching IP Address.

* The mapping of DNS IP & Domain names are stored in DNS Server.
* Before sending a packet to the Destination Address PC first sends a DNS Query asking the DNS Server for the IP Address of a specified Domain Name & in return DNS Server sends a DNS Reply which lists the Domain Name's IP Address. Now the computer can send the packet to the specific IP Address of that Hostname.
* DNS Server across the globe work together to ask & resolve the IP Addresses of the Requested Domain Name. DNS follows specific Standards & Protocols for the text name used across the globe. 

## Reference:

CCNA 200-301 OCG, Volume 1, Pg. 76-77 - Wendell Odom.
