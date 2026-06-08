<div align="center">

# DNSZLSK

CDA @ AFPA Bretagne · Expert EADL @ ENI (sept. 2026)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kewin-poszalski)

</div>

---

### [MUAD'DIB](https://github.com/DNSZLSK/muad-dib) - Supply chain security scanner

Scanner open-source npm/PyPI. Monitoring 24/7, analyse chaque nouveau package publié. Sandbox gVisor, analyse temporelle, détection d'ATO.

```bash
npx muaddib-scanner scan .
```

- 14 scanners (AST, dataflow, obfuscation, sandbox gVisor, temporal diff, taint tracking)
- 265K+ IOCs npm, 17K+ PyPI
- 4158 tests, 264 règles, TPR@3 95.74%, FPR 1.10%
- [npm](https://www.npmjs.com/package/muaddib-scanner) · [VS Code](https://marketplace.visualstudio.com/items?itemName=dnszlsk.muaddib-vscode) · GitHub Action

Stack : Node.js, Docker, gVisor, tree-sitter WASM, Acorn, SARIF

---

### [LexLuthor](https://github.com/DNSZLSK/lexluthor) - Code subtitler

Extension VS Code qui affiche des sous-titres en langage naturel sous le code, comme des VOSTFR de cinéma. 100% déterministe, offline, sans IA. Le dictionnaire est le produit.

- tree-sitter WASM (JS/TS), i18n FR/EN/ES
- 612 tests, 74% rich reading
- Monorepo : core, reader, VS Code extension, CLI

Stack : TypeScript strict, tree-sitter WASM, Vitest

---

### [DDD (DigDigDig)](https://github.com/DNSZLSK/digdigdig) - DJ lossless toolkit

App desktop pour DJs : vérifie la qualité lossless par analyse spectrale FFT, scrape les tracklists de DJ sets YouTube (Content ID), acquiert via Soulseek avec vérification automatique.

- Scan bibliothèque : détecte les faux FLAC/WAV (upscaled MP3)
- Scraper DJ sets : YouTube Content ID + description + commentaires
- Pipeline : wishlist Bandcamp/Discogs → Soulseek → vérif spectrale → bibliothèque

Stack : Python, Flet, sldl, FFT/librosa

---

### [GitCoach](https://www.npmjs.com/package/gitcoach-cli) - CLI d'apprentissage Git

11e/400 au GitHub Copilot CLI Challenge. CLI TypeScript, 522 tests, i18n, 5 intégrations Copilot.

---

### Cherche

- **Alternance** 2 ans (sept. 2026) - Bretagne ou remote

---

<div align="center">

*"The code must flow."*

> Code écrit avec Claude (Anthropic). Architecture, méthodologie, tests et audits : moi.

![Visitors](https://komarev.com/ghpvc/?username=DNSZLSK&color=00ff00&style=flat-square)

</div>
