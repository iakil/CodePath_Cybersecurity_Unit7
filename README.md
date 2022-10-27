# Project 7 - WordPress Pen Testing

Time spent: **9** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pen Testing Report

### 1. (Required) Vulnerability Name or ID

- [ ] Summary: This attack requires admin access.
  - Vulnerability types: xss injection
  - Tested in version: 4.2
  - Fixed in version: 5.0
- [ ] GIF Walkthrough: 
<img src="File/cs.gif" alt="Q1">
- [ ] Steps to recreate: This doesn't require HTML and only requires an imbedded link with xss injected.
- [ ] Affected source code: imbedded link
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
  
### 2. (Required) Vulnerability Name or ID

- [ ] Summary: This attack requires admin access.
  - Vulnerability types: xss injection
  - Tested in version: 4.2
  - Fixed in version: 6.4
- [ ] GIF Walkthrough: 
<img src="File/cs.gif" alt="Q2">
- [ ] Steps to recreate: You'll need to access the html on the page and inject the code anywhere you want. Once the victim opens the page the XSS will run.
- [ ] Affected source code: HTML
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

### 3. (Required) Vulnerability Name or ID

- [ ] Summary: This attack requires admin access.
  - Vulnerability types: xss injection
  - Tested in version: 4.2
  - Fixed in version: 7.8
- [ ] GIF Walkthrough: 
<img src="File/cs.gif" alt="Q3">
- [ ] Steps to recreate: You'll need to access the html on the page and inject the code. Once the vicim opens the web page the xss will run.
- [ ] Affected source code: HTML
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)



## Notes
Had a big issue, when I was trunning vagrant with VM. Showed ip address distance error. After 2 hours, I figured out the issue. 
