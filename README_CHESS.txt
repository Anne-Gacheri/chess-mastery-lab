CHESS MASTERY LAB — GITHUB PAGES SETUP

1. Upload index.html and this README into the root of your GitHub repository.
2. Stockfish engine files are required beside index.html:
   - stockfish-19-lite-single.js
   - stockfish-19-lite-single.wasm
3. Download Stockfish.js 19.0.1 (GPL-3.0) from the official npm package:
   https://www.npmjs.com/package/stockfish
   The npm package contains the prebuilt lite single-threaded engine files in its bin directory.
   If downloading the package archive directly, use:
   https://registry.npmjs.org/stockfish/-/stockfish-19.0.1.tgz
   Extract the archive and locate the files named stockfish-19-lite-single.js and
   stockfish-19-lite-single.wasm. Upload BOTH to the repository root, alongside index.html.

4. In GitHub repository: Settings > Pages > Build and deployment > Deploy from a branch.
   Choose branch main and folder /(root), then Save.
5. Your site should appear at:
   https://anne-gacheri.github.io/chess-mastery-lab/

IMPORTANT:
- Stockfish worker JS and matching WASM must be in the SAME folder as index.html.
- This version uses chess.js from a CDN, so the page needs internet access to load chess rules.
- Stockfish 19 is GPL-3.0; retain license/source attribution if distributing the game.
