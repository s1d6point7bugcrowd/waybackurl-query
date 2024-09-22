# URL Based Archive Search

A tool for querying and retrieving archived pages from the `*.secret.app` domain using the Internet Archive’s CDX API.


This project allows users to search for and extract archived pages from the `*.secret.app` domain using the Internet Archive's CDX API. It is useful for researchers, security analysts, and anyone interested in the historical data of the Secret App website.

## Features

- Query archived pages using a wildcard URL pattern.
- Retrieve original URLs of archived pages.
- Output results in a plain text format.
- Group results by URL key for streamlined analysis.

## Use Cases

### Value in Bug Bounties

1. **Identifying Vulnerabilities**:
   - Access older versions of the site to discover vulnerabilities that may have been patched in the current version. This can help you understand how security controls have evolved.

2. **Contextual Analysis**:
   - Gather historical context on specific features or endpoints that may have introduced vulnerabilities. Understanding past functionality can help you better assess current security posture.

3. **Exploit Development**:
   - Use archived data to identify potential weaknesses in legacy code or outdated practices that may still exist in current applications, allowing for effective exploit development.

4. **Proof of Concept (PoC)**:
   - Enhance your bug bounty reports by including evidence from archived pages. This can demonstrate how vulnerabilities impact users or data integrity over time.

5. **Security Best Practices**:
   - Compare the evolution of security measures across different versions of the site. This can provide insights into best practices and areas for improvement.


