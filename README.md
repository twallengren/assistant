# Toren’s Assistant — informational website

Static homepage and privacy policy. No application code, credentials or user records belong here.

## Hosting
GitHub Pages: deploy from main, repository root.
Intended custom domain: assistant.teedubz.online.
After configuring Pages, add a CNAME record at the DNS provider:
- Host: assistant
- Target: twallengren.github.io

Then configure the Pages custom domain and enable HTTPS after certificate provisioning. Verify domain ownership through GitHub before routing DNS where possible. Do not change the apex domain or Jam Night DNS.

## Privacy review
The policy describes personal assistant data processing. Verify each configured AI service’s data-use settings and terms comply with Google's Limited Use requirements before sending Google user data. Publication is not Google verification or proof of compliance.

## Local preview
Run `python3 -m http.server 8080` and open http://localhost:8080/.
