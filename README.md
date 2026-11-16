# Hitendra B. Singh — Personal Branding Website

A responsive React + Vite executive portfolio website.

## Run locally
1. Install Node.js (LTS): https://nodejs.org/
2. Extract this ZIP and open a terminal in the project folder.
3. Run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL shown by Vite (usually http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```
The production site is generated in `dist/`.

## Customise your profile
Edit `src/data/profile.js`. Update your name, summary, social links, experience, projects, skills and education there.

## Add your photograph
Your supplied professional photograph is already included as `public/profile.jpg`. To replace it, overwrite that file with another image.

## Add your CV
Your supplied CV is already included as `public/Hitendra-Singh-CV.pdf` and linked from the Resume buttons. Replace this PDF when your CV is updated.

## Add or edit projects
Update the `projects` array in `src/data/profile.js`. Use verified outcomes only; replace the sample descriptions and placeholders with approved public information.

## Publish to GitHub
1. Create a new empty repository on GitHub.
2. In this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial personal branding website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

## Deploy on Vercel
1. Sign in at https://vercel.com/ and choose **Add New → Project**.
2. Import your GitHub repository.
3. Vercel should detect Vite automatically.
4. Keep Build Command as `npm run build` and Output Directory as `dist`.
5. Select **Deploy**. Future pushes to `main` will trigger deployments.

## Important before publishing
- Replace sample or indicative content with verified dates, outcomes and metrics.
- Add your actual LinkedIn URL, professional email, photograph and CV.
- The contact form is a front-end demo only. Connect Formspree, Web3Forms or your own backend before expecting submissions.
- Do not publish confidential government, client or project information without permission.
