# Mansoor Protocol — Launcher

A tiny static page that copies the **current Mansoor Protocol activation script** and links you to ChatGPT/Claude.

- **Copy Script** button fetches live text from the GitHub Gist (source of truth).
- **Open ChatGPT / Open Claude** buttons to start a new chat and paste.
- Optional **bookmarklet** to auto-insert the script into a new chat with one click.

**Live Script (Gist):** https://gist.githubusercontent.com/Mansoor-Protocol/9ac9c9fb9f0194b62acf486b467e44bf/raw/mansoor-protocol-activation.txt

## How to update the script
Edit the Gist above (keep the same filename). The launcher always pulls the latest automatically.

## Local development
Just open `index.html` in your browser.

## License

- **Protocol text (activation script itself):** Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) via the [Zenodo record](https://doi.org/10.5281/zenodo.13315794).  
  This covers the words of the protocol and related explanatory materials. Use, adapt, and share with attribution, **non-commercial only**, and under the same license.

- **Launcher code (this repository):** Licensed under the MIT License (see LICENSE file).  
  This covers the HTML/JavaScript for the copy button and bookmarklet. It is permissive and may be reused in other projects.

By separating these two, the **protocol** remains under its Creative Commons license, while the **code** here is open for developers to reuse freely.
