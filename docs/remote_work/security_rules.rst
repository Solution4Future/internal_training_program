======================
Example security rules
======================

In todo..


Security of Software
====================

 - Use Linux or OSX with full disk encryption
 - Disable automatic login
 - Use unique password for each authentication method
 - Create complex passwords
 - Update your operating system and software as frequently as possible
 - Install only trusted software, add only trusted repositories to your repository list
 - Use automatic screen locker, always lock screen when you go away from computer
 - Don't give access to your account other people, use anonymous sessions or guest mode
 - If you notice something suspicious check all logs (OS logs, applications logs) and network traffic


Security of Passwords
=====================

  - create *unique* 10 characters passwords with lower and uper-case letters, numbers and specials characters
  - change your password regulary (once on 3 months)
  - use double authentication if this is possible (example: Gmail)
  - use passwords wallets (if you need) and use encription
  - don't use personal data in your password like dog name, child birthday
  - don't use words from dictionary
  - don't use security questions for password recovery
  - don't share your password with anyone
  - don't write your passwords on paper


Security of Source Code
=======================

  - use ssh keys to authorization with unique complex password
  - don't share your private key with anyone, save this only on encrypted disk
  - use encription disk
  - communicate with code repository only on safe internet connection(not in public wi-fi)
  - respect all of other security polices in this document
  - don't paste code snippets on GitHub, Bitbucket public repositories
  - don't share source code with others via chats, in emails etc..

Security of Correspondence and Collaboration
============================================

  - don't share credentials to any services on chats, in emails, source code etc..
  - close all windows with sensitive data, disable all popup/screen notification during screen sharing

Security of Mobile Devices
==========================

Your mobile devices is your rest area. Your bass will call you in emergency situation or send you sms:

  - use sreen lock, change your code frequently
  - don't use business mail account on your mobile devices
  - enable SMS notification from chat services (example: HipChat)
  - always login from online services in mobile browsers
  - don't store any sensitive information on your mobile device (specifications, internal documents etc..)
  - use "Find my iPhone" services (or similar)
  - use remote reset mobile device option


Security of Web Browsing
========================

  - Don't use public wi-fi or someone else computer to check information
  - Use latest version of your browser
  - During authentication check SSL
  - Block popups
  - Use only trusted extensions to your browser
  - Clear cookies and cache frequently
  - Check all suspicious activity by monitoring your logins
  - Don't give other people access to your browser, use guest mode in operation system
  - Don't save your passwords and logins in browser
  - Read all alerts
  - Read terms of services and privacy policy before you accept them
  - Raport all suspicious activity


Security of Backups
===================


Security of Development
=======================

  - use environment variables to store sensitive data and credentials
  - set correct emails in you settings
  - don't use debug mode on production and staging server
  - use debug mode on local environment