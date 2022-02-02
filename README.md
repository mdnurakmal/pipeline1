# DevSecOps pipeline for ReactJS based project (Managed Services focused )



[![codecov](https://codecov.io/gh/mdnurakmal/react-cicd-1/branch/main/graph/badge.svg?token=U03ASER0MO)](https://codecov.io/gh/mdnurakmal/pipeline1)
[![CircleCI](https://circleci.com/gh/mdnurakmal/pipeline1/tree/main.svg?style=svg)](https://circleci.com/gh/mdnurakmal/pipeline1/tree/main)
[![Known Vulnerabilities](https://snyk.io/test/github/mdnurakmal/pipeline1/badge.svg)](https://snyk.io/test/github/mdnurakmal/pipeline1)
[![BCH compliance]](https://bettercodehub.com/edge/badge/mdnurakmal/pipeline1?branch=main)

* IDE - Visual Studio Code
* IDE Scanner - Snyk Vulnerability Scanner
* CICD - Circle.CI
* Pre-commit hook - N/A
* Orchestration - N/A
* SCM - Github
* Artifact repository - N/A
* Compliance Scanning - N/A
* Secret check - GitGuardian
* SCA - safety
* SAST - bandit
* CVA / CSA - N/A
* Container Audit - N/A
* DAST - nikto for scans, selenium-chrome for grabbing session cookie
* Security Audit - lynis
* Threat Detection - N/A
* SIEM & SOAR - N/A
* WAF - N/A
* Environment - Netlify
* Code Coverage  - CodeCov
* Dependency Management - N/A
* Security Scanning - snyk

* Collaboration : Slack
* Logging : logstash
* Visualization : grafana , kibana
* Monitor:
* Plan: Jira

# Acronym
SCM : Source Code Mangement
SCA : Software Composition Analysis
SAST : Static Analysis Security Testing
DAST  : Dynamic Analysis and Security Testin
CSA : Container Security Analysis
CVA : Container Vulnerability Analysis

IDE Scanner -> Github -> Pre-commit hook -> Unit Test -> Code Coverage -> Static analysis -> Static Analysis Security Testing / Vulnerability Scan ->  -> Build - >  -> Slack -> - > Deploy >Monitor


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

2 repo

1 Application , 1 Infra