# Raging Fire Arena

Sito vetrina bilingue italiano/inglese con newsletter Brevo.

## File del sito

HTML, CSS e JavaScript si trovano nella cartella `public/`.

## Pubblicazione

Il branch `main` è collegato al Worker Cloudflare `polished-wind-f03c`, associato a ragingfirearena.com.
Ogni aggiornamento di `main` avvia la pubblicazione automatica tramite Cloudflare Workers Builds.

- Build command: vuoto
- Deploy command: `npx wrangler deploy`
- Root directory: `/`
- Configurazione: `wrangler.jsonc`

L'esito delle pubblicazioni è consultabile nel pannello Cloudflare del Worker.
