# Severity Levels (Pentesting)

## 🔴 High Severity
- CSP header missing entirely
- unsafe-inline in script-src
- unsafe-eval in script-src
- wildcard (*) in script-src or default-src
- frame-ancestors missing (clickjacking)

## 🟠 Medium Severity
- data: or blob: allowed
- default-src overly permissive
- object-src not set to 'none'
- base-uri missing

## 🟢 Low Severity
- CSP-Report-Only used instead of enforce
- report-to / report-uri absent
