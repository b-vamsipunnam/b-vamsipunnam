# Hi, I'm Vamsi

**Enterprise Automation Engineer | [Robot Framework Ambassador](https://robotframework.org/ambassador/)**

I'm Bhimeswara Vamsi Punnam. I build open-source tools for Salesforce file extraction, object discovery, and test automation. I focus on making long-running workflows easier to validate, troubleshoot, and recover when something goes wrong.

## Projects I maintain

### [Salesforce Files Bulk Downloader](https://github.com/b-vamsipunnam/salesforce-files-downloader-tool)

Helps Salesforce developers and migration teams extract files to local storage. It combines API metadata with authenticated browser downloads, parallel batch processing, and bounded retries.

A recorded benchmark of **10,000 files, approximately 6.4 GB**, took 240 minutes with one worker and 31 minutes with eight workers, a **7.74× speedup**.

[Getting started](https://github.com/b-vamsipunnam/salesforce-files-downloader-tool/blob/main/docs/Installation.md) · [Benchmark details and limitations](https://github.com/b-vamsipunnam/salesforce-files-downloader-tool/blob/main/docs/Performance.md)

### [Salesforce Objects Scanner](https://github.com/b-vamsipunnam/salesforce-objects-scanner-tool)

Helps Salesforce administrators and migration teams inventory accessible objects and count records where supported. Excel and JSON reports distinguish successful counts, skipped objects, and failed queries to support cleanup and migration planning.

[Getting started](https://github.com/b-vamsipunnam/salesforce-objects-scanner-tool/blob/main/docs/installation.md)

## Contributions to SeleniumLibrary

I've contributed four merged pull requests to SeleniumLibrary, adding two keywords, fixing table footer matching, and improving test reliability.

**Keywords released in [SeleniumLibrary 6.9.0](https://github.com/robotframework/SeleniumLibrary/releases/tag/v6.9.0):**

- [**Get CSS Property Value**](https://github.com/robotframework/SeleniumLibrary/pull/1969): retrieves an element's browser-computed CSS property value.
- [**Drag And Drop Across Frames**](https://github.com/robotframework/SeleniumLibrary/pull/1953): supports drag-and-drop operations across frame contexts.

**Bug fixes and test improvements:**

- [**Table footer matching**](https://github.com/robotframework/SeleniumLibrary/pull/2000): updated `Table Footer Should Contain` to recognize both `<th>` and `<td>` footer cells, with regression tests to verify that matching stays within the intended footer.
- [**Cross-frame drag-and-drop tests**](https://github.com/robotframework/SeleniumLibrary/pull/2001): resolved headless Chrome acceptance-test failures by setting an appropriate browser viewport and restoring the original window size after each test.

## Research

**[A Single-Node Parallel Framework for Bulk Binary File Extraction from Salesforce CRM: Design and Performance Evaluation](https://ieeexplore.ieee.org/document/11627370)**  
IEEE Cloud Summit 2026

My paper examines the design, scalability, and performance of parallel Salesforce file extraction on a single machine.

## Core stack

Python · Java · Robot Framework · SeleniumLibrary · Pabot · Salesforce APIs · SOQL · Salesforce CLI

## Community

- IEEE Senior Member.
- Presented **Salesforce Application Automation with CumulusCI and Robot Framework Integration** at the Robot Framework Americas meetup in April 2026.
- Reviewed eight applications as part of the November 2026 IEEE Senior Member application review panel.
- Completed a peer review for IEEE Access in November 2026.

## Connect

[LinkedIn](https://www.linkedin.com/in/bvamsipunnam/) · [ORCID](https://orcid.org/0009-0009-4668-0244)

I'm happy to exchange ideas about Salesforce automation, Robot Framework, and open-source tooling.

---

![Profile views](https://visitor-badge.laobi.icu/badge?page_id=b-vamsipunnam.b-vamsipunnam)
