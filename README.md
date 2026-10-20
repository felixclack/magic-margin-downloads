# Magic Margin downloads

Official binary distribution for Magic Margin. This repository contains installer releases and safe release/checksum metadata only.

The latest Mac download is version 0.1.0 for Apple silicon (M1 or newer), requiring macOS 13.3 or newer. It is ad-hoc signed and is not notarized by Apple. No Intel or iOS installer is offered.

Use the Releases section to download the DMG. Verify its SHA-256 against SHA256SUMS.txt. The source revision and build timestamp are recorded in desktop-release.json and embedded inside the app.

Website: https://magic-margin.kid80.chatgpt.site

Current build: 6732fd7 (20 October 2026), with bundled importer 0.2.2. It retains the staging-folder safety fix from cce91e9. App version remains 0.1.0. Build 64413b1 is superseded because of an importer staging-directory safety defect; use the corrected release.

This build adds the optional Mac Study coach with ChatGPT plan sign-in preview. Requests require preview and Send; lecture transcripts are opt-in. Real OpenAI sign-in, plan eligibility and usage remain unverified; tests use a simulated provider.
