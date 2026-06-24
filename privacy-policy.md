# Privacy policy — Help Desk Segreteria KB Action

Questa Custom GPT Action usa GitHub API per leggere i file della Knowledge Base autorizzata Help Desk Segreteria dalla repository configurata e per creare issue strutturate di richiesta aggiornamento.

Dati trattati:
- richieste tecniche necessarie a recuperare file Markdown dalla repository;
- testo inserito dall'utente in una richiesta di aggiornamento KB, quando viene creata una GitHub Issue;
- token OAuth GitHub gestito da OpenAI/GitHub secondo le rispettive impostazioni;
- contenuto dei file KB autorizzati.

La Action non deve:
- leggere repository diverse da quella configurata;
- scrivere o modificare file della KB;
- creare pull request o commit;
- trattare credenziali, password o dati bancari in chiaro.

Gli utenti devono avere accesso GitHub alla repository privata per usare la Action in modalità OAuth.
