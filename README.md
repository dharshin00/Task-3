# Cybersecurity Internship – Task 3

## Objective
Perform a basic network discovery scan on a mobile device to identify its presence on the network and observe if any vulnerabilities can be detected.

---

##  Tools Used

- **Scanner:** Nessus Essentials (Free Version)
- **Scan Policy:** Ping-Only Discovery
- **Target:** My phone's IP address (192.168.1.xx)
- **Scan Duration:** A few seconds

---

## What I Did

1. Opened Nessus Essentials and selected the **Ping-Only Discovery** scan template.
2. Entered my phone’s IP address as the scan target.
3. Launched the scan and waited for it to complete.
4. The scan confirmed that the phone was reachable but did not return any critical vulnerabilities.
5. Saved the scan summary and screenshots.
6. Documented the results in `report.md`.

---

## What I Learned

- Ping-only scans are limited to basic device discovery (ICMP response).
- Many mobile devices block deeper scans, so this approach is useful for mapping presence but not detailed vulnerabilities.
- Learned how to differentiate between information-level results and actual threats.

---

## Files in This Repo

| File/Folder            | Description                                    |
|------------------------|------------------------------------------------|
| `screenshots/`   | Folder containing screenshots of the scan      |
| `report.md`            | Full report of scan results                    |
| `README.md`            | Overview of the task and what I did            |

---
 **Note:** This was a limited scan performed on a mobile device for educational purposes. No active vulnerabilities were discovered.
