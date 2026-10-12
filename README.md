Recotest

Recotest is an AI-powered reconnaissance and attack surface analysis assistant integrated with Burp Suite, designed to help penetration testers discover, organize, and analyze a target's exposed assets and potential attack points. It collects and correlates information such as subdomains, JavaScript files, endpoints, parameters, and technologies, using AI to identify interesting endpoints and suggest potential vulnerabilities across a wide range of web application vulnerability classes.

Instead of acting as a fully automated vulnerability scanner, Recotest helps security testers prioritize areas worth investigating and prepare selected endpoints for manual testing through Burp Suite Repeater.

Features

- Attack Surface Mapping: Organizes discovered assets under a target-based structure.
- Subdomain Discovery: Collects and categorizes discovered subdomains.
- JavaScript Analysis: Analyzes JavaScript files to extract endpoints, parameters, and potentially hidden routes.
- Endpoint Discovery: Identifies and organizes endpoints discovered during reconnaissance.
- Technology Detection: Collects information about the technologies used by the target.
- AI-Powered Endpoint Analysis: Analyzes discovered endpoints and their context to suggest potential vulnerability classes.
- Potential Vulnerability Identification: Highlights suspicious endpoints for further investigation without treating AI predictions as confirmed vulnerabilities.
- Burp Suite Integration: Helps prepare selected endpoints for manual testing in Burp Repeater.
- Target-Based Dashboard: Displays the target and its related subdomains, JavaScript files, endpoints, technologies, and potential vulnerabilities in a structured tree.
- Endpoint Prioritization: Helps testers focus on the most interesting attack points first.

Tech Stack

- Security Testing Platform: Burp Suite
- AI Layer: AI-powered endpoint analysis and vulnerability candidate classification
- Reconnaissance Modules: Subdomain discovery, JavaScript analysis, and endpoint extraction
- Dashboard: Web-based target and attack surface visualization
- Backend & API: To be determined during implementation
- Database: To be determined based on the final architecture

How It Works

1. Target Configuration: The penetration tester defines the target and authorized testing scope.
2. Reconnaissance: Recotest collects information about discovered subdomains, JavaScript files, endpoints, parameters, and technologies.
3. Data Extraction: The tool analyzes JavaScript files and other available sources to identify additional endpoints and parameters.
4. Attack Surface Mapping: Discovered information is organized and linked to its corresponding target.
5. AI-Powered Analysis: The AI analyzes endpoint characteristics and available context to identify interesting attack points and suggest potential vulnerability classes.
6. Dashboard Visualization: All discovered assets and potential vulnerabilities are displayed in a structured, target-centered interface.
7. Manual Testing: Selected endpoints can be prepared for further investigation through Burp Suite Repeater, where the penetration tester performs and validates the tests.

Screenshots

Screenshots of the Recotest dashboard and its attack surface mapping interface will be added here.

Setup

Installation instructions, configuration, and Burp Suite integration steps will be added as the project implementation progresses.

Security & Scope

Recotest is intended for authorized penetration testing and security research. AI-generated vulnerability suggestions are candidates for investigation, not proof of exploitable vulnerabilities. Final validation remains the responsibility of the penetration tester.

License

MIT
