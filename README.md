# ZIPSPEED Privacy Policy

Public policy source for **ZIPSPEED by AnakinYoo**.

- Package: `com.aistudio.zipspeed.zskt`
- Version: `85.0.0`
- Canonical app source: `dachopol/ZIPSPEEDmain`
- Current build: no Ads SDK, Firebase Analytics SDK, Billing SDK, account system, or Android location permission.
- Measurement provider currently documented: Cloudflare Network Quality.

The policy must be re-checked whenever the app's permissions, SDKs, endpoints, data handling, Ads, Billing, or account behavior changes.

Checked repository `index.html` presents version 85.0.0, matching the checked ZIPSPEEDmain `package.json`. Historical Pages PASS is not fresh live-host evidence.

## LandMeasure Global

Public policy page for **LandMeasure Global by AnakinYoo**.

- Public page: https://dachopol.github.io/privacy-policy/landmeasure/
- Package: `com.anakinyoo.landmeasure`
- Version stated in the checked policy HTML: `1.5.0` (historical policy source, not verified live deployment).
- Current app source: `1.6.0` (`versionCode 7`), verified from LandMeasure-Global `app/build.gradle.kts` at `b1b523caa95000163b03ed39a1f76f82470f8f8c`.
- Policy-to-app version alignment: **TO VERIFY** before release; the policy page is not silently relabelled.
- Canonical app source: `dachopol/LandMeasure-Global`
- Current release behavior documented: foreground location, local parcel storage, optional Google Maps/Geocoder paths, explicit user-initiated Netherlands PDOK/Kadaster lookup, GeoJSON/KML export, and no Ads/Analytics/Billing/account SDKs.

GitHub Pages publication status: historical deployment reported PASS; current served content and suitability for app v1.6.0 are **TO VERIFY**.


## UCISE Local — คู่มือเริ่มต้นและ Documentation Gate / Getting started

<!-- UCISE_DOCUMENTATION_GATE_V1 -->

**ขั้นตอนเริ่มต้น (TH):** อ่านนโยบายของ ZIPSPEED และ LandMeasure Global → เทียบกับ source และรุ่นของแอปจริง → ตรวจ permissions, SDK, endpoints, ads, billing และ data handling → บันทึกความแตกต่างก่อนแก้นโยบาย → ตรวจลิงก์และสถานะ GitHub Pages แยกจาก source. ไม่มีขั้นตอนรันแอปใน repository นโยบายนี้.

**Getting started (EN):** Read the project-specific sections above. Confirm exact version, authorized workspace, platform and prerequisites before following any command. Run only documented, authorized steps; record actual output and errors. Do not infer runtime or release readiness from this documentation.

### Required documentation before closing work

- [ ] Purpose, exact version/source identity, prerequisites and installation/configuration.
- [ ] Step-by-step user workflow, examples, expected outputs, and TH/EN guidance appropriate to the audience.
- [ ] Build/run/test commands from actual source where applicable; record host, exact command, exit status and evidence. Untested commands are NOT_VERIFIED, not PASS.
- [ ] Architecture, permissions, safety constraints, troubleshooting, recovery/rollback and limitations.
- [ ] AI handoff: checkpoint, changed files, remaining tasks, dependency and next authorized action; research assumptions and evidence scope when applicable.
- [ ] Review existing documentation first; update it without duplication; never copy secrets or local-only data to the cloud.

Use README sections or existing linked guides; split into QUICKSTART, USER_GUIDE, AGENTS, TESTING, SECURITY, RESEARCH or RECOVERY files only when useful. Missing required documentation or evidence keeps the relevant DoD item INCOMPLETE/BLOCKED. This checklist is not a test receipt, native approval, release authorization or permission to bypass Owner/Watchdog Hold. Production and existing security gates remain unchanged. Documentation-only candidate; command execution and independent QA are NOT_RUN in this edit.

### Policy verification and recovery / ตรวจสอบนโยบายก่อนเผยแพร่

1. Compare `index.html` and `landmeasure/index.html` against the exact intended app source revision, package, version, manifest permissions, direct and transitive SDKs, data collection, storage, sharing, and user-facing behavior. The checked LandMeasure manifest declares foreground fine/coarse location and INTERNET; its Gradle source declares Maps Compose and Play Services Location. These are source observations, not runtime or complete transitive-SDK verification.
2. Treat build/run of an Android app as N/A for this policy-only repository; app builds and device QA belong to the linked canonical app repos. Validate the HTML locally as inert text before rendering in an authorized isolated browser. Check Thai/English equivalence, links, declared version, mobile layout and accessibility. Do not treat a file read as a live GitHub Pages deployment check.
3. Keep the existing policy wording until the owner-approved privacy/data-safety review establishes any necessary changes. Record evidence for the exact intended version; verify actual served URLs and deployment after a separately authorized publication. No publish, deployment, or change to HTML was performed in this PR.
4. หากไม่ตรงกับแอป ให้คงสถานะ TO VERIFY และระบุรายการที่ไม่ตรง; ห้ามระบุ PASS จากการเปลี่ยนเลขเวอร์ชันอย่างเดียว. Rollback: preserve the prior policy content and deployment until review, and use the established approved release process if restoration is needed.
