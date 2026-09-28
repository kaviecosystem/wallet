# Kavi Wallet (Android)

A self-custody wallet for BNB Chain with a built-in dApp browser. Every site opened in Discover connects to Kavi Wallet, and every transaction includes the $0.001 KAVI fee that feeds the hourly jackpot.

## Build the APK with GitHub (no computer setup needed)

1. Create a new repository on GitHub and upload everything in this folder (keep the `.github` folder).
2. Open the **Actions** tab. The "Build Kavi Wallet APK" workflow starts automatically (or press **Run workflow**).
3. When it finishes (about 5 minutes), open the run and download **KaviWallet-apk** under Artifacts.
4. Unzip it and install `app-debug.apk` on your Android phone (allow "Install unknown apps" when asked).

## Build with Android Studio

Open this folder in Android Studio and press Run.

## Where things are

- `app/src/main/assets/www/` — the wallet app (`index.html`, `wallet.js`)
- `app/src/main/assets/kavi-provider.js` — the connection injected into every dApp
- `app/src/main/java/app/kaviwallet/MainActivity.java` — the Android shell and dApp browser
- KaviHub address: `NETS` at the top of `wallet.js`
