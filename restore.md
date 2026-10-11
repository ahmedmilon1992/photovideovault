# Backup & Restore Guide — Photo & Video Vault

Your vault is encrypted with keys only you hold, so a backup is only useful if you also have your **secret** (PIN / password / pattern) **or your recovery key**. Keep the recovery key somewhere safe and separate from your phone.

## Two ways to back up

### 1. iCloud backup (Pro)
Settings → Backup and recovery → turn on *Back up this space to iCloud Drive*. The app mirrors your encrypted vault into iCloud Drive → Photo & Video Vault. The status shows *Local only*, *Uploading* or *Uploaded*. Each vault (main and hidden) is backed up separately and only while it is unlocked.

### 2. Encrypted archive (Pro)
Settings → Backup and recovery → *Export encrypted archive*. This saves a `.pvvault` folder to Files. Copy it to a computer, a drive or any cloud — it stays encrypted.

## Test your backup
Settings → Backup and recovery → *Restore rehearsal*. The app opens your backup with your recovery key and shows sample photos coming back, without touching your real data. Do this after large imports.

## Restore on a new iPhone
1. Install Photo & Video Vault.
2. On the welcome screen choose *Restore a vault* (or *Restore from archive* on the unlock screen).
3. Pick the `.pvvault` folder from Files or from iCloud Drive → Photo & Video Vault.
4. Enter the vault's secret or recovery key. Every file is verified before anything is installed.
5. Unlock as usual. Repeat for the hidden vault if you had one.

## If you lose your phone
Your data is safe: without your secret or recovery key the files are unreadable. Restore from iCloud or your archive on the new phone as above.

Questions: https://ahmedmilon1992.github.io/photovideovault/support
