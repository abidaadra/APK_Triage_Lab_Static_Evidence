# APK_Triage_Lab_Static_Evidence

**Configuration:** Static-only analysis · API vs open-source LLM comparison · Research + portfolio + practical tool.

This notebook creates an evidence-first APK triage pipeline. It hashes the APK, inspects its ZIP structure, parses Android metadata where possible, extracts DEX strings and network indicators, applies transparent review rules, and exports a JSON evidence bundle.

**Safety:** The APK is treated as untrusted data. This notebook does not install, launch, or execute it. Permissions and strings are indicators for investigation—not proof of malicious behavior.

## Never execute suspicious APKs in this notebook or on your everyday machine.
