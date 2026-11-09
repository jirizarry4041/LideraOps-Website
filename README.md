# Lidera Operations Advisory

Static bilingual website for Lidera Operations Advisory, founded by Joel Irizarry.

## Files

- `dist/index.html` / `dist/es.html`: English and Spanish homepages.
- `dist/services.html` / `dist/servicios.html`: Services.
- `dist/case-studies.html` / `dist/casos-de-estudio.html`: Case studies from Joel’s prior leadership experience.
- `dist/perspectives.html` / `dist/perspectivas.html`: Selected publications, kept in English on both versions.
- `dist/style.css`: shared styles.
- `dist/img/`: logo and photographs.

## Preview

Run `python3 -m http.server 8000 --directory dist` and open http://localhost:8000.

No installation or build step is required.

## Hosting

Production hosting is on Netlify for LideraOps.com. Use branch `main`, publish directory `dist`, and no build command. If continuous deployment is enabled, pushes to main trigger publication.

The ChatGPT Sites version is maintained separately; changes do not automatically synchronize between Sites and this repository.

The contact form remains a draft and does not send submissions. Until activated and tested, visitors are directed to LinkedIn.

Synced from Sites source revision `211b650cd3913a1e599d82ed2969b2dc219e90e1` on November 9, 2026.
