# Quanto Costa Band — Lokalni pregled v2

## Novine
- **Kontakt forma** šalje na **QuantoCostaBand@gmail.com** preko FormSubmit (radi na bilo kom hostingu). Ako pređeš na Netlify Forms, vrati prethodni atribut `data-netlify` i `action="/hvala.html"`.
- **Lokalni video**: `<video>` sa MP4 fajlovima u `assets/video/` (ubaci svoje `promo1.mp4`, `promo2.mp4`).
- **Kalendar raspoloživosti**: čita datume iz `data/booked.json` i obeležava rezervisano (X, crveno) vs. slobodno (zeleno).
- **Admin (offline)**: `admin.html` ti omogućava da dodaš/obrišeš datume i preuzmeš novi `booked.json` koji samo zamenis u `/data/` i redeploy.

## Kako da koristiš
1. Otvori `index-local.html` za lokalni pregled (forma vodi na `hvala.html`).  
2. U `assets/video/` postavi svoje MP4 fajlove i promeni nazive u `index.html` ako želiš drugo ime.  
3. U `admin.html` ažuriraj datume i preuzmi novi `booked.json`, zameni fajl u `/data/`.

## Napomena za pravi panel (onlajn)
Za pravo online uređivanje (upload slika/video i kalendara bez ručnog deploy-a) predlog je **Decap/Netlify CMS** (besplatno, /admin panel, media upload u repo) ili **Supabase/Firebase** (autentikacija + storage). Rado ću ti dati gotov config kada kažeš koji put biraš.
