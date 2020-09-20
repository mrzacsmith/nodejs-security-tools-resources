# Learn to be more secure! This is a open source list of security references is for NodeJS, JavaScript, NPM, and other frameworks that are Javascript based!

<img src='https://res.cloudinary.com/devsec/image/upload/v1600570113/hacker_cqclsh.png' alt='hacker on computer' />

# Contents

- [Tools](#projects)
  - [Web Framework Hardening](#web-framework-hardening)
  - [Static Code Analysis](#static-code-analysis)
  - [Input/Output Validation](#input-validation--output-encoding)
  - [Secure Composition](#secure-composition)
  - [CSRF](#csrf)
  - [XSS](#xss)
  - [Vulnerabilities and Security Advisories](#vulnerabilities-and-security-advisories)
  - [Security Hardening](#security-hardening)
- [Security Incidents](#security-incidents)
- [Educational](#educational)
  - [Hacking Playground](#hacking-playground)
  - [Articles](#articles)
  - [Research Papers](#research-papers)
  - [Books](#books)
  - [Other Lists](#other-lists)
- [Companies](#companies)

# Tools

## Web Framework Hardening
- [Helmet](https://www.npmjs.com/package/helmet) - Helmet helps you secure your Express apps by setting various HTTP headers.


## Static Code Analysis
- [eslint-plugin-security](https://www.npmjs.com/package/eslint-plugin-security) - ESLint rules for Node Security. This project will help identify potential security hotspots, but finds a lot of false positives which need triage by a human.


## Input Validation & Output Encoding
- [validator](https://github.com/chriso/validator.js) - An npm library of string validators and sanitizers.
- [Reverse shell on NodeJS application](https://wiremask.eu/writeups/reverse-shell-on-a-nodejs-application/)


## Secure Composition

## XSS
- [Google Learn XSS](https://www.google.com/about/appsecurity/learning/xss/)

## CSRF
- [csurf](https://www.npmjs.com/package/csurf) - Node.js CSRF protection middleware.


## Vulnerabilities and Security Advisories.
- [check-my-headers](https://github.com/UlisesGascon/check-my-headers) - Fast and simple way to check any HTTP Headers.
- [is-website-vulnerable](https://github.com/lirantal/is-website-vulnerable/) - finds publicly known security vulnerabilities in a website's frontend JavaScript libraries.

## Security Hardening
- [tor-detect-middleware](https://github.com/UlisesGascon/tor-detect-middleware) Tor detect middleware for express
- [10 Tools to Secure NodeJS Applications Online](https://geekflare.com/how-to-secure-nodejs/)



# Security Incidents

NodeJS, JavaScript, and NPM related communities, groups, and materials related to past security events. 

* **is-promise** - one-liner library breaks an ecosystem. References: [[Forbes Lindesay - Maintainer post-mortem]](https://medium.com/javascript-in-plain-english/is-promise-post-mortem-cab807f18dcc), [[snyk's postmortem]](https://snyk.io/blog/why-did-is-promise-happen-and-what-can-we-learn-from-it/)
- [BadJS](https://badjs.org/) - a repository of malicious JavaScript that has been found in websites, extensions, npm packages, and anywhere else JavaScript lives.

# Educational

## Hacking Playground
 - [OWASP NodeGoat](https://github.com/OWASP/NodeGoat) - The OWASP NodeGoat project provides an environment to learn how OWASP Top 10 security risks apply to web applications developed using Node.js and how to effectively address them.
 - [OWASP Juice Shop](https://github.com/bkimminich/juice-shop) - The OWASP Juice Shop is an intentionally insecure webapp for security trainings written entirely in Javascript which encompasses the entire OWASP Top Ten and other severe security flaws.
 - [DomGoat](https://domgo.at/cxss/intro) - Client XSS happens when untrusted data from sources ends up in sinks. Information and excercises on different sources, different sinks and example of XSS occuring due to them in the menu on the left-hand side. 

## Articles
 - [A Roadmap for Node.js Security](https://nodesecroadmap.fyi/)
 - [10 npm security best practices](https://snyk.io/blog/ten-npm-security-best-practices/)
 - [OWASP Cheat Sheet Series - Node.js Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Nodejs_security_cheat_sheet.html)
 - [Implement Access Control in Node.js](https://blog.nodeswat.com/tagged/cybersecurity)


## Books
- [Secure Your Node.js Web Application: Keep Attackers Out and Users Happy](https://www.amazon.com/Secure-Your-Node-js-Web-Application-ebook/dp/B01BPPUP30) by Karl Duuna, 2016

## Other Lists
  - [What a Pwnly Day: Learn NodeJS](https://canyoupwn.me/en-awesome-learn-nodejs/)

# Companies

- [Shieldfy](https://shieldfy.io) - Automated security code review for your code and dependencies.

# Contributing
We value your contributions, follow the [guidelines](/CONTRIBUTING.md) and support Open Source. This is a great first time project to contirbute year around and during Hacktoberfest! 

### Credits
This was made to assist new developers to get started in contributing to Open Source, and this list was inspired by [Twitter](https://twitter.com/liran_tal), drop by and say thanks! 

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
