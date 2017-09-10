## Spaghetti - Web Application Security Scanner
![build](https://img.shields.io/badge/build-passing-green.svg) ![python](https://img.shields.io/badge/python-2.7-green.svg)  ![license](https://img.shields.io/badge/License-GPLv3-brightgreen.svg)

![logo](https://raw.githubusercontent.com/m4ll0k/Spaghetti/master/screenshots/logo.png)

## Description
Spaghetti is a web application security scanner tool. It is designed to find various default and insecure files, configurations and misconfigurations. Spaghetti is built on python2.7 and can run on any platform which has a Python environment.

## Installation
```
$ git clone https://github.com/m4ll0k/Spaghetti.git
$ cd Spaghetti 
$ pip install -r requirements.txt
$ python spaghetti.py --help
```

## Features
- Fingerprints
  - Server
  - Web Frameworks (CakePHP,CherryPy,Django,...)
  - Web Application Firewall (Waf) (Cloudflare,AWS,Barracuda,...)
  - Content Management System (CMS) (Drupal,Joomla,Wordpress,Magento)
  - Operating System (Linux,Unix,Windows,...)
  - Language (PHP,Ruby,Python,ASP,...)

- Discovery:
  - Apache
    - Apache (mod_userdir)
    - Apache (mod_status)
    - Apache multiviews
    - Apache xss
  - Apache Enumeration Users
  - Apache XSS
  - Apache ModStatus
  - Backdoors
  - Backup
  - Captcha
  - Common Directories
  - Common Files
  - Cookie Security
  - Multiple Index
  - Information Disclosure (Emails and Private IP)

## Screenshots
![screen1](https://github.com/m4ll0k/Spaghetti/blob/master/screenshots/screenshot_1.png)
![screen2](https://github.com/m4ll0k/Spaghetti/blob/master/screenshots/screenshot_2.png)
![screen3](https://github.com/m4ll0k/Spaghetti/blob/master/screenshots/screenshot_3.png)
