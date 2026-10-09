ACICP302ICS MODULE 1 – PRACTICAL LAB EVIDENCE

Integrated ICS Network Security & Attacks: Analyze, Test & Recover

LEARNER
Wendell Twumasi

SOURCE
Repository:
ACICP302ICS-Network-Security-and-Attacks

Canonical lab source:
labs/ot-security/student-lab-source/

Verified source commit:
2a66f9bcf253eb3fe31c68ad52794cd535421da8


LAB SCOPE AND SAFETY

This submission documents work performed using the supplied ACICP302ICS
OT Security Simulation.

All simulated ICS communication was restricted to loopback:
127.0.0.1

No real or external ICS/OT system was targeted.

No bridged networking, port forwarding, or external network access was
used during the lab execution.

The archive-original simulator was not executed.

The supplied scripts and default lab targets were used without modifying
their target addresses, ports, request counts, durations, or thread
counts.

The four lab services were stopped after testing.


SUBMISSION CONTENTS

FINAL_REPORT/
    Complete practical-lab report in Microsoft Word format.

evidence/screenshots/
    Numbered screenshots supporting the activities, controlled
    demonstrations, guard analysis, and recovery.

evidence/pcap/
    Baseline Modbus/TCP packet capture from the supplied simulation.

docs/
    Evidence index and evidence-to-activity traceability information.


KEY VALIDATION FINDINGS

1. Normal plant operation was established through the supplied direct
   and guarded dashboards.

2. Modbus/TCP communication was observed locally through Wireshark.

3. The direct plant path accepted unsafe false-data values, demonstrating
   that the direct path does not provide the validation performed by the
   guard.

4. The guarded path rejected out-of-range and cumulative-drift writes.

5. The supplied guard did not detect the demonstrated repeated,
   identical, in-range replay writes. This limitation is documented in
   the final report.

6. Recovery was verified after the controlled demonstrations.


EVIDENCE

Evidence numbering and descriptions are provided in:

docs/EVIDENCE_INDEX.md

The complete interpretation, findings, risk assessment, validation
results, recovery observations, and conclusion are provided in:

FINAL_REPORT/ACICP302ICS_Module_1_Practical_Lab_Final_Report.docx


FINAL SAFETY STATE

At completion:

- Lab services were stopped.
- Local listeners on ports 5020, 5021, 8080 and 8081 were stopped.
- The Ubuntu VM network interfaces used for external connectivity were
  DOWN.
- Loopback 127.0.0.1 remained available.
- The final Git working tree was clean.
- The verified source commit was:
  2a66f9bcf253eb3fe31c68ad52794cd535421da8


SUBMISSION NOTE

This repository is intended to be private and contains assessment
evidence. It should not be made public.