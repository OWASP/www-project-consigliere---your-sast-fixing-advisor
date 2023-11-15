---

layout: col-sidebar
title: OWASP Consigliere - Your SAST Fixing Advisor
tags: example-tag
level: 2
type: documentation
pitch: A very brief, one-line description of your project

---
Welcome to Consigliere, your SAST fixing advisor!

### Project Goal

Standardization of the available fixing techniques of code issues detected by the industry-leading SAST tools.

### Project Description

There are usually many ways to fix security vulnerabilities to eliminate risk.
However, when it comes to Static Code Analysis, different SAST tools expect different mitigation techniques. As a result, developers do not have a clear path to fixing a finding in a way that assures the SAST tool will not recognize the issue anymore.

This document is aimed to standardize the valid techniques available for fixing common SAST findings.
It has two main consumers:

1. Developers and security teams - will be able to fix SAST findings easily and with a clear path to ensure the issue isn't re-detected after the fix.
2. SAST tools - will be able to support the different valid fix techniques available for the findings they produce, and by that eliminate mass amounts of false positive issues they report to their customers.

### Project Roadmap

1. Create a document with guidelines and code samples of vulnerable codes and valid techniques to fix, for common findings - SQLi, XSS, Path Traversal, CMDi, SSRF, XXE, and more.
2. Invite developers and security enthusiasts to add their feedback and contribute more issue types and/or mitigation techniques.
3. Collaborate with the industry SAST leaders to promote the idea of a clear path for fixing SAST findings, so everyone can benefit and save precious time.

### Additional Comments

This is an open-source, free project, that's aimed to help anyone who writes or maintains code.
This project will be executed in full collaboration with any actor in the industry that manages vulnerability detection or auto-remediation, who is interested in participating.
