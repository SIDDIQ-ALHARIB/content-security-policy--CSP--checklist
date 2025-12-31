# Content Security Policy (CSP) Checklist

A beginner-friendly, pentester-focused checklist for reviewing
**Content-Security-Policy (CSP)** and related HTTP security headers.

## What this covers
- CSP directive reference
- HTTP security headers list
- CSP via meta tag
- OWASP Top 10 mapping
- Severity levels for findings

⚠️ For **educational and ethical security testing only**.

## Quick Usage
1. Review a website’s headers with browser devtools or curl
2. Check each header from the lists below
3. Use severity levels to prioritize issues
4. Map issues to OWASP Top 10 risks


## Full Security Headers List Summary

### Core Security Headers
- Content-Security-Policy
- Content-Security-Policy-Report-Only
- Strict-Transport-Security
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy
- Permissions-Policy

### Cross-Origin / Isolation Headers
- Cross-Origin-Opener-Policy
- Cross-Origin-Embedder-Policy
- Cross-Origin-Resource-Policy

### CORS Headers
- Access-Control-Allow-Origin
- Access-Control-Allow-Methods
- Access-Control-Allow-Headers
- Access-Control-Allow-Credentials
- Access-Control-Max-Age

### Cookie Security Attributes
- Secure
- HttpOnly
- SameSite

### Deprecated / Legacy Headers
- X-XSS-Protection
- X-Content-Security-Policy
- X-Webkit-CSP


## Bonus Tips (Real Security)

- Use online tools to test your checklist against real websites
- Compare expected headers with actual responses
- Practice on intentionally vulnerable labs and test sites

## Content Notice

This repository is an independent educational checklist.
All header and directive names are industry standards.
Content is summarized in original wording and does not copy official specifications.


## CSP Meta Tag

Content Security Policy can also be defined using an HTML meta tag:

```html
<meta http-equiv="Content-Security-Policy" content="default-src 'self';">

