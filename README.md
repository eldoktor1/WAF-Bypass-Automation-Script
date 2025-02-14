🔥 WAF Bypass Automation Script 🚀

This script automates various bypass techniques for Web Application Firewalls (WAFs) using curl requests. It cycles through a list of user agents, headers, and URL modifications to find potential bypass methods. The script also includes random delays to help avoid detection.
Features ✨

Randomized user-agents for each request 🕵️‍♀️
Multiple bypass techniques, including URL encoding, SQL-like injections, and header manipulations 🛠️
HTTP request headers to bypass common WAF defenses 📡
Proxy support through proxychains 🌍
Custom delay between requests to evade rate-limiting defenses ⏱️

Installation ⚙️

To install, clone the repository using the following command:

    git clone https://github.com/eldoktor1/WAF-Bypass-Automation-Script.git

Usage 💻

Make sure proxychains and curl are installed.
Navigate to the directory and give execution permissions to the script:

    cd WAF-Bypass-Automation-Script
    chmod +x d0k_waf_bypass.sh

Run the script:

    ./d0k_waf_bypass.sh

Input the target URL when prompted and let the script run.




Important ⚠️

This tool is for educational and authorized penetration testing purposes only. Misuse of this tool could result in legal consequences. Always ensure you have permission before running this tool on any web application.
