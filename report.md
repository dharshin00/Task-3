# Vulnerability Report – Task 3 (Phone Scan)

## Scan Summary

- Scan Type: Ping-Only Discovery
- Target Scanned: 192.168.1.xx
- Scanner Used: Nessus Essentials
- Total Vulnerabilities Found: 2
- Scan Duration: A few seconds

### Severity Breakdown:
- Critical: 0
- High: 0
- Medium: 0
- Low: 0
- Info: 2

---

## Vulnerabilities Identified

### 1. Ping the Remote Host
- Severity: Info
- Description: This plugin checks if the host responds to a ping request. This is not a vulnerability by itself, but it confirms the device is online and reachable.
- Recommendation: If this device should not be discoverable, consider firewall rules to block ICMP echo replies.

### 2. Nessus Scan Information
- Severity: Info
- Description: This plugin provides metadata about the Nessus scan. It does not indicate a vulnerability.
- Recommendation: No action needed; this is purely informational.

---

##  Conclusion

This scan used a Ping-Only Discovery policy, which is limited in scope:
- It confirmed the host was alive and responding to ICMP
- No actual port or service vulnerabilities were detected

---

 Tools Used: Nessus Essentials  
 Policy Used: Ping-Only Discovery  
 Screenshots saved in `/screenshots_phone/` folder
