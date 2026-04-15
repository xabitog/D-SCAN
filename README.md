# D-SCAN: Supply Chain Security Scanner

D-SCAN is a high-performance, automated security tool designed for developers and security researchers to identify vulnerable or malicious dependencies within GitHub repositories. 

It specializes in detecting "Dependency Confusion" risks and missing npm packages by auditing repository manifests against public registry availability.

## Key Features

* **Supply Chain Auditing:** Scans organization-wide GitHub repositories for `package.json` files.
* **Vulnerability Detection:** Identifies missing npm packages that could be exploited via dependency confusion attacks.
* **Automated Intelligence:** Integrates with real-time threat analysis to assess the safety of third-party code.
* **Fast & Scalable:** Optimized for large-scale enterprise GitHub organizations.
* **Minimalist Terminal UI:** Designed for efficiency, providing clear, actionable security insights.

## How It Works

1.  **Repository Sync:** The tool fetches all `package.json` files from your specified GitHub organization.
2.  **Dependency Extraction:** It parses both `dependencies` and `devDependencies` from the manifests.
3.  **Registry Verification:** D-SCAN queries the public npm registry to verify the existence of the listed packages.
4.  **Risk Identification:** If a package is listed in your project but is missing from the public registry (404), it is flagged as a potential high-risk vector for malicious code injection.

## Getting Started
## URL TO ACCESS TOOL : https://d-scan-xabit.netlify.app/
1.  **Configure:** Input your Target GitHub Organization and a valid GitHub Personal Access Token (PAT).
2.  USE github token
3.  **Audit:** Run the scan to perform a deep analysis of your dependency tree.
4.  **Analyze:** View the output in the terminal to identify risky dependencies and mitigate supply chain threats before deployment.

## Disclaimer

D-SCAN is intended for ethical security research and authorized auditing only. Users are responsible for ensuring they have permission to scan the target organizations.

## Developed by @zabitmajeed
