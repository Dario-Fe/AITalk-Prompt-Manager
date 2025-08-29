# AI Talk - Gestore di Prompt

Un'applicazione semplice ed elegante per gestire e organizzare i tuoi prompt per l'IA. Questo strumento ti aiuta a creare, modificare e classificare i tuoi prompt in cartelle per un facile accesso e una maggiore produttività quando lavori con modelli di intelligenza artificiale.

## Funzionalità

- **Gestione Cartelle:** Crea, rinomina ed elimina cartelle per classificare i tuoi prompt.
- **Gestione Prompt:** Aggiungi nuovi prompt con un titolo e un contenuto a qualsiasi cartella. Modifica o elimina i prompt esistenti.
- **Accesso Rapido:** Visualizza rapidamente tutti i prompt all'interno di una cartella.
- **Design Responsivo:** Un'interfaccia utente pulita e moderna che funziona su schermi di tutte le dimensioni.
- **Tema Chiaro e Scuro:** L'interfaccia supporta sia il tema chiaro che quello scuro.

## Stack Tecnologico

Questo progetto è costruito con uno stack frontend moderno:

- **[Vite](https://vitejs.dev/):** Un tool per il frontend di nuova generazione che offre un'esperienza di sviluppo più rapida e snella.
- **[React](https://react.dev/):** Una libreria JavaScript per la costruzione di interfacce utente.
- **[TypeScript](https://www.typescriptlang.org/):** Un superset tipizzato di JavaScript che compila in JavaScript puro.
- **[Tailwind CSS](https://tailwindcss.com/):** Un framework CSS utility-first per uno sviluppo rapido dell'interfaccia utente.
- **[shadcn/ui](https://ui.shadcn.com/):** Una collezione di componenti riutilizzabili costruiti usando Radix UI e Tailwind CSS.

## Come Iniziare

Per ottenere una copia locale funzionante, segui questi semplici passaggi.

### Prerequisiti

È necessario avere installato [Node.js](https://nodejs.org/) (versione 18 o superiore consigliata) e un gestore di pacchetti come `npm` or `bun`. Questa guida utilizzerà `bun`.

### Installazione

1.  **Clona il repository:**
    ```sh
    git clone https://github.com/Dario-Fe/AITalk-Prompt-Manager.git
    ```

2.  **Naviga nella directory del progetto:**
    ```sh
    cd AITalk-Prompt-Manager
    ```

3.  **Installa le dipendenze:**
    ```sh
    bun install
    ```

### Eseguire l'Applicazione

Per avviare il server di sviluppo locale, esegui il seguente comando:

```sh
bun run dev
```

L'applicazione sarà disponibile all'indirizzo `http://localhost:8080` (o un'altra porta se la 8080 è già in uso).

## Script Disponibili

Nella directory del progetto, puoi eseguire:

- `bun run dev`: Esegue l'app in modalità sviluppo.
- `bun run build`: Costruisce l'app per la produzione nella cartella `dist`.
- `bun run lint`: Analizza il codice alla ricerca di potenziali errori e problemi di stile.
- `bun run preview`: Avvia un server locale con la build di produzione per un'anteprima.
