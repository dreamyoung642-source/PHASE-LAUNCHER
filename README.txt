PHASE LAUNCHER - iOS (unsigned IPA builder)

You do NOT need a Mac. GitHub builds the IPA for you, free.

1. Make a free account at github.com and create a new repository (Public is simplest).
2. Upload everything in this folder to it, including the hidden ".github" folder.
   Tip: if ".github" does not upload, click "Add file > Create new file",
   type  .github/workflows/build-ipa.yml  as the name, and paste the contents of
   build-ipa.yml.txt into it.
3. Open the repo's "Actions" tab > "Build IPA" > "Run workflow". Wait about 5 minutes.
4. Open the finished run, scroll to "Artifacts", download "PhaseLauncher-ipa"
   and unzip it. Inside is PhaseLauncher.ipa (unsigned).
5. Sign and install it with one of:
   - Sideloadly (Windows/Mac) with your Apple ID. Free IDs last 7 days.
   - AltStore, same idea, refreshes itself over Wi-Fi.
   - TrollStore, no signing needed, on supported iOS versions only.
