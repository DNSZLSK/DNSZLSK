<div align="center">

<h1>DNSZLSK</h1>

Master’s student in Software Architecture and Development (work-study).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kewin-poszalski)

</div>

---

### [MUAD'DIB](https://github.com/DNSZLSK/muad-dib) - Supply chain security scanner

Scanner open-source npm/PyPI (AGPL-3.0). Monitoring 24/7, analyse chaque nouveau package publié. Sandbox gVisor, analyse temporelle, détection d'ATO.

```bash
npx muaddib-scanner scan .
```

- 22 scanners (AST, dataflow, obfuscation, sandbox gVisor, temporal diff, taint tracking)
- ~256K IOCs (243K npm, 12K+ PyPI)
- 4545 tests, 277 règles, TPR 92.8% (Datadog 17K), FPR 1.10%
- [Blog](https://dnszlsk.github.io/muad-dib/blog/) · [npm](https://www.npmjs.com/package/muaddib-scanner) · [VS Code](https://marketplace.visualstudio.com/items?itemName=dnszlsk.muaddib-vscode) · GitHub Action

Stack : Node.js, Docker, gVisor, tree-sitter WASM, Acorn, SARIF

---

### [DDD (DigDigDig)](https://github.com/DNSZLSK/digdigdig) - DJ library toolkit

App desktop pour DJs : classe chaque fichier par coupure spectrale, retrouve une meilleure version sur Soulseek, la vérifie et l'ajoute à la bibliothèque sans toucher aux originaux.

- Scan qualité : 4 niveaux (Wide / HQ / Iffy / Review), spectrogramme par track, doublons, cache de rescan. Lit FLAC, WAV, AIFF, MP3, OGG/Opus, M4A (AAC/ALAC), WMA, APE, WavPack
- Identification audio : Chromaprint + AcoustID, renommage proposé puis validé track par track
- Tri par genre : tags ID3, puis Discogs/MusicBrainz, puis Discogs-EffNet (ONNX local, 400 styles)
- Pipeline : favoris Discogs/Bandcamp, sets YouTube, likes SoundCloud → Soulseek → vérification → bibliothèque. Introuvable → page de liens d'achat
- [Landing page](https://dnszlsk.github.io/digdigdig) · Windows .exe · macOS Apple Silicon · Docker

Stack : Python, Flet, sldl, numpy/scipy, PyAV, onnxruntime, yt-dlp, GitHub Actions

---

### [LATENTIS](https://github.com/DNSZLSK/latentis) - Latent Data Refinement since 1974

*"The work is important. Its nature is not your concern."*

Mod Claude Code : pendant que ton agent travaille, ton Session Self trie des tokens suspects dans quatre départements. Satire corporate de l'industrie de l'IA, en grille de chiffres façon écran cathodique.

- 4 bacs : Hallucination, Sycophancy, Repetition, Overconfidence
- Maximes du fondateur Elias Gradient, badges volontairement décevants, heures sup non payées
- Sécurité : aucun process, aucun réseau, aucun hook d'outil, seul `.git/HEAD` est lu
- [Corporate site](https://dnszlsk.github.io/latentis) · MIT

```
/plugin marketplace add DNSZLSK/latentis
/plugin install latentis@latentis
```

Stack : TypeScript, Claude Code function hooks, Ink

---

### OPAC Plérin - Site WordPress FSE

Site complet pour une association culturelle. Thème FSE custom, 6 Custom Post Types, workflow d'inscription (paliers, waitlist, promotion), envoi d'emails en masse, PWA.

- [opacplerin.fr](https://opacplerin.fr)

Stack : WordPress FSE, PHP, MySQL, OVH

---

### [GitCoach](https://github.com/DNSZLSK/gitcoach-cli) - CLI d'apprentissage Git

11e/400 au GitHub Copilot CLI Challenge. CLI TypeScript, 1036 tests, i18n, 5 intégrations Copilot.

- [npm](https://www.npmjs.com/package/gitcoach-cli)

---

<div align="center">

*"The code must flow."*

> Code écrit avec Claude (Anthropic). Architecture, méthodologie, tests et audits : moi.

![Visitors](https://komarev.com/ghpvc/?username=DNSZLSK&color=00ff00&style=flat-square)

</div>
