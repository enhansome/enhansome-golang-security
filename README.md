<br/>
<div align="center">

A curated list of awesome golang Security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

*List inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 499,470 | 🐛 106 | 📅 2026-08-21 list thing.*

Supported by: [GuardRails.io](https://www.guardrails.io)

</div>
<br/>

# Contents

* [Tools](#tools)
* [Educational](#educational)
* [Other](#other)
* [Contributing](#contributing)

# Tools

## Web Framework Hardening

* [secure](https://github.com/unrolled/secure) ⭐ 2,354 | 🐛 0 | 🌐 Go | 📅 2026-05-01 -  Secure is an HTTP middleware for Go that facilitates most of your security needs for web applications.
* [nosurf](https://github.com/justinas/nosurf) ⭐ 1,747 | 🐛 15 | 🌐 Go | 📅 2025-05-13 - CSRF protection middleware for Go.
* [gorilla/csrf](https://github.com/gorilla/csrf) ⭐ 1,207 | 🐛 34 | 🌐 Go | 📅 2025-04-14 - Provides Cross-Site Request Forgery (CSRF) prevention middleware for Go web applications & services.
* [gorilla/securecookie](https://github.com/gorilla/securecookie) ⭐ 727 | 🐛 11 | 🌐 Go | 📅 2023-11-08 - Encodes and decodes authenticated and optionally encrypted cookie values for Go web applications.
* [unindexed](https://github.com/jordan-wright/unindexed) ⭐ 29 | 🐛 2 | 🌐 Go | 📅 2021-12-07 - A drop-in replacement for `http.Dir` which disables directory indexing.
* [beego-security-headers](https://github.com/gosecguy/beego-security-headers) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2019-01-17 - beego framework filter for easy security headers management.

## Libraries

* [jwt-go](https://github.com/dgrijalva/jwt-go) ⚠️ Archived - Golang implementation of JSON Web Tokens (JWT).
* [httprobe](https://github.com/tomnomnom/httprobe) ⭐ 3,119 | 🐛 45 | 🌐 Go | 📅 2024-06-22 - Take a list of domains and probe for working HTTP and HTTPS servers.
* [paseto](https://github.com/o1egl/paseto) ⭐ 941 | 🐛 7 | 🌐 Go | 📅 2023-02-25 - Platform-Agnostic Security Tokens implementation in GO (Golang).
* [hsts](https://github.com/StalkR/hsts) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2024-10-03 - Go HTTP Strict Transport Security library.

## Static Code Analysis

* [gosec](https://github.com/securego/gosec) ⭐ 8,930 | 🐛 13 | 🌐 Go | 📅 2026-08-21 - Inspects source code for security problems by scanning the Go AST and matching it with a set of rules. Comes bundled in a Docker container [securego/gosec](https://hub.docker.com/r/securego/gosec).
* [gometalinter](https://github.com/alecthomas/gometalinter) ⚠️ Archived - Concurrently runs most of the existing go linters and normalizes their output.
* [safesql](https://github.com/stripe/safesql) ⚠️ Archived - Static analysis tool for Golang that protects against SQL injections. It does not seem to be actively maintained at the moment.
* [ChainJacking](https://github.com/Checkmarx/chainjacking) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2026-05-22 - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack.
* [CodeQL](https://securitylab.github.com/tools/codeql) - A tool that lets you query your code like data, in order to find vulnerabilities and bugs. See also [LGTM.com](https://lgtm.com) for pull request integration and running queries in the cloud.

## Vulnerabilities and Security Advisories

* [golang-announce](https://groups.google.com/forum/#!forum/golang-announce) - The golang release mailing list. Language-specific security issues are announced here.
* [GoCenter Security](https://jfrog.com/blog/gocenter-reveals-go-module-vulnerabilities-with-xray/) and [JFrog VSCode Extension for Go](https://marketplace.visualstudio.com/items?itemName=JFrog.jfrog-vscode-extension) - Free vulnerability data around Go Modules
* [snyk Vulnerability DB](https://snyk.io/vuln?type=golang) - Commercial but free listing of known vulnerabilities in libraries.
* [Common Vulnerabilities and Exposures](https://www.cvedetails.com/vulnerability-list/vendor_id-14185/Golang.html) - Vulnerabilities that were assigned a CVE. Covers the language and packages.
* [National Vulnerability Database](https://nvd.nist.gov/vuln/search/results?form_type=Basic\&results_type=overview\&query=golang\&search_type=all) - Golang known vulnerabilities in the National Vulnerability Database.

## Private Key Infrastructure

* [CloudFlare SSL](https://github.com/cloudflare/cfssl) ⭐ 9,462 | 🐛 336 | 🌐 Go | 📅 2026-04-24 - CFSSL is CloudFlare's PKI/TLS swiss army knife. It is both a command line tool and an HTTP API server for signing, verifying, and bundling TLS certificates.

# Awesome Educational with stars

## Hacking Playground

* [govwa](https://github.com/0c34/govwa) ⭐ 187 | 🐛 11 | 🌐 Go | 📅 2025-02-20 - A vulnerable golang application including the most common vulnerabilities found in web applications today.
* [Lambhack](https://github.com/wickett/lambhack) ⭐ 98 | 🐛 1 | 🌐 Go | 📅 2019-10-07 - A very vulnerable serverless application in AWS Lambda.

## Articles, Guides & Talks

* [OWASP Go - Secure Coding Practices](https://github.com/OWASP/Go-SCP) ⭐ 5,284 | 🐛 26 | 🌐 Go | 📅 2024-05-31 by Checkmarx - Go programming language secure coding practices guide.
* [Hacking with Go](https://github.com/parsiya/Hacking-with-Go) ⚠️ Archived - Hacking with Go for security professionals.
* [golang-tls](https://github.com/denji/golang-tls) ⭐ 1,330 | 🐛 4 | 📅 2020-11-20 - Simple Golang HTTPS/TLS Examples.
* [gosea](https://github.com/komand/gosea) - Go Secure Example Application (GOSEA).
* [Go - Secure Coding Practices](https://www.owasp.org/images/2/2b/Owasp-171123063052.pdf) by OWASP - \[PDF] Talk given by Sulhaedir at the OWASP Jakarta meetup.
* [Memory Security in golang](https://cryptolosophy.org/memory-security-go/) - Handling data securely in memory.
* [A Go Programmer's Guide to Secure Connections](https://www.youtube.com/watch?v=kxKLYDLzuHA) - \[Video] GopherCon 2018, Liz Rice.
* [ReDoS in Go](https://www.checkmarx.com/2018/05/07/redos-go/) by Checkmarx - Diving Deep into Regular Expression Denial of Service (ReDoS) in Go.
* [Attacking Go](https://blog.trailofbits.com/2019/11/07/attacking-go-vr-ttps/): A detailed description on Security assessment techniques for Go projects.

# Other

## Reporting Bugs

* [Go Security Policy](https://golang.org/security)

# Contributing

Found an awesome project, package, article, or another type of resources related to golang Security? Submit a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
