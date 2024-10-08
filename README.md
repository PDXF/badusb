
Stand Up to Hate Against Furries and Other Minorities: Silence is Complicity!
ZRK Flipper Zero BadUSB Payload Library
ZRK Flipper Zero BadUSB Payload Library
This repository aims to consolidate all Flipper Zero-friendly BadUSB payloads into a single, organized library—similar to the IRDB. With this, the community can easily stay updated by pulling from the master repository.

If you're searching for resources or tools to craft your own payloads, check out the BadUSB-Playground repo.

Contributing Guidelines
Follow These Practices When Submitting a Payload
Naming Conventions
Your payload should have a unique, clear, and descriptive name. Avoid spaces in file or directory names; use - or _ instead. Submit each payload into its own directory within one of the established categories like exfiltration, phishing, remote_access, or recon. Please refrain from creating new categories.

Staged Payloads
"Staged payloads" are payloads that download code from an external source outside of the payload.txt file.

While staged payloads can be useful, this repository is not a CDN for deploying stages. It is intended for sharing code between developers, not for serving code to target systems. The end user is responsible for hosting staged code on their own infrastructure.

Refer to GitHub's acceptable use policies for further details.

Any staged code must be either included in the payload’s comments or submitted as a separate file. Links to staged code are not allowed for security and version control reasons. Links can be easily altered, potentially turning safe code into something harmful without the user's knowledge.

Payload Documentation
Each payload must start with REM comments specifying the following details: title, author, target system, description, and version.

Example:

vbnet
Copy code
REM Title: Canary Duck
REM Author: Jessie Crimson Hart
REM Description: Opens hidden PowerShell and connects to a canary server, notifying you of unauthorized access.
REM Target: Windows 10 (PowerShell)
REM Props: Hak5, Thinkst
REM Version: 1.0
REM Category: General
Payloads are for educational purposes only. ZRK devices are intended for security analysis and auditing where legally permitted. Users are responsible for adhering to all applicable laws. FalsePhilosopher and the ZRK community assume no responsibility for unauthorized or unlawful use.

Disclaimer
Proceed with caution when using any script.

Payloads can execute commands on your device, and as such, may potentially cause damage. Payloads in this repository are provided as-is without guarantees or support. While I do my best to review submissions, there are no assurances of their safety or effectiveness.
