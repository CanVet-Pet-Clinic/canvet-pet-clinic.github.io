# Canvet Veterinary Clinic website

The public website of Canvet Veterinary Clinic in Merkezefendi, Denizli.

**Live site:** <https://canvet-pet-clinic.github.io/>

## Pages

| Page | Turkish | English |
|---|---|---|
| Home | [`index.html`](index.html) | [`en/index.html`](en/index.html) |
| Privacy policy | [`privacy.html`](privacy.html) | [`en/privacy.html`](en/privacy.html) |

The site opens in Turkish; the button at the top right switches to English.

The home page also describes CanVet, the clinic's own desktop program. The
privacy policy explains how CanVet uses Google Drive for the clinic's encrypted
backups. Google shows both addresses on its consent screen, so they must keep
working: if either one moves, update it in Google Auth Platform → Branding too.

## How it works

Plain HTML and CSS with no build step, published by GitHub Pages from the root
of the `main` branch. Every push to `main` goes live within a minute or two.

To preview it locally:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Before publishing

- Change the Turkish and English pages together.
- Do not add customer faces, records, prescriptions or anything else from the
  clinic's data. This repository and the site are public.

## Credits

Set in [Plus Jakarta Sans](https://github.com/tokotype/PlusJakartaSans), under
the SIL Open Font License ([`fonts/OFL.txt`](fonts/OFL.txt)).
