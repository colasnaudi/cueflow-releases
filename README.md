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

**Cueflow** prépare tes morceaux pour le mix, sur ton Mac : BPM, beatgrid, première mesure, tonalité, structure et
hot cues, envoyés vers Rekordbox ou Serato. Tout se fait hors ligne.

Ce dépôt ne contient que les **téléchargements** de l'app Cueflow. Le code source de l'app n'est pas public.

### Configuration requise

| | |
| --- | --- |
| **Mac** | Apple Silicon (M1, M2, M3, M4…). Les Mac Intel ne sont pas pris en charge. |
| **macOS** | 15 Sequoia ou plus récent. |
| **Licence** | Un abonnement, 4,99 € par mois ou 39 € par an, pour 1 Mac. Essai gratuit de 14 jours, sans carte bancaire. |
| **Internet** | Pour l'activation, puis au moins une fois par semaine pour vérifier la licence. L'analyse marche hors ligne. |

Pour vérifier ton Mac : menu Pomme > **À propos de ce Mac**.

### Installation

1. Télécharge `Cueflow-x.y.z-arm64.dmg` depuis la [dernière version](https://github.com/colasnaudi/cueflow-releases/releases/latest).
2. Ouvre-le et glisse **Cueflow** dans ton dossier **Applications**.
3. Lance Cueflow. Il est signé et notarisé par Apple : il s'ouvre tout de suite.
4. Clique sur **Essayer 14 jours gratuits**, ou colle ta clé `CUEF-` et clique sur **Activer**.

### Mises à jour

Cueflow te prévient quand une nouvelle version sort (et depuis le menu : **Cueflow** > **Check for Updates…**).
Télécharge-la ici, puis remplace Cueflow dans ton dossier Applications : ta bibliothèque, tes analyses et ta licence
sont conservées. Si tu viens de la 0.2.0 : ses codes d'activation ne marchent pas avec la 1.0, lance l'essai ou
utilise une clé `CUEF-`. Ce que chaque version apporte, et la précision de son analyse :
[cueflow.fr/versions](https://cueflow.fr/versions).

### Vérifier ton téléchargement

Chaque version indique le SHA-256 de son DMG. Dans le Terminal :

```bash
shasum -a 256 ~/Downloads/Cueflow-*-arm64.dmg
```

Le résultat doit être identique à celui des notes de la version.

### Tes fichiers restent à toi

Cueflow lit ton dossier de musique et ne réécrit jamais un tag ni un fichier, sauf une exception que tu choisis :
un envoi vers Serato écrit les tags de cues et de grille propres à Serato dans les fichiers MP3, WAV et AIFF, après
une sauvegarde identique à l'octet près, et peut être annulé. L'analyse se fait sur ton Mac : rien de ta bibliothèque
n'est envoyé.

</details>

<p align="center"><sub>© 2026 Colas Naudi · <a href="https://cueflow.fr/legal/licences.html">Open source licences</a></sub></p>
