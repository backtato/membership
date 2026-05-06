# Prompt per Codex

Agisci come Senior WordPress Plugin Architect e Security Auditor.

Analizza questo repository Membership Manager composto da tre plugin separati:

- `plugins/membership-manager-core`
- `plugins/membership-manager-passcreator`
- `plugins/membership-manager-woocommerce`

Obiettivo iniziale: controllo strutturale e compatibilità, senza modificare codice.

Vincoli:

- Non rifattorizzare.
- Non rinominare funzioni/classi/hook.
- Non cambiare la logica WooCommerce.
- Non cambiare la logica Passcreator.
- Non cancellare file.

Produci:

1. mappa dei plugin e delle dipendenze;
2. elenco dei punti critici pre-go-live;
3. controllo compatibilità WordPress/WooCommerce;
4. checklist di test manuali;
5. proposte di branch/PR ordinate per rischio.
