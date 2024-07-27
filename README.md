# Streamlined DevSecOps Pipeline for Juice Shop

This project sets up a comprehensive DevSecOps pipeline using GitHub Actions to ensure the security and integrity of the Juice Shop application. The pipeline integrates various security testing tools to perform Static Application Security Testing (SAST), Software Composition Analysis (SCA), Container Security Scanning, and Dynamic Application Security Testing (DAST). Each stage of the pipeline is automated, from code checkout to deployment, to provide continuous integration and continuous delivery (CI/CD) with robust security checks at each step.

## Key Features

- **Automated Code Checkout**: Clones the Juice Shop repository to ensure the latest code is used in the pipeline.
- **Dependency Management and Build**: Installs necessary Node.js dependencies and builds the application.
- **Static Application Security Testing (SAST)**: Uses KICS to scan the source code for security vulnerabilities.
- **Software Composition Analysis (SCA)**: Employs Snyk to analyze dependencies for known vulnerabilities.
- **Container Security Scanning**: Utilizes Trivy to scan the Juice Shop Docker image for security issues.
- **Dynamic Application Security Testing (DAST)**: Leverages OWASP ZAP to perform runtime vulnerability scanning on the deployed application.
- **Automated Deployment**: Placeholder steps demonstrating the deployment process, ready for integration with actual deployment steps.

By implementing this pipeline, the project ensures that security is an integral part of the development process, providing early detection and remediation of vulnerabilities, thereby enhancing the overall security posture of the Juice Shop application.

## Tools and Frameworks Used

- **GitHub Actions**: For creating and managing CI/CD pipelines.
- **KICS**: For Static Application Security Testing (SAST).
- **Snyk**: For Software Composition Analysis (SCA).
- **Trivy**: For Container Security Scanning.
- **OWASP ZAP**: For Dynamic Application Security Testing (DAST).
- **Docker**: For containerizing and running security tools.
- **Node.js**: For managing Juice Shop dependencies and builds.

