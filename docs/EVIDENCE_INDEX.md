ACICP302ICS MODULE 1 – EVIDENCE INDEX

Assessment:
Integrated ICS Network Security & Attacks: Analyze, Test & Recover

Source:
ACICP302ICS-Network-Security-and-Attacks
Canonical path:
labs/ot-security/student-lab-source/

Verified source commit:
2a66f9bcf253eb3fe31c68ad52794cd535421da8

SAFETY / SCOPE
- Supplied OT simulator only.
- All lab traffic remained on 127.0.0.1.
- No bridged networking was used.
- No external/real ICS device was targeted.
- Archive-original was not executed.
- Four lab services were stopped after testing.
- Final network check showed loopback only; enp0s3 and enp0s8 were DOWN.

EVIDENCE REGISTER

Evidence 01 – Wireshark baseline capture
Evidence 02 – Normal direct dashboard
Evidence 03 – Normal guarded dashboard
Evidence 04A – False-data attack terminal output
Evidence 04B – Direct dashboard impact
Recovery 1 – Direct dashboard returned to normal
Evidence 05A – Slow-drift guarded attack
Evidence 05B – Slow-drift guard rejection
Evidence 06A – Replay attack
Evidence 06B – Replay event-log check
Recovery 3 – Normal plant telemetry after replay
Evidence 07 – Local Modbus service exposure
Evidence 08 – Four local listeners
Evidence 09 – Matching Modbus transaction
Evidence 10 – Register map and ranges
Evidence 11 – Direct dashboard baseline
Evidence 12 – Guarded dashboard baseline
Evidence 13 – Guard source checks and thresholds
Evidence 14 – Guard rejection events

FILES INCLUDED
- FINAL_REPORT/ACICP302ICS_Module_1_Practical_Lab_Final_Report.docx
- evidence/pcap/base_modbus_capture.pcapng
- evidence/screenshots/  [screenshots to be placed here]