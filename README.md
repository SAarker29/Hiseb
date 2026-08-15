# দৈনিক হিসাব খাতা

A Flutter Android ledger app with permanent local storage.

## Build APK with GitHub — no Android Studio required

1. Create a new GitHub repository.
2. Upload **all files and folders from this project** to the repository.
3. Open the repository's **Actions** tab.
4. Select **Build Android APK**.
5. Click **Run workflow**.
6. Wait for the workflow to finish.
7. Open the completed workflow run.
8. Under **Artifacts**, download `daily-ledger-release-apk`.
9. Extract the downloaded artifact to get `app-release.apk`.

The workflow is already included at:

`.github/workflows/build-apk.yml`

The APK is built in GitHub's cloud environment, so Android Studio is not required on your computer.

## Local build

If Flutter is installed locally:

```bash
flutter pub get
flutter build apk --release
```

APK:
`build/app/outputs/flutter-apk/app-release.apk`
