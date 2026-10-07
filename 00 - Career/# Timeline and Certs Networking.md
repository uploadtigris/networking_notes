_Updated 2026-10-06 to the networking roadmap. Full day-by-day plan lives in
`becoming_networkAnalyst/plan & tracking/` (career-roadmap-v1, job-plan-oct6-22-v1,
application-tracker-v1)._
## Goal

An entry-level, hands-on **networking** job: **network technician, NOC technician,
network support, or junior network admin/analyst**. Austin, TX or remote. **Not** data
center roles. One title everywhere: **Network Technician**.

## Current status

- IT Support Associate II at Amazon (since Aug 2025), 5,000+ users — troubleshoot VPN
  routing, DNS, and domain-join problems daily.
- **Security+** ✓ · **UT Austin Elements of Computing** ✓ · **AWS Certified AI Practitioner** ✓
- Studied **Network+** heavily; **CCNA** lightly.
- Building the homelab flagship: five-VLAN segmentation on pfSense (in progress, Oct 2026).

## Certification path

1. **CompTIA Security+** — ✅ done (security baseline; gets past HR filters).
2. **CompTIA Network+ (N10-009)** — exam **Oct 2026**. The fastest credential to add; turns
   the resume from "IT support who likes networking" into "networking candidate."
3. **Cisco CCNA (200-301 v1.1)** — start the day after the Net+ exam; target exam
   **~mid-January 2027**. The cert hiring managers for real network roles ask for most.

**Dropped (no longer on the path):** RHCSA, AWS Solutions Architect, AWS SysOps, AWS
Security Specialty, Terraform Associate, CKA/Kubernetes. These served the old DevOps/SRE
plan, not networking.

### Exam facts (checked Oct 6, 2026)

| | CompTIA Network+ | Cisco CCNA |
|---|---|---|
| Exam | N10-009 | 200-301 v1.1 |
| Retires | ~2027 (no date announced) | **v1.1 last day Feb 2, 2027** (v2.0 starts Feb 3) |
| Format | ≤90 questions, 90 min, pass 720/900, includes PBQs | 120 min, multiple choice + sims |
| Price (US) | ~$399 retail | ~$300–330 |

Before paying, check whether **Amazon Career Choice** covers the voucher.

## Job progression

### Phase 1 — Land an entry networking role (now)
- Apply **in parallel** with Net+ study, don't wait for the cert. Entry postings list certs
  as *preferred*; the homelab + Amazon support experience is the real evidence.
- Resume v2 first (Network Technician headline, networking-led skills, Amazon VPN bullet),
  then **50 tailored applications Oct 9–21** (weekdays), plus outreach to Austin networking people.
- Target roles: network technician, NOC technician, network support, junior network admin/analyst.

### Phase 2 — Build experience (first role, 1–2 years)
- Get hands-on with switching, routing, firewall policy, VLANs, DNS/DHCP, wireless, and
  monitoring on the job. Finish **CCNA** while working (1 h/workday + weekends).
- Keep documenting every fix (STAR write-ups in `sysadmin_handbook`).

### Phase 3 — Network admin / analyst / engineer I (years 2–4)
- Move from NOC/support into **junior network administrator / network engineer I**.
- CCNA is the line that opens these, especially at Cisco shops (enterprise, ISPs,
  universities, government).

### Phase 4 — Specialize (years 3–5+)
- Network engineer, then a chosen depth: enterprise/campus networking, wireless, security
  (NGFW/segmentation on the Security+ base), or network automation (Python + REST/APIs).

## Homelab evidence (what interviews ask about)
- **Segmented home network (VLANs + pfSense)** — flagship: Mgmt 1 / Trusted 20 / IoT 30 /
  Guest 40 / Servers 50 on 10.0.VLAN.0/24, default-deny inter-VLAN rules, tested with nmap.
- **Pi-hole network DNS** — DNS filtering + a real DHCP/static-IP troubleshooting story.
- **Wazuh SIEM** — rebuilding (security add-on, not the headline).

## Action items
- [x] Pass Security+
- [ ] Pass **Network+** (exam Oct 2026); update resume/LinkedIn/site/profile to "Network+ (Passed)"
- [ ] Finish the VLAN build + test matrix + write-up (flipping the lab to "Completed")
- [ ] Resume v2 + 50 applications (Oct 9–21) + LinkedIn + outreach
- [ ] Start **CCNA** the day after Net+; exam ~mid-Jan 2027 (before v1.1 retires Feb 2, 2027)
- [ ] Keep the GitHub portfolio honest — evidence before any "done" claim

## Key principles
- **One title: Network Technician.** No Cloud Engineer / DevOps / SRE framing.
- **Projects > certs** when job hunting — show you can do the work.
- **Never claim before evidence.** "In progress" until screenshots/configs/tests exist.
- **Not on any application or notes:** Ansible (never used), Proxmox (gone), OPNsense
  (it's pfSense), AWS SA, Wireshark (until real captures), Wazuh/Suricata as "running."
