# Stratum Launcher

An independent Windows launcher for Minecraft: Java Edition, with supported version/patch selection, compatible Modrinth downloads, and eleven configurable client modules.

This repository contains the small public project website. It does not contain the large Windows installer, dependencies, or game downloads.

## Features

- Ten version families and thirteen exact supported game patches.
- Separate compatible client files, community mods, worlds, and HUD preferences for each patch.
- Direct Modrinth searches/downloads with version and loader filtering and required dependency checks.
- A smooth Right Shift module menu, detailed options, and a draggable/resizable HUD.
- Microsoft browser authorization with PKCE, Xbox Live/XSTS, and Minecraft Services entitlement/profile checking before normal game launch.
- Windows-protected encrypted session storage. Passwords are entered on Microsoft's sign-in page.

The current developer preview is 1.2.1. Microsoft browser authorization reaches Stratum, but Minecraft Services application approval is still required before account sign-in can complete. This website does not claim approval or link a public installer yet.

## Publish this website with GitHub Pages

Keep `index.html`, `styles.css`, `.nojekyll`, and the `assets` folder at the repository root. For a free GitHub Pages site, use a public repository. Under **Settings → Pages**, choose **Deploy from a branch → main → /(root) → Save**. Use the actual published URL displayed there for the AppID review form.

## Large launcher files

The 125 MB Windows executable belongs in a GitHub **Release** as an attached release asset. Do not upload it as a normal repository file. The launcher source ZIP can also be attached to the release; keeping source as normal code files requires extracting it first and excluding generated dependencies/build caches.

The repository website and the launcher installer are separate uploads. No purchased custom domain is required to use GitHub's provided Pages address.

Stratum's source and original brand artwork are MIT licensed. Minecraft imagery belongs to Mojang/Microsoft. Stratum is independent and not affiliated with Mojang, Microsoft, or Lunar Client.
