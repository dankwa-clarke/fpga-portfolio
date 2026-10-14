# FPGA Engineering Portfolio

## Open in VS Code
1. Extract the ZIP and open the `fpga-portfolio-vscode` folder in VS Code.
2. Install Node.js LTS from https://nodejs.org/ if it isn't installed.
3. In the VS Code terminal run `npm install` then `npm run dev`.
4. Open the localhost URL displayed in the terminal.

## Manage content
- Edit `src/projects.js` to add, update, or remove projects.
- Edit the `profile` object at the top of `src/main.jsx` for your name, email, GitHub and LinkedIn.
- Edit `src/style.css` for colors, layout, and typography.
- Put photos in `public/` and set each project's `image` to e.g. `/orb-board.jpg`.
- Do not publish private code, unpublished research, or unverified performance claims.

## Publish
Push this folder to a GitHub repository, then import that repository into Vercel. Use the Vite framework preset; build command `npm run build`, output directory `dist`. Vercel can redeploy automatically when you push updates.
