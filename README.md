<div align="center">

<h1>DNSZLSK</h1>

CDA @ AFPA Bretagne · Expert EADL @ ENI (nov. 2026)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kewin-poszalski)

</div>




---
 
### [MUAD'DIB](https://github.com/DNSZLSK/muad-dib) - Supply chain security scanner
 
Scanner open-source npm/PyPI (AGPL-3.0). Monitoring 24/7, analyse chaque nouveau package publié. Sandbox gVisor, analyse temporelle, détection d'ATO.
 
```bash
npx muaddib-scanner scan .
```
 
- 21 scanners (AST, dataflow, obfuscation, sandbox gVisor, temporal diff, taint tracking)
- ~288K IOCs (271K npm, 16K+ PyPI)
- 4540 tests, 275 règles, TPR 92.8%, FPR 1.10%
- [npm](https://www.npmjs.com/package/muaddib-scanner) · [VS Code](https://marketplace.visualstudio.com/items?itemName=dnszlsk.muaddib-vscode) · GitHub Action · [Blog](https://dnszlsk.github.io/muad-dib/blog/)
Stack : Node.js, Docker, gVisor, tree-sitter WASM, Acorn, SARIF
 
---
 
### [DDD (DigDigDig)](https://github.com/DNSZLSK/digdigdig) - DJ lossless toolkit
 
App desktop pour DJs : vérifie la qualité lossless par analyse spectrale FFT, identifie les tracks via empreinte acoustique (Chromaprint/AcoustID), scrape les tracklists de DJ sets YouTube, acquiert via Soulseek avec vérification automatique.
 
- Scan bibliothèque : détecte les faux FLAC/WAV (upscaled MP3), forensic multi-signal (Tier 0/1/2)
- Identification audio : Chromaprint + AcoustID + MusicBrainz
- Genre sorting : Discogs-EffNet (EfficientNet-B0 ONNX, local, 400 styles)
- Pipeline : wishlist Bandcamp/Discogs → Soulseek → vérif spectrale → bibliothèque
- [Landing page](https://dnszlsk.github.io/digdigdig) · Docker · macOS Apple Silicon
Stack : Python, Flet, sldl, FFT/librosa, ONNX, GitHub Actions
 
---
 
### [LexLuthor](https://github.com/DNSZLSK/lexluthor) - Code subtitler
 
Extension VS Code qui affiche des sous-titres en langage naturel sous le code, comme des VOSTFR de cinéma. 100% déterministe, offline, sans IA. Le dictionnaire est le produit.
 
- tree-sitter WASM (JS/TS), i18n FR/EN/ES
- 612 tests, 74% rich reading
- Monorepo : core, reader, VS Code extension, CLI
Stack : TypeScript strict, tree-sitter WASM, Vitest
 
---
 
### [OPAC Plérin](https://opacplerin.fr) - Site WordPress FSE
 
Site complet pour une association culturelle. Thème FSE custom, 6 Custom Post Types, workflow d'inscription (paliers, waitlist, promotion), envoi d'emails en masse, PWA.
 
Stack : WordPress FSE, PHP, MySQL, OVH

---

### [MUSUBI](https://dnszlsk.github.io/musubi/) - Jeu de puzzle rétro
 
Jeu de logique style CRT inspiré de Glyn. Relie les chiffres, résous les puzzles. PWA installable sur mobile.
 
- 3 modes de difficulté, mode chrono avec leaderboard en ligne
- Puzzle du jour, hints, streaks
- [Jouer](https://dnszlsk.github.io/musubi/) · [GitHub](https://github.com/DNSZLSK/musubi)
Stack : Vanilla JS, Vite, Canvas API, GitHub Pages
 
---
 
### [GitCoach](https://www.npmjs.com/package/gitcoach-cli) - CLI d'apprentissage Git
 
11e/400 au GitHub Copilot CLI Challenge. CLI TypeScript, 522 tests, i18n, 5 intégrations Copilot.
 
---

<div align="center">

*"The code must flow."*

> Code écrit avec Claude (Anthropic). Architecture, méthodologie, tests et audits : moi.

![Visitors](https://komarev.com/ghpvc/?username=DNSZLSK&color=00ff00&style=flat-square)

</div>
