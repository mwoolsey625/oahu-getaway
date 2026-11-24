# Oahu Getaway (private trip page)

The trip page is encrypted (AES-256-GCM, key from the passphrase via PBKDF2-SHA256, 600,000 rounds).
Visitors without the passphrase see only a password box. Nothing readable is stored in this repo.

## Publish
1. Create a new repo and upload every file in this folder to the top level.
2. Settings > Pages > Build and deployment: Deploy from a branch, branch `main`, folder `/ (root)`. Save.
3. After a minute it's live at https://<username>.github.io/<repo-name>/

## Tips
- Open it once while online. After that it works offline (it saves a copy to the phone).
- iPhone: Share > Add to Home Screen for an app-style icon. Enter the passphrase once there.
- To lock a device again, open the page with `?lock` at the end of the address.
- To update: replace index.html with the new one and commit. Phones get it next time they're online.
