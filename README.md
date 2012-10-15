Server Shield v1.0.5
=============

Server Shield is a lightweight method of protecting and hardening your Linux server. It is
easy to install, hard to mess up, and makes your server instantly and effortlessly resilient
to many basic and advanced attacks.

It's easy to maintain, automatically installs all dependencies, configures itself, and self-updates!
Support for servers with multiple IP addresses will be added soon.


Features
--------

* Firewall Hardening
* TCP Hardening
* Data Leakage Protection
* ICMP/Ping Flood Protection
* Rootkit Protection
* DoS Protection
* Spoof Protection
* SYN Flood Protection


Installation
------------

    git clone https://github.com/Brian-Holt/server-shield

    cd server-shield;chmod +x sshield;mv sshield /etc/init.d

    /etc/init.d/sshield start    


Requirements
--------
All requirements will be automatically installed and updated, as long as "yum" is installed.

* yum
* iptables
* nmap
* net-tools
* sed
* gawk
* git