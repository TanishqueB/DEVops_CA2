# Docker & Container Security — FestPass

## Student Details
- **Name:** Tanishque Baranwal
- **Registration No.:** 318
- **Port:** 98
- **Docker Hub:** [tan1shque/fest-backend](https://hub.docker.com/r/tan1shque/fest-backend)

## Project Overview
FestPass is a three-tier web application using Docker Compose:
- **Frontend:** Nginx
- **Backend:** Python Flask
- **Database:** PostgreSQL

## Features
- Docker containerisation and Compose orchestration
- Network isolation and persistent database storage
- Trivy vulnerability scanning
- Docker image tagging and versioning
- Cosign image signing and verification

## Vulnerability Report

| Metric | Before | After |
|---|---|---|
| CRITICAL vulnerabilities | See `trivy-before.txt` | Not completed |
| HIGH vulnerabilities | See `trivy-before.txt` | Not completed |
| Image size | Not recorded | Not recorded |

## Progress
- **Stage 1:** Backend containerised and health endpoint tested.
- **Stage 2:** Three-tier application configured using Docker Compose.
- **Stage 3:** Partially completed; initial Trivy report generated, remediation and final scan incomplete.
- **Stage 4:** Image tags created; Docker Hub push encountered network connectivity errors.
- **Stage 5:** Cosign signing and verification not completed.

## AI Disclosure
ChatGPT was used for configuration guidance, troubleshooting, and documentation.

## Incomplete Tasks
- Complete Stage 3 remediation and generate the after-scan report.
- Complete Stage 5 Cosign signing and verification.