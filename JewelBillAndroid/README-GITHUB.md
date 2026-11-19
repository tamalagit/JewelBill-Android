# Build Jewel Bill APK with GitHub (no Android Studio required)

1. Create a free GitHub account at https://github.com/ if you do not already have one.
2. Create a new repository, for example `JewelBill-Android`.
3. Upload the **contents** of this project ZIP to the repository (the folders `app`, `.github`, and the Gradle files should be at the repository root). Do not upload customer/billing data.
4. Open the repository's **Actions** tab. If GitHub asks, enable Actions for the repository.
5. Select **Build Jewel Bill APK** from the workflow list, tap **Run workflow**, then **Run workflow** again.
   - A push to the `main` or `master` branch also starts the build automatically.
6. Wait for the run to finish with a green check mark. Open that run, scroll to **Artifacts**, and download `JewelBill-debug-apk`.
7. Extract the downloaded artifact ZIP. It contains `app-debug.apk`. Open that APK on your Android phone to install it.

The workflow builds a debug APK, which is suitable for testing and direct installation. It is not a Play Store release APK. Keep your repository private if you do not want the app source publicly visible. GitHub Actions artifacts are temporary build outputs; download and keep a copy.
