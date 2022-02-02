# DevSecOps pipeline for ReactJS based project 
NETLIFY_AUTH_TOKEN=asdf65wHAn-BfQhJJRJwCt-asl56px6LV66eug-y2Q
NETLIFY_AUTH_TOKEN=asdf65wHAn-BfQhJJRJwCt-asl56px6LV66eug-y2Q

[![codecov](https://codecov.io/gh/mdnurakmal/react-cicd-1/branch/main/graph/badge.svg?token=U03ASER0MO)](https://codecov.io/gh/mdnurakmal/react-cicd-1)

* IDE - Visual Studio Code
* IDE Scanner - Snyk Vulnerability Scanner
* CICD - Circle.CI
* Pre-commit hook - talisman
* Orchestration - N/A
* SCM - Github
* Artifact repository - N/A
* Compliance Scanning - N/A
* Secret check - trufflehog
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
* Security Scanning - N/A

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