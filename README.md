# Meowldrin & Rensie — Link in bio

Piccola landing page mobile-first con link a **YouTube, Twitch e Instagram**. È un sito statico (HTML, CSS e JavaScript): niente backend, framework, tracker o servizi esterni per il rendering.

## File

- `index.html` — interfaccia responsive, illustrazione vettoriale del gatto astronauta e icone.
- `config.js` — link e testi da aggiornare.
- `.nojekyll` — evita la generazione Jekyll di GitHub Pages.

## Prima di pubblicare

Apri `config.js` e **verifica che i tre indirizzi siano corretti**, in particolare il canale YouTube `@MeowldrinITA`, il cui URL non è stato possibile confermare direttamente. Gli indirizzi Twitch e Instagram sono ricavati dai profili collegati alla precedente pagina Linktree di Meowldrin.

Se desideri promuovere un episodio specifico, cambia `featured.url` con il collegamento al video, poi modifica titolo e descrizione. Altrimenti il riquadro porta alla scheda dei video su YouTube.

## Pubblicazione con GitHub Pages

1. Su GitHub crea un **repository pubblico**, ad esempio `meowldrin-links`.
2. Carica **i singoli file** `index.html`, `config.js` e `.nojekyll` nella radice del repository (non caricare soltanto lo ZIP).
3. Nel repository vai in **Settings → Pages**.
4. In **Build and deployment → Source**, seleziona `Deploy from a branch`.
5. Scegli branch `main`, cartella `/(root)` e fai **Save**.
6. A pubblicazione completata, il sito sarà raggiungibile su `https://TUO-USERNAME.github.io/meowldrin-links/` (se il repository ha questo nome).
7. Metti quell'URL nel campo `Sito web` del profilo TikTok.

Per aggiornare i link, modifica `config.js` su GitHub: il sito verrà ripubblicato automaticamente.

Documentazione ufficiale: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Anteprima

Puoi aprire `index.html` direttamente con un browser per vedere il layout. Per verificare tutti i link ed evitare restrizioni locali tra file, puoi anche usare un server HTTP locale (per esempio `python -m http.server 8000`) nella cartella del progetto.

## Note

- L'illustrazione del gatto astronauta è un segnaposto vettoriale originale, sostituibile con il vostro avatar ufficiale.
- Non raccoglie dati personali né imposta cookie. I siti esterni seguono le proprie policy.
- La pagina non è ancora stata pubblicata sul tuo GitHub.
