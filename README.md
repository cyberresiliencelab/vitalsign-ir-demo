# VitalSign IR — public demo

A shareable, open demo of VitalSign IR: a healthcare multi-agent incident-response lab with 58 synthetic scenarios across 12 threat families, 9 controllable AI agents with kill switches and autonomy levels, 32 simulated open-source tools (Wazuh, Velociraptor, Zeek, Suricata, MISP and more), a policy engine with human approval gates, a hash-chained audit log, and an international IR benchmark and regulatory-clock crosswalk (NIST SP 800-61r3, ISO/IEC 27035, HIPAA, GDPR, NIS2, CERT-In, DPDP and others).

**Try it:** open the site and choose **Explore the demo without an account**, or create a local account to try role-based access and MFA.

## What this demo is

- All data is synthetic: reserved test IPs, `.example` domains, tokenised patient IDs.
- Tool outputs are simulated; nothing connects to real systems.
- Everything runs in your browser. Accounts and settings are stored only in your browser's local storage.
- The live AI triage feature only works when the lab runs inside Claude; here it uses the built-in offline engine.

## Deploy your own copy

1. Fork or upload this folder to a public repo named `vitalsign-ir-demo`.
2. Settings → Pages → Source: **GitHub Actions**.
3. Push to `main`; the site appears at `https://<you>.github.io/vitalsign-ir-demo/`.

Do not enter real credentials, patient data or production telemetry.
