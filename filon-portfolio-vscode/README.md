# Filon Kabouridis — Portfolio (VS Code)

An independent, responsive implementation inspired by the **publicly visible structure and text** of https://filon-kabouridis-portfolio.lovable.app/.
This is **not** the original Lovable source code and its exact styling or interactive behavior has not been verified.

## Files
- `index.html`: All content and sections.
- `styles.css`: Layout, colors, typography and responsive styles.
- `script.js`: Updates the footer year.

## How to run
1. Unzip the project.
2. In Visual Studio Code choose **File → Open Folder** and open `filon-portfolio-vscode`.
3. Open `index.html` in a browser, or use the VS Code **Live Server** extension and click **Go Live**.

## Customize
- Your name, profile text, email and link URLs: `index.html`.
- Color palette: `:root` variables at the top of `styles.css`.
- The LinkedIn contact link displays “LinkedIn Contact via email” and currently points to the generic LinkedIn homepage. Replace its URL with your actual profile URL.
- The green “Contact via email” button opens Gmail Compose in a new tab, addressed to filonkab@gmail.com. The visitor may need to sign in to Gmail. Other email links use the default email app (`mailto:`).
- GitHub points to the profile listed publicly on the reference site.

No build process or Node.js required. Google Fonts are loaded online; fallback fonts work offline.
