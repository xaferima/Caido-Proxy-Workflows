# Caido-Proxy-Workflows
Caido Proxy Workflows is a repository dedicated to the creation, management, and optimization of workflows for Caido Proxy, an advanced tool for web application analysis and security testing. 

**Tool: https://caido.io/**

**Caido is a lightweight web security auditing toolkit that aims to help security professionals and enthusiasts audit web applications with efficiency and ease.** This repository contains scripts, configurations, and documentation to automate and enhance the use of Caido Proxy, facilitating the detection of vulnerabilities and strengthening web application security.

**How to use workflows:**
https://docs.caido.io/reference/workflows/workflows.html

## Workflows:
  - **SearchDataInBody.json:**
    This workflow is designed to search for a specific data term: in the request and response bodies intercepted by the Caido platform. It generates findings based on the presence and values of this term.

  - **UnmaskedSensitiveDataSearch.json:**
    This workflow searches for specific terms in HTTP request and response bodies, identifying and reporting values that are not properly masked. It generates findings in Caido for any uncovered sensitive data.


