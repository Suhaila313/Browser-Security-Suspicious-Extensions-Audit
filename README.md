# Browser Security: Suspicious Extensions Audit

# Overview
This task involved identifying and removing potentially harmful browser extensions to improve security and performance. The process included reviewing permissions, assessing risks, and documenting findings.

# Tools Used
- Google Chrome (Extensions Manager)

# Steps Performed
1. Audited installed extensions via `chrome://extensions/`
2. Evaluated each extension based on:
   - Source legitimacy
   - Permission scope
   - User reviews
   - Actual usage
3. Removed suspicious extensions:
   - McAfee WebAdvisor (third-party bundled)
   - Instant Data Scraper (high-risk permissions)
   - SEOquake (unused with broad access)
   - SEO META in 1 CLICK (unused with broad access)
4. Kept only verified safe extension:
   - Google Docs Offline (official Google product)

 # Key Findings
- 4/5 extensions were unnecessary or posed potential risks
- Post-removal browser performance improved noticeably
- Many legitimate-looking extensions request excessive permissions

Security Insights
Malicious extensions can:
- Steal sensitive data (logins, payment info)
- Track browsing activity
- Inject ads/malware
- Bypass privacy modes

# Best Practices
✔ Regularly review extensions  
✔ Remove unused add-ons  
✔ Verify permissions before installation  
✔ Prefer official extension stores  
