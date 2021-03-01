# hacking-snippets
Useful snippets and links for hacking competitions. Work in progress

# Table of Contents
1. [Recconnaissance](#Recconnaissance)
2. [Enumeration](#Enumeration)
3. [Exploitation](#Exploitation)
4. [PrivEsc](#PrivEsc)



## Recconnaissance

### Useful links
- [peoplefinder](https://peoplefinder.com) - Information about Persons
- [who.is](https://who.is) - Domain lookup
- [sublist3r](https://github.com/aboul3la/Sublist3r) - Subdomain enumeration
- [hunter.io](https://hunter.io/) - Find emails associated with domain
- [builtwith.com](https://builtwith.com/) - See what tech the site is built with
- [wappalyzer](https://www.wappalyzer.com/) - Similar to builtwith
- [viewdns.info](https://viewdns.info) - Lookup a lot of information regarding domains and ip.


## Enumeration

### NMAP
It is often useful to do two nmap scans - one for low hanging fruit (quick), and one that can run in the background and scan all ports.

Quick: `nmap -sC -sV -oA quick.nmap <target ip>`

Long: `nmap -sC -sV -oA -p- full.nmap <target ip>`

### Dir scans

**Dir scan**

**VHOST scan**

### Nikto

## Exploitation


## PrivEsc

### Useful links
- [gtfobins](https://gtfobins.github.io/) 
