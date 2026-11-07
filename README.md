Firefox:
https://addons.mozilla.org/en-US/firefox/addon/duolingo-max-fork-ia/

About this extension
🔄 Why this Fork? (The Backstory)

As noted by the original author (apersongithub) in release 3.6, Duolingo began retiring Duolingo for Schools, which broke the core codebase that powered 1 to 2/3 of the standalone Unlimited Hearts patches. Because the original author decided to move on and leave those legacy methods behind without exploring the alternatives, this fork picks up where they left off.

Rather than letting the extension die with the old school-based workarounds, this version drops the outdated dependency entirely and implements modern, direct network and API interception.

🛠 What Was Fixed & Re-engineered

Removal of the Schools Dependency: Cleaned out the legacy hacks that relied on the retiring Duolingo for Schools infrastructure.

Direct Network Hooking (fetch & GraphQL): Rebuilt the patching layer (patch4.js to patch7.js and shared/patches.js) to intercept live API and GraphQL responses in real-time. This forces the client app to recognize active gold_subscription, super, max, and unlimited hearts parameters dynamically.

Modernized Store & Browser Compatibility: Refined extension manifests, fixed resource accessibility warnings, and ensured smooth performance across both Firefox (Manifest V2 compliance) and Chromium browsers.

🚀 Features

Duolingo Max & Super Support: Unlocks advanced conversational and learning modules.

Unlimited Hearts: Enjoy mistake-free learning without running out of health.

Standalone Operation: Works out-of-the-box on your personal account without needing teacher/student school setups.

Disclaimer: This project is an independent open-source contribution for educational and research purposes. It is not affiliated with or endorsed by Duolingo.
