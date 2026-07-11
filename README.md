# <img src="icons/robot.svg" width="32" height="32"> AI_Instructions <img src="icons/robot.svg" width="32" height="32">
**A standardized instruction set and workflow protocol for managing AI-driven code edits.**

---

## Overview
AI_Instructions is a specialized utility designed to enforce strict behavioral protocols during AI-assisted programming sessions. It establishes a unified framework for version control, code modification, and communication, ensuring that AI agents maintain surgical precision without unauthorized refactoring or data loss.

**Primary Environment:** Developed for compatibility with LLM-based coding assistants. It is designed for users who require rigorous control over output formatting and automated editing workflows.

### The Core Engine
The utility utilizes a defensive header architecture that acts as a "hard" constraint on the AI's generation logic. 

Key operational features include:
1. **Message Stamp Protocol:** Enforces a mandatory, time-synchronized version stamp on every code-containing response to ensure traceability.
2. **Surgical Fix Pipeline:** Restricts the AI to minimal, targeted code edits, preventing the accidental rewriting of large blocks or unintended refactoring.
3. **Verbatim Anchor Protocol:** Mandates a specific "Before/After/Replace" anchoring structure, enabling seamless "Find and Replace" operations in text editors like Notepad++.
4. **Content Preservation:** Protects existing telemetry and debug data from being stripped during the editing process.

### Logic & Precision
AI_Instructions operates with a "governance-first" philosophy. The protected code block is immutable, ensuring that the AI agent cannot alter its own operating parameters or modify its versioning logic, maintaining a predictable and consistent coding interface.

---

## Feature Reference

| Option | Description |
| :--- | :--- |
| **Message Stamp** | A timestamped signature (YYYY.MM.DD__HH.MM.SS) required for every code response. |
| **Snippet Prohibition** | Prevents the AI from suggesting automated updates to the script versioning itself. |
| **Surgical Edits** | Limits code modification to high-precision, surgical changes. |
| **Anchor Protocol** | Requires specific context anchors (Before/After/Replace) for all code injections. |

---

## Assets & Licensing
This software is released under the **MIT License**.

### Icon/Asset Credits
* **File:** `robot.svg`
    * **Asset:** Robot SVG Vector
    * **Author:** Twitter
    * **Source:** <a href="https://www.svgrepo.com/svg/407351/robot" target="_blank">https://www.svgrepo.com/svg/407351/robot</a>
    * **License:** MIT License
    * **Modifications:** Removed metadata.

---

## Dependencies
* **OS:** Cross-platform (text-based implementation).
* **Language/Framework:** Compatible with any LLM supporting system instruction overrides.
* **Requirements:** N/A.

## Support & Maintenance
**This repository is provided "as-is" for archival purposes.** The author is not actively looking for feedback, feature requests, or bug reports. The issue tracker is disabled.

## Disclaimer
*AI_Instructions is a tool for behavioral management of AI coding agents. The author is not responsible for any legal implications arising from the use of AI-generated code or the software's execution.*

---
> **Document Control**<br>
> *This document is up-to-date with the following version of AI_Instructions.*<br>
> *2026.07.11__10.10.56*