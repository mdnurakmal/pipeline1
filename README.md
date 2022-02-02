
# DevSecOps pipeline for ReactJS based project 

IDE - Visual Studio Code
IDE Scanner - Snyk Vulnerability Scanner
CICD - Circle.CI
Pre-commit hook - talisman
Orchestration - N/A
SCM - Github
Artifact repository - N/A
Compliance Scanning - N/A
Secret check - trufflehog
SCA - safety
SAST - bandit
CVA / CSA - N/A
Container Audit - N/A
DAST - nikto for scans, selenium-chrome for grabbing session cookie
Security Audit - lynis
WAF - N/A
Environment - Netlify


Collaboration : Slack
Logging : 

SCM : Source Code Mangement
SCA : Software Composition Analysis
SAST : Static Analysis Security Testing
DAST  : Dynamic Analysis and Security Testin


IDE Scanner -> Github -> Pre-commit hook -> Unit Test -> Code Coverage -> Static analysis -> Static Analysis Security Testing / Vulnerability Scan ->  -> Build - >  -> Slack -> - > Deploy >Monitor

logstash , grafana

Vulnerability Assessment (prod server) -> Dynamic code analysis -> Infrastructure scanning -> Infra compliance check

React specific
Jest and enzyme

## Slow NPM install
npm config set registry https://registry.npmjs.org/ --global

## Managed vs Self-Hosted CI/CD Services
- Managed
* Requires to include API keys from various providers (CircleCI, Netlify, CodeCov)
* Higher cost 

Pre-commit Hooks
Software Composition Analysis
Dynamic Analysis Security Testing
Artifact storage

SonarLint real-time analaysis

Talisman - https://github.com/thoughtworks/talisman

2 repo

1 Application , 1 Infra