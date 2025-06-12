# La Blocklist Definitiva per AdGuard Home

Questa è una blocklist completa e "definitiva" per AdGuard Home, Pi-hole e altri sistemi di blocco DNS. L'obiettivo è fornire un unico punto di partenza per bloccare un'ampia gamma di minacce e contenuti indesiderati, unendo diverse fonti affidabili e specializzate.

## Categorie Bloccate

Questa blocklist unificata mira a bloccare le seguenti categorie:

-   **Pubblicità (Ads)**: Domini noti per servire annunci pubblicitari.
-   **Tracker e Telemetria**: Domini che tracciano l'attività degli utenti e raccolgono dati telemetrici.
-   **Malware e Ransomware**: Domini associati a software dannoso, inclusi ransomware e virus.
-   **Phishing e Truffe (Scam)**: Domini utilizzati per tentativi di phishing e altre truffe online.
-   **Contenuti per Adulti**: Domini che ospitano materiale pornografico e per adulti.
-   **Telemetria Smart Home e IoT**: Domini utilizzati da dispositivi come Amazon Alexa, Google Home, Smart TV (Samsung, LG, etc.) per inviare dati ai loro server, con l'obiettivo di preservare la funzionalità di base.

## Fonti Utilizzate

Questa lista è un'aggregazione di diverse fonti rinomate, tra cui:

-   **StevenBlack/hosts**: Una delle più note e utilizzate liste di base per il blocco di annunci e malware.
-   **The Firebog**: Una vasta collezione di blocklist suddivise per categorie (Malicious, Suspicious, Advertising, etc.).
-   **Liste specializzate per Phishing**: Come Phishing Army e malware-filter.
-   **Liste per la Privacy**: Come WindowsSpyBlocker per la telemetria di sistema.
-   **Liste per Smart TV e IoT**: Basate su raccolte della community come quella di hkamran80, per bloccare la telemetria di dispositivi connessi.

Tutte le fonti sono state combinate e de-duplicate per garantire efficienza e ridurre la ridondanza.

## Come Utilizzare

Copia il link del file `definitive_blocklist.txt` e aggiungilo come nuova "Blocklist" nelle impostazioni del tuo AdGuard Home o Pi-hole.

1.  Vai al pannello di controllo di AdGuard Home.
2.  Naviga in `Filtri` -> `Filtri DNS`.
3.  Clicca su `Aggiungi blocklist`.
4.  Inserisci un nome (es. "Lista Definitiva") e incolla l'URL del file raw di `definitive_blocklist.txt` che caricherai su GitHub.
5.  Salva e attendi che AdGuard Home aggiorni i filtri.

## Disclaimer

Questa è una lista di blocco molto aggressiva. Sebbene l'obiettivo sia mantenere la massima funzionalità possibile, alcuni siti o servizi potrebbero non funzionare correttamente. Se riscontri problemi, utilizza gli strumenti di log di AdGuard Home o Pi-hole per identificare i domini bloccati e aggiungerli alla tua "Allowlist" (lista dei permessi) se necessario. 