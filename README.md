<p align="center">
  <img src="logo.png" alt="Skriva" width="88" />
</p>

<h1 align="center">Skriva</h1>

<p align="center">
  <strong>Notes, tasks, and contacts for you — and for your team.</strong>
</p>

<p align="center">
  Local-first · Built for teams · Offline-ready · No Skriva account · <strong>Testing phase</strong>
</p>

<p align="center">
  <strong>macOS · Windows · Linux</strong>
</p>

<p align="center">
  <a href="https://github.com/impishraptor/skriva-app/releases/latest">
    <img alt="Download latest release" src="https://img.shields.io/badge/Download-v1.0.20-2f6f5e?style=flat-square&logo=github" height="28" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/impishraptor/skriva-app/releases/latest"><strong>Download latest release</strong></a>
  ·
  <a href="#testing-phase">Testing</a>
  ·
  <a href="#install">Install</a>
  ·
  <a href="#what-you-get">Features</a>
  ·
  <a href="#privacy">Privacy</a>
</p>

---

## Testing phase

Skriva is **in testing** right now. You’re welcome to download it, try it on your machines, and use it freely while we improve the product.

- No account required — install and start
- Available for **macOS**, **Windows**, and **Linux**
- Expect rough edges; things can change between updates
- Feedback helps — open a [GitHub Issue](https://github.com/impishraptor/skriva-app/issues) if something breaks or feels off

This is not a final “finished” product yet. Treat it as an open test build you can explore without ceremony.

---

## What is Skriva?

Skriva is a desktop app for **notes**, **tasks**, and **contacts** — built so people can **work on the same information as a team**, without putting everything in a SaaS silo.

Your data lives on **your machine** and works **offline**. Share a workspace with teammates (or your other devices) by pointing Skriva at a folder your cloud already syncs — iCloud Drive, Dropbox, OneDrive, a shared drive, and similar. Everyone stays in sync on the **same notes, tasks, and contacts** — including **tasks delegated** to teammates. There is **no Skriva account** and **no Skriva server** holding your content.

This repository is for **downloads and updates** only. Builds here are **test releases** — free to try.

---

## Install

### macOS (Apple silicon)

1. Open the [**latest release**](https://github.com/impishraptor/skriva-app/releases/latest).
2. Download the **`.dmg`**.
3. Open it and drag **Skriva** into **Applications**.
4. Launch Skriva from Applications or Spotlight.

> Prefer the in-app path later: **Settings → Check for updates**, or use **Download DMG** if automatic update isn’t available.

### Windows (x64)

Windows builds ship with every release starting with **1.0.14**.

1. Open the [**latest release**](https://github.com/impishraptor/skriva-app/releases/latest).
2. Download **`Skriva Setup … .exe`** (x64 installer).
3. Run the installer and follow the prompts (you can choose the install folder).
4. Launch **Skriva** from the Start menu or desktop shortcut.

> The Windows installer is **unsigned** for now. Windows SmartScreen may show “Windows protected your PC” / unknown publisher — choose **More info → Run anyway** if you trust this download. Code signing will come later.

On Windows you can also use **Settings → Check for updates**, or download the latest Setup `.exe` from Releases.

### Linux

From the [**latest release**](https://github.com/impishraptor/skriva-app/releases/latest), pick what matches your system:

| Package | Best for |
| --- | --- |
| **`.AppImage`** | Most distros — make executable and run |
| **`.deb`** | Debian, Ubuntu, and derivatives |
| **`.pkg.tar.zst`** | Arch Linux and derivatives |

**AppImage**

```bash
chmod +x Skriva-*.AppImage
./Skriva-*.AppImage
```

**Debian / Ubuntu**

```bash
sudo dpkg -i skriva_*_amd64.deb
# if needed:
sudo apt-get install -f
```

**Arch**

```bash
sudo pacman -U skriva-*-x86_64.pkg.tar.zst
```

---

## What you get

| | |
| --- | --- |
| **Teams** | Share one workspace via a sync folder; assign and **delegate tasks** to teammates |
| **Notes** | Rich writing, tables, images, attachments, links between notes, offline spellcheck |
| **Tasks** | Lists and boards, due dates, reminders, recurrence — **delegate work to team members** |
| **Contacts** | People you care about, keep-in-touch prompts, birthdays |
| **Home** | A calm dashboard for focus, follow-ups, and what’s next |
| **Quick capture** | Grab a thought without breaking flow |
| **Search** | Find notes, tasks, and people quickly |
| **Local-first** | Fully usable offline; your files stay on your devices |
| **Shared sync** | Same workspace across **teammates and machines** through a folder you control |

---

## Updates

Skriva can check for new versions from this repository.

- **macOS** — use **Settings → Check for updates**, or install the latest `.dmg` from Releases.
- **Windows** — use **Settings → Check for updates**, or download the latest Setup `.exe` from Releases.
- **Linux** — download the package for your distro from the latest release and install over the previous version.

Always prefer the **[latest release](https://github.com/impishraptor/skriva-app/releases/latest)** page for first-time installs.

---

## Privacy

- No Skriva account.
- No Skriva-hosted cloud for your notes, tasks, or contacts.
- Team and multi-device sync use **a folder you choose** (personal or shared).
- Your data stays on **your machines** and in the storage **you** already trust for that folder.

---

## Support

Found a bug, install problem, or something that feels off? Please **[open an issue](https://github.com/impishraptor/skriva-app/issues/new)** on this repository — that is the best way to report it while Skriva is in testing.

You can also browse [existing issues](https://github.com/impishraptor/skriva-app/issues) before filing a new one.

---

<p align="center">
  <sub>Skriva — your team’s notes, on your machines.</sub>
</p>
