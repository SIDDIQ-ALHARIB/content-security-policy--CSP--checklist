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


## Full List of Security Headers Checked

- Content-Security-Policy
- Content-Security-Policy-Report-Only
- Strict-Transport-Security
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy
- Permissions-Policy
- Cross-Origin-Opener-Policy
- Cross-Origin-Embedder-Policy
- Cross-Origin-Resource-Policy
- CORS Response Headers
- Cookie Security (Secure, HttpOnly, SameSite)
- Deprecated: X-XSS-Protection, X-Webkit-CSP


## CSP Meta Tag

Content Security Policy can also be defined using an HTML meta tag:

```html
<meta http-equiv="Content-Security-Policy" content="default-src 'self';">
