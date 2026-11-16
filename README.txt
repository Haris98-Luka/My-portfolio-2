VERCEL PAR DEPLOY KARNE KE STEPS
=================================
Is folder ki sari files (index.html, manifest.webmanifest, sw.js, vercel.json, icons/)
project ke ROOT mein honi chahiye. Koi build ya framework ki zaroorat nahi.

TAREEQA A - GitHub ke zariye (browser se)
1. github.com par naya repository banayein (jaise: haris-portfolio).
2. "Add file" > "Upload files" mein is folder ki SARI files aur icons folder drag karein. Commit karein.
3. vercel.com par login karein > "Add New" > "Project" > apna repo "Import" karein.
4. Framework Preset: "Other". Build Command aur Output Directory khali chorein. "Deploy" dabayein.
5. Link milega, jaise https://haris-portfolio.vercel.app

TAREEQA B - Vercel CLI (PC par, Node.js chahiye)
1. Is folder mein terminal kholein.
2. npx vercel
3. Sawalon ke jawab dein, aakhir mein "npx vercel --prod"

APP KI TARAH INSTALL KARNA
- Android Chrome: link kholein > menu (3 dots) > "Install app" ya "Add to Home screen".
  Page ke upar "Install app" button bhi aa sakta hai.
- iPhone Safari: Share > "Add to Home Screen".
- PC Chrome: address bar mein install icon.
Icon par "HARIS" likha nazar aayega, aur app full-screen khulegi.

APK CHAHIYE TO
Vercel link ko https://www.pwabuilder.com par daal kar Android package bana sakte hain.
