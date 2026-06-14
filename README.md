# DMZ-Project

**DMZ Network Security Lab - 4Geeks Cybersecurity Program**

Hands-on lab configuring a Demilitarized Zone using Cisco Packet Tracer.

---

## What This Lab Does

- Configure 3 separate network zones (Internal, DMZ, External)
- Set up NAT to expose web server securely
- Create ACLs (firewall rules) to block unauthorized traffic
- Test security and prevent lateral movement

## Network Zones

| Zone | IP Range | Gateway | Device |
|------|----------|---------|--------|
| Internal LAN | 192.168.1.0/24 | 192.168.1.1 | PC_Internal |
| DMZ | 192.168.2.0/24 | 192.168.2.1 | Web Server |
| External/Internet | 192.168.3.0/24 | 192.168.3.1 | PC_External |

## How to Use

1. Download `DMZ_PROJECT.pka`
2. Open in Cisco Packet Tracer
3. Read `DMZ_Lab_Report_4Geeks_Template.md` for instructions
4. See `evidencias/` folder for test screenshots

## Key Results

✅ All devices can reach their gateways
✅ External users can access web server via NAT
✅ DMZ and Internal LAN are completely isolated (blocked)

## Configuration Summary

**NAT (Network Address Translation):**
- Internal server: 192.168.2.10
- External IP: 192.168.3.1

**Security Rules (ACLs):**
- Allow: HTTP (port 80) from Internet to DMZ only
- Block: All traffic between DMZ and Internal LAN

## Files in This Repo

- `DMZ_Lab_Report_4Geeks_Template.md` - Full lab report with analysis
- `DMZ_PROJECT.pka` - Cisco Packet Tracer file
- `README.md` - This file
- `evidencias/` - Screenshots of all tests

## Student

Terry (Tw30625)
4Geeks Miami Cybersecurity Program
June 2026

---

**Status:** ✅ Complete | All Tests Passing
