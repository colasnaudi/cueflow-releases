<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/cueflow-logo-dark.svg">
    <img src=".github/cueflow-logo-light.svg" alt="Cueflow" width="248">
  </picture>
</p>

<p align="center">
  <strong>Your tracks ready to mix, analysed on your Mac.</strong><br>
  BPM, beatgrid, bar 1, key and hot cues, sent to Rekordbox or Serato. Fully offline.
</p>

<p align="center">
  <a href="https://github.com/colasnaudi/cueflow-releases/releases/latest"><b>Download the latest version</b></a>
  ·
  <a href="https://cueflow.fr">Website</a>
  ·
  <a href="https://cueflow.fr/docs/">Docs</a>
  ·
  <a href="https://cueflow.fr/versions">What's new</a>
</p>

---

This repository only hosts the **downloads** of the Cueflow app. The app's source code is not public.

## Requirements

| | |
| --- | --- |
| **Mac** | Apple Silicon (M1, M2, M3, M4…). Intel Macs are not supported. |
| **macOS** | 15 Sequoia or later. |
| **Licence** | A subscription, 4.99 EUR a month or 39 EUR a year, for 1 Mac. Free 14-day trial, no card. |
| **Internet** | To activate, then at least once a week for the licence check. Analysis works offline. |

To check your Mac: Apple menu > **About This Mac**.

## Install

1. Download `Cueflow-x.y.z-arm64.dmg` from the [latest release](https://github.com/colasnaudi/cueflow-releases/releases/latest).
2. Open it and drag **Cueflow** to your **Applications** folder.
3. Launch Cueflow. It is signed and notarised by Apple: it opens at once.
4. Click **Try free for 14 days**, or paste your `CUEF-` key and click **Activate**.

## Updates

Cueflow tells you when a new version is out (and from the menu: **Cueflow** > **Check for Updates…**).
Download it here, then replace Cueflow in your Applications folder: your library, your analyses and your licence
are kept. Coming from 0.2.0: its activation codes do not work with 1.0, start the trial or use a `CUEF-` key. What each version brings, and how accurate its analysis is: [cueflow.fr/versions](https://cueflow.fr/versions).

## Check your download

Each release lists the SHA-256 of its DMG. In Terminal:

```bash
shasum -a 256 ~/Downloads/Cueflow-*-arm64.dmg
```

The result must match the one in the release notes.

## Your files stay yours

Cueflow reads your music folder and never rewrites a tag or a file, with one exception you choose: a send to
Serato writes Serato's own cue and grid tags into MP3, WAV and AIFF files, after a byte-identical backup, and can be
undone. Analysis runs on your Mac; nothing from your library is uploaded.

---

<details>
<summary><b>En français</b></summary>

<br>

**Cueflow** analyse et prépare ta bibliothèque DJ sur ton Mac : BPM, beatgrid, première mesure, tonalité,
structure et hot cues, envoyés vers Rekordbox et Serato. Tout hors ligne.

**Configuration :** un Mac Apple Silicon (M1 ou plus récent) avec macOS 15 Sequoia ou plus récent, et un
abonnement (4,99 € par mois ou 39 € par an, pour 1 Mac), avec un essai gratuit de 14 jours sans carte.

**Installation :**

1. Télécharge le DMG de la [dernière version](https://github.com/colasnaudi/cueflow-releases/releases/latest).
2. Ouvre-le et glisse **Cueflow** dans **Applications**.
3. Lance Cueflow. Il est signé et notarisé par Apple : il s'ouvre tout de suite.
4. Clique sur **Essayer 14 jours gratuits**, ou colle ta clé `CUEF-` et clique sur **Activer**.

**Mises à jour :** Cueflow te prévient quand une nouvelle version sort. Télécharge-la ici et remplace l'app dans
Applications : ta bibliothèque, tes analyses et ta licence sont conservées. Depuis la 0.2.0 : ses codes
d'activation ne marchent plus avec la 1.0, lance l'essai ou utilise une clé `CUEF-`.
[Ce que chaque version apporte](https://cueflow.fr/versions).

</details>

<p align="center"><sub>© 2026 Colas Naudi · <a href="https://cueflow.fr/legal/licences.html">Open source licences</a></sub></p>
