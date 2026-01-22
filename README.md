# appwrite-poc-test

# Appwrite POC Test Repository

⚠️ **Security Research Purpose Only**

This repository is used for testing a webhook signature verification vulnerability in Appwrite.

## Purpose

This repository demonstrates a critical vulnerability (CVSS 10.0) in Appwrite's GitHub webhook integration:
- **Vulnerability**: Webhook signature verification bypass
- **Impact**: Arbitrary code execution, API key theft, project compromise
- **Status**: Responsible disclosure in progress

## How it works

The `package.json` file contains an install script that:
1. Sends a request to RequestCatcher when the build process runs
2. Demonstrates that attacker-controlled code can be executed
3. Proves the signature verification was bypassed

## DO NOT USE IN PRODUCTION

This is for security research and responsible disclosure only.

## Responsible Disclosure

This vulnerability is being reported to Appwrite's security team following responsible disclosure guidelines.

## Timeline

- **Discovery**: 2026-01-20
- **POC Created**: 2026-01-22
- **Vendor Notification**: Pending
- **CVE Application**: Pending
