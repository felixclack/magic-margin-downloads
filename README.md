# Magic Margin downloads

Official binary distribution for Magic Margin. This repository contains installer releases and safe release/checksum metadata only.

The latest Mac download is version 0.1.0 for Apple silicon (M1 or newer), requiring macOS 14 or newer. It is ad-hoc signed and is not notarized by Apple. No Intel or iOS installer is offered.

Use the Releases section to download the DMG. Verify its SHA-256 against SHA256SUMS.txt. The source revision and build timestamp are recorded in desktop-release.json and embedded inside the app.

Website: https://magic-margin.kid80.chatgpt.site

Current build: ce0730f (21 October 2026), app 0.1.0, bundled importer 0.2.2. This build replaces Gemma with local Parakeet transcription and adds automatic Live notes with Luna. Live notes is on by default after ChatGPT sign-in and can be switched off. No real account features were exercised during release checks.

The real native speech addon loads from the signed Mac DMG; real lecture audio, model download and OpenAI notes remain unverified. Ad-hoc signed, not Apple-notarized. The native addon requires macOS 14. The cce91e9 importer staging safety correction remains present. Historical releases are retained, including the warning on unsafe 64413b1.
