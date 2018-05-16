# hardware/mailserver

Simple and full-featured [mail server](https://github.com/hardware/mailserver) as a set of multiple docker images includes :

* **Postfix** : a full set smtp email server
* **Dovecot** : secure imap and pop3 email server
* **Rspamd** : anti-spam filter with SPF, DKIM, DMARC, ARC, ratelimit and greylisting capabilities
* **Clamav** : antivirus with automatic updates and third-party signature databases
* **Zeyple** : automatic GPG encryption of all your e-mails
* **Sieve** : email filtering (vacation auto-responder, auto-forward...etc)
* **Fetchmail** : fetch e-mails from external IMAP/POP3 server into local mailbox
* **Rainloop** : web based email client
* **Postfixadmin** : web based administration interface
* **Unbound** : recursive caching DNS resolver with DNSSEC support
* **NSD** : authoritative DNS server with DNSSEC support
* **Træfik** : modern HTTP reverse proxy
* **SSL** : let's encrypt with auto-renewal (SAN and wildcard certificates), custom and self-signed certificates support
* Supporting multiple virtual domains over MySQL/PostgreSQL backend

## Introduction

This chart bootstraps a [hardware/mailserver](https://github.com/hardware/mailserver) deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.
