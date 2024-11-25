# Security Policy  

At the 10Alytics Data Science Collaboration Platform, we prioritize the security of our contributors and users. This document outlines how to report vulnerabilities and the measures we take to ensure a secure platform.  

---

## **Supported Versions**  
We actively maintain the latest version of this repository. Security updates and patches will only be provided for the main branch.  

---

## **Reporting a Vulnerability**  

If you discover a security vulnerability, please report it responsibly.  

### **Steps to Report:**  
1. **Email:** Send a detailed report to [datascience@10alytics.io](datascience@10alytics.io).  
2. **GitHub Security Advisories:** Use the [GitHub security advisory feature](https://docs.github.com/en/code-security/security-advisories) to report privately.  

Your report should include:  
- A clear description of the vulnerability.  
- Steps to reproduce the issue (if applicable).  
- Any relevant screenshots or logs.  

We will acknowledge your report within **48 hours** and work with you to address the issue promptly.  

---

## **Security Best Practices for Contributors**  

### **Handling Data**  
- Avoid uploading sensitive or proprietary data.  
- Anonymize datasets before sharing them in `/projects` or `/tutorials`.  

### **Code Contributions**  
- Validate input data in code snippets to prevent vulnerabilities.  
- Do not commit sensitive credentials (e.g., API keys, passwords).  

### **Dependency Management**  
- Use up-to-date dependencies when contributing to scripts or projects.  
- Run security checks using tools like `pip-audit` for Python before submission.  

---

## **Automated Security Measures**  
We use the following tools to enhance repository security:  
- **GitHub Dependabot:** Automatically identifies and resolves vulnerabilities in dependencies.  
- **Branch Protection Rules:** Ensures only reviewed and approved code is merged.  
- **Code Scanning:** Detects potential security flaws in pull requests.  

---

## **Acknowledgment**  
We value your effort in helping us maintain a secure platform. Contributors who responsibly disclose vulnerabilities may be credited in the repository (if desired). 
