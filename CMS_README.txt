NETLIFY CMS (Decap) — brzi vodič

1) Hostuj repo na GitHubu i poveži ga na Netlify (New site from Git).
2) U Netlify podešavanjima uključi:
   - Identity: Enable Identity
   - Registration: Invite only
   - Git Gateway: Enable Git Gateway
3) Dodaj svoj e‑mail u Identity → Invite user (prihvati poziv).
4) Otvori /admin na sajtu i uloguj se. Tu možeš:
   - Menjati /data/booked.json kroz UI (rezervisani datumi).
   - Uploadovati slike u assets/gallery (automatski WebP ako želiš promeni ekstenziju).
   - Uploadovati MP4 u assets/video (za velike fajlove razmotri Cloudflare Stream/Bunny).
5) Ako želiš da se promene odmah odraze na index.html, možemo dodati skriptu koja čita index_copy.json i renderuje delove stranice dinamički.
