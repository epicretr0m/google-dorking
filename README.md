# Google Dork

## English 
- **Filetype-specific search**:
  - Using `filetype:` operator: `filetype:pdf` to search for PDF files.
  - Using `ext:` operator: `ext:doc` to search for doc files.

- **Title search**:
  - Using `intitle:` operator: `intitle:"index of"` to find pages with "index of" in their title.

- **URL search**:
  - Using `inurl:` operator: `inurl:admin` to find pages with "admin" in their URL.

- **Similar sites search**:
  - Using `related:` operator: `related:example.com` to find sites similar to "example.com".

- **Term exclusion**:
  - Using `-` operator: `site:example.com -term` to exclude pages containing the specified term.

- **Specific link search**:
  - Using `link:` operator: `link:example.com` to find pages that contain a link to "example.com".

- **File metadata search**:
  - Using `intext:"metadata"` operator: `intext:"metadata" site:example.com` to find pages containing specific metadata.

- **Directory search**:
  - Using `intitle:"index of"` operator: `intitle:"index of" site:example.com` to find directories and file lists on a specific site.

- **Vulnerable server search**:
  - Using `intitle:"Apache HTTP Server Test Page"` operator: `intitle:"Apache HTTP Server Test Page"` to find potentially vulnerable Apache servers.

- **Confidential documents search**:
  - Using `intext:"confidential" OR intext:"secret"` operator: `intext:"confidential" OR intext:"secret" site:example.com` to find potentially confidential documents on a specific site.

- **Exposed passwords search**:
  - Using `intext:"password" filetype:txt` operator: `intext:"password" filetype:txt` to find text files containing passwords.

- **Sensitive parameter search**:
  - Using `inurl:"?id="` operator: `inurl:"?id=" site:example.com` to find pages with sensitive URL parameters.

- **PDF document search with specific keywords**:
  - Using `intext:"keyword"` with `filetype:pdf` operator: `intext:"confidential" filetype:pdf site:example.com` to find PDF documents containing the keyword "confidential" on a specific site.

- **Backup directory search**:
  - Using `intitle:"index of" AND intitle:"backup"` operator: `intitle:"index of" AND intitle:"backup" site:example.com` to find backup directories on a specific site.

- **SQL injection vulnerable page search**:
  - Using `inurl:"page.php?id="` operator: `inurl:"page.php?id=" site:example.com` to find potentially SQL injection vulnerable pages on a specific site.

- **Email address search**:
  - `site:example.com intext:@example.com` : Search for email addresses on example.com.

- **Phone number search**:
  - `intext:"phone number" site:example.com` : Search for pages containing the text "phone number" on example.com.

- **IP address search**:
  - `intext:"IP address" site:example.com` : Search for pages containing the text "IP address" on example.com.

- **Phone numbers in contact pages search**:
  - `intext:"contact us" intext:"phone" site:example.com` : Search for contact pages containing the word "phone" on example.com.

- **IP addresses in server logs search**:
  - `filetype:log intext:"IP address" site:example.com` : Search for log files containing the text "IP address" on example.com.
