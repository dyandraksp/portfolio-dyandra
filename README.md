# Dyandra Ayu Portfolio — deploy to Vercel

Static site (no build step). Files: index.html, img/, og.jpg, favicon.png, vercel.json.

## Deploy (Terminal, macOS)
1. Unzip, then: cd ~/Downloads/deploy
2. npx vercel --prod
   - First time: it asks you to log in (opens browser) → choose "Continue with GitHub/Google/Email".
   - "Set up and deploy?" → Y
   - "Which scope?" → your account
   - "Link to existing project?" → N
   - "Project name?" → dyandra-portfolio (or any name)
   - "In which directory is your code located?" → ./  (press Enter)
   - Framework → Other, no build command, output directory → ./ (accept defaults)
3. Vercel prints the live URL, e.g. https://dyandra-portfolio.vercel.app

## Update later
Replace files in this folder, then run `npx vercel --prod` again.
