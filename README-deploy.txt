Spese vacanza live - istruzioni rapide

1. Apri travel-expense-split-live.html.
2. Cerca il blocco:
   const firebaseConfig = { ... }
   e sostituisci i valori REPLACE_ME con quelli del tuo progetto Firebase.

3. In Firebase:
   - crea un progetto
   - abilita Firestore Database
   - opzionale ma consigliato: Authentication anonima

4. Pubblica il file HTML su un hosting statico:
   - GitHub Pages
   - Netlify
   - Azure Static Web Apps

5. Apri il link dal telefono tuo e della tua compagna.
6. Inserite lo stesso ID viaggio, per esempio: sardegna-2026
7. Da quel momento vedrete le spese sincronizzate.

Nota importante:
- Il file è pronto come demo tecnica/funzionale.
- Prima dell'uso reale conviene aggiungere regole Firestore e, idealmente, autenticazione anonima.
- Se vuoi, il passo successivo è una versione con login leggero, edit delle spese e protezione del viaggio con codice condiviso.
