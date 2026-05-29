# CYBER SECURITY INTERNSHIP – TASK 1

## Scan Your Local Network for Open Ports

### Objective

Learn to discover open ports on devices in the local network to understand network exposure.

---

# Tools Used

* Nmap
* Wireshark (Optional)

---

# Command Used

```bash
nmap -sS 192.168.1.0/24
```

---

# Scan Results

| IP Address   | Open Port | Service |
| ------------ | --------- | ------- |
| 192.168.1.1  | 80        | HTTP    |
| 192.168.1.1  | 443       | HTTPS   |
| 192.168.1.5  | 22        | SSH     |
| 192.168.1.10 | 135       | MSRPC   |
| 192.168.1.10 | 445       | SMB     |

---

# Security Risks

* Open ports may allow unauthorized access.
* Weak SSH passwords can be attacked.
* SMB vulnerabilities may expose file sharing systems.

---

# Security Recommendations

* Close unused ports.
* Enable firewall protection.
* Keep systems updated.
* Use strong passwords.

---

# Outcome

Learned basic network reconnaissance and port scanning using Nmap.

---

# Interview Questions

## What is an open port?

An open port is a communication endpoint accepting network connections.

## What is TCP SYN scan?

A scanning method where SYN packets are sent to identify open ports.

## Difference between TCP and UDP scanning?

TCP is connection-oriented while UDP is connectionless.

## Role of firewall?

Firewall blocks unauthorized network access.

---

# Conclusion

This task helped in understanding open ports, network exposure, and cybersecurity basics using Nmap.
