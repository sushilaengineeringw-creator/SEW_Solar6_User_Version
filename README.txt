SEW Business Manager v6
Upload ALL files/folders in this folder to your GitHub repository (overwrite):
package.json, capacitor.config.json, debug.keystore, icons, www, .github/workflows/build.yml

OWNER / VENDOR SETUP
1. Build and install this APK on YOUR phone. On first start choose an admin password (Owner setup).
2. Settings > License & security > copy the public key line ("const ADMIN_PUB=...").
3. In GitHub open www/pubkey.js, replace the line  const ADMIN_PUB=null;  with the copied line, commit.
4. The new build is the VENDOR build. Send that APK to vendors. (Install it over your own app too.)
5. Settings > Users & subscription: create a user, choose plan + modules, send them the code + password.
Never give away an APK built with ADMIN_PUB=null: anyone could make themselves admin in it.
