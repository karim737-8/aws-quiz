WEB DISTRIBUTION INSTRUCTIONS
=============================

1. UPLOAD
   Upload the contents of this folder (`web_dist`) to a static hosting provider.
   
   Recommended Options:
   - GitHub Pages:
     1. Create a new repository on GitHub.
     2. Upload these files (`index.html`, `questions.json`).
     3. Go to Settings > Pages and enable it for the main branch.
   
   - Netlify / Vercel:
     1. Drag and drop this folder onto their deployment dashboard.

2. UPDATING QUESTIONS
   - The "Import PDF" feature DOES NOT work on the web version because it requires Python.
   - To update questions:
     1. Use the Desktop App on your PC to import a new PDF.
     2. This updates the `questions.json` file on your PC.
     3. Copy the updated `questions.json` to this folder.
     4. Re-upload `questions.json` to your hosting provider.

3. MOBILE USE
   - Once hosted, the website will work on any mobile browser.
   - The layout is responsive.
