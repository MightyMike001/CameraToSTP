Deploy-instructies (Netlify Drop of GitHub Pages)

1) Netlify Drop (snelste manier, HTTPS):
   - Ga naar https://app.netlify.com/drop
   - Sleep deze zip of de map met 'index.html' erin naar het venster
   - Je krijgt direct een https://...netlify.app link
   - Open die link in Safari op iPhone

2) GitHub Pages:
   - Nieuwe repo aanmaken
   - Upload 'index.html' naar de root
   - Settings → Pages → Deploy from branch (main)
   - Open https://<jouwnaam>.github.io/

iPhone tips:
- Open altijd via HTTPS (geen file://).
- In iOS Instellingen → Safari → Geavanceerd → Website-instellingen → Camera: Toestaan.
- Als video zwart blijft: druk op 'Herstart camera' op de pagina.
- Als randen niet werken: 'Herlaad OpenCV' (cache-buster).
