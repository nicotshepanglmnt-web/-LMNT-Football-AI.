# LMNT Football AI (Starter)

Android starter project for LMNT Football AI. It currently provides a usable offline demo:
- Match prediction calculator using editable team strength, recent form, and home advantage
- 1X2 probability estimates, goal estimate, and illustrative scoreline
- BTTS and Over/Under 2.5 estimates
- Saved prediction history on the device (local browser storage)
- Responsive dark mobile interface

## Important
This starter does **not** fetch live fixtures or odds yet. Demo predictions are estimates from the entered inputs, not a trained model and not betting advice. Do not treat probabilities as guarantees.

## Build an APK using GitHub on Android
1. Download and unzip this project.
2. Create a new repository on GitHub named `LMNT-Football-AI`.
3. In the repository, choose **Add file → Upload files** and upload the contents of this folder (not the outer folder).
4. Commit the files to the `main` branch.
5. Open the repository's **Actions** tab and enable Actions if prompted.
6. Open the workflow named **Build LMNT Football AI APK** and choose **Run workflow** if it has not started automatically.
7. Wait for the run to finish successfully. Open the run, scroll to **Artifacts**, and download `LMNT-Football-AI-debug-apk`.
8. Extract the downloaded artifact ZIP and install `app-debug.apk` on your Android phone. You may need to allow installation from your browser or file manager for this one-time install.

## Next version
Connect a free football data provider for real fixtures/results, add proper historical backtesting, and calibrate probabilities against completed matches. Never store API secrets directly in the app source.
