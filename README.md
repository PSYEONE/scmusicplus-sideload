<p align="center">
  <img src="https://rov3r.github.io/depictions/assets/images/scmusicplus-icon.png" width="150" title="SCMusicPlus">
</p>

# SCMusicPlus
Enhance your SoundCloud experience with the following features:
- Remove Ads
- Remove Promoted Playlists
- Remove Upsell Buttons

Note: To ensure all ads are blocked, use a DNS filter like nextDNS to block the domain 'ads.soundcloud.com'

# Building
You can build the project any time using GitHub actions. Just run build.yml and you will get both rootful and rootless debs in a zip file.

# Installation

Sideloaded (Developer Account): **UPDATED 2025**
- Until fixed, users will have to link a Google or Facebook account to their SoundCloud. This can be done on the SoundCloud website.
- Download the .ipa (application file) from a source of your choosing. (I chose armconverter decrypyed store with version 7.56.0)
- Use Sideloadly to merge the deb (in Releases) with the ipa:
  * Drag the decrypted .ipa file into Sideloadly
  * Click Advanced Options, Check Inject dylibs and choose the .deb file.
  * Make sure both Cydia Substrate and Sideload Spoofer is checked.
  * Click Start.
  * New injected IPA will be outputted.
- Install using your preferred sideloading method** (AltStore, Sideloadly, appdb, etc.)
- Once installed, sign in using only via Google or Facebook. Regular email (including gmail) doesn't work for now. This will be addressed in a future update.

For troubleshooting assistance, please see the issues section of this repository.

# Depiction
For the most updated package depiction, including changelogs and known bugs, you can view it here: https://rov3r.github.io/depictions/scmusicplus.html
