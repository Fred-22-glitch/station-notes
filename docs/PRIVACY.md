# Privacy

- Notes are stored only on your device and, if you choose, in the vault folder you pick. No notes, drawings or files are sent to the author or to third parties.
- No account, login, ads, tracking or usage analytics.
- Network access is limited to the update check below, the optional study AI download and, with Pro active, the refunded-keys list (both described further down). The update check: the app queries the project's GitHub releases (`api.github.com`) and, if you choose to update, downloads the installer from there. GitHub receives the usual technical data of any request (such as your IP address), covered by GitHub's own privacy policy.
- Device sync (optional): only after you pair with a code, the app exchanges notes and the Pro key, encrypted with AES-256-GCM, with your devices on the same local network. Nothing goes through the internet or to any server. A device name is announced on the network only after a device is paired or while a code is showing.
- Study AI (Pro, optional): only when you choose "Download the AI", the app downloads the model file from Hugging Face (`huggingface.co`): Qwen3 4B (~2.5 GB), on Android optionally Gemma 4 E2B (~2.6 GB), or on Windows optionally Qwen3 1.7B (~1.1 GB). Inference runs locally on the device; note text is never sent anywhere.
- Android permissions: access to the vault folder you select through the system folder picker, internet (updates only), Wi-Fi state and multicast (device sync on the local network), vibration (long-press feedback) and installing app updates (requested by Android when updating).
- Read aloud uses the device's own text-to-speech voice (Windows or Android). Station Notes doesn't send the text anywhere.
- If you activate Station Notes Pro, the key is stored on the device and in the vault folder. It contains the email used for the purchase and is verified offline. With Pro active, the app downloads, at most once a day, the public list of keys cancelled by refund (from the OmniStation website, `loxkbkphvovkzhkcyfjz.supabase.co`) and compares it on the device. Nothing is sent: neither the key nor the email.
- Automatic backups stay on the device: `Documents/Station Notes/backups` on Windows and the app's own folder under `Android/data` on Android (or the app's internal storage when that folder can't be written). The study AI model files are left out of Android's cloud backup.
- To remove all data, uninstall the app and delete the vault folder and the backups folder.

See [LICENSE](../LICENSE) for the terms of use.

[Back to README](../README.md)
