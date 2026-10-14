# AssistenzaBAT Remote

Client di assistenza remota di [AssistenzaBAT.it](https://assistenzabat.it), basato su
[RustDesk](https://github.com/rustdesk/rustdesk) 1.5.0 (licenza AGPL-3.0).

Modifiche rispetto a upstream, applicate in fase di build da
`.github/workflows/assistenzabat.yml`:

- nome applicazione e metadati dell'eseguibile;
- icone generate da `branding/icon.svg`;
- server ID/relay e chiave pubblica del server self-hosted AssistenzaBAT.

Nessuna altra modifica al codice. Il sorgente completo è questo repository.
Build: Actions → "AssistenzaBAT Windows" → Run workflow. Gli eseguibili sono nelle Releases.
