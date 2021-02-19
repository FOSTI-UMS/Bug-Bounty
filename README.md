# FOSTI UMS Bug Bounty Rules for internal purpose

### Anda harus mematuhi kebijakan di bawah ini saat melaporkan masalah keamanan. Berikut ini hal-hal yang perlu diperhatikan: 
- Anda memberi kami waktu untuk menyelidiki dan memperbaiki masalah yang Anda laporkan sebelum Anda mempublikasi ke publik atau membagikan informasi tersebut kepada orang lain.
- Selama melakukan percobaan bughunting, Anda tidak diperkenankan: 
    - omenggunakan akun orang lain tanpa izin dari pemilik Akun. Gunakan akun buatan Anda sendiri.
    - omenghapus data yang dapat menggangu operasional layanan organisasi.
    - mengeksploitasi masalah keamanan yang dapat menyebabkan terganggunya operasional.
- Anda akan mendapatkan sertifikat dan hall of fame atas temuan kerentanan tersebut.
- Mohon untuk menunggu, proses pemberian sertifikat dapat berlangsung 7 hingga 60 hari kerja setelah ditetapkan level risiko.

**In Scope Vulnerabilities
- Account takeover
- Authentication bypass
- Cross-site request forgery
- Cross-site scripting (XSS)
- Directory Traversal Issues
- Exposed Administrative Panels that don't require login credentials
- IDOR/Broken Access Control, sensitive actions by user
- Information disclosure / Sensitive data exposure
- Local File Disclosure (LFD)
- Privilege escalation
- Remote/Arbitrary code execution
- Server Side Template Injection (SSTI)
- Server-Side Request Forgery (SSRF)
- SQL Injection
- Timing or enumeration attacks that have a tangible risk to security or privacy
- XML External Entity Attacks (XXE)

**Out of Scope Vulnerabilities
- Banner grabbing issues (figuring out what web server we use, etc.).
- Being able to upload files with wrong extension in chooser.
- Clickjacking
- CSV injection.
- Denial of Service Attacks.
- Host header injections unless you can show how they can lead to stealing user data.
- Missing autocomplete attributes.
- Missing best practices (we require evidence of a security vulnerability).
- Missing cookie flags on non-security-sensitive cookies.
- Missing security headers which do not lead directly to a vulnerability.
- Open ports without an accompanying proof-of-concept demonstrating vulnerability.
- Open Redirect
- Password, email and account policies, such as email id verification, reset link expiration, password complexity.
- Reflected File Download (RFD).
- Reports of insecure SSL/TLS ciphers (unless you have a working proof of concept, and not just a report from a scanner).
- Reports of spam (i.e., any report involving ability to send emails & SMS without rate limits).
- Reports that state that software is out of date/vulnerable without a proof of concept.
- Self-XSS (we require evidence on how the XSS can be used to attack another user).
- Stack traces that disclose information.
- XSS issues that affect only outdated browsers.

>Domain
- *.fostiums.org
- fosti.ums.ac.id
