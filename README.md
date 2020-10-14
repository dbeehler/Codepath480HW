# Project 7 - WordPress Pentesting

Time spent: **10** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability CVE:2015-3440
  - [ ] Summary: In version 4.2 you can add XSS into a comment box located on the website. I did this by simply putting a html button into the comment that when clicked generates a Javascript alert.
    - Vulnerability types: WEBAPP
    - Tested in version: 4.2
    - Fixed in version: 4.2.1+?
  - [ ] GIF Walkthrough: <img src="screenfetch.gif" alt="WordPress XSS">
  - [ ] Steps to recreate: insert any Javascript code into a comment and reload the page.
  - [ ] Affected source code: 
    - [Link 1](https://www.exploit-db.com/exploits/36844)
1. (Required) Wordpress Popup Builder 3.49 - Persistent Cross-Site Scripting - EDB-ID: 47518
  - [ ] Summary: This plugin allows you to add a popup to any post on a WP website.
    - Vulnerability types: WEBAPP
    - Tested in version: 3.49
    - Fixed in version: I tried it on the latest version and it still works
  - [ ] GIF Walkthrough: <img src="exploit3.gif" alt="Popup Builder XSS">
  - [ ] Steps to recreate: install popup builder, create a popup with code in the title, create a page or post in WP, the XSS with trigger
  - [ ] Affected source code: https://www.exploit-db.com/exploits/47518
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) CVE:2019-17671
  - [ ] Summary: You are able to view Private posts by adding a variable to the URL
    - Vulnerability types: WEBAPP
    - Tested in version: 4.1.31
    - Fixed in version: 5.2.4
  - [ ] GIF Walkthrough: <img src="exploit2.gif" alt="WordPress URL attack">
  - [ ] Steps to recreate: add ?static=1&order=asc to the end of your URL and you can access hidden posts
  - [ ] Affected source code:
    - [Link 1](https://www.exploit-db.com/exploits/47690)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)


## Notes

Describe any challenges encountered while doing the work
