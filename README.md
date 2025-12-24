# Markdown to PDF for Braynr 🚀

Un'applicazione web leggera e veloce per convertire istantaneamente chat in Markdown (es. da Qwen o altri LLM) in documenti PDF pronti per lo studio avanzato su Braynr.

## 📖 Il Progetto

Questo tool nasce da un'esigenza reale durante il mio percorso di studi al 5° anno di Manutenzione Elettrotecnica.

Nella mia scuola non utilizziamo libri cartacei per scelta culturale e didattica. Per studiare, utilizzo l'intelligenza artificiale (specialmente Qwen) per generare fonti di studio personalizzate e approfondimenti tecnici. Tuttavia, per fissare i concetti, utilizzo Braynr, un software fondamentale per la lettura efficace e la creazione di mappe mentali.

## Il Problema

Prima di questo tool, il passaggio da una chat di IA a Braynr era lento e macchinoso:

1. Generazione del testo su Qwen.
2. Ricerca di un convertitore online.
3. Formattazione manuale.
4. Download e caricamento.

Questo processo richiedeva spesso più di 10 minuti per ogni singola sessione di studio.

## La Soluzione

Ho sviluppato questa webapp per abbattere i tempi di preparazione. Ora il flusso è immediato:  
**Copia la chat di Qwen ➜ Incolla nel tool ➜ Scarica il PDF ➜ Carica su Braynr.**

Grazie a questa automazione, posso dedicare più tempo alla lettura efficace e alle mappe mentali piuttosto che alla gestione dei file.

## ✨ Funzionalità

- **Editor Real-time**: Incolla il Markdown e vedi subito l'anteprima.
- **Rendering Fedele**: Supporto per tabelle, blocchi di codice, liste e formattazione avanzata.
- **Export PDF ad alta qualità**: Genera documenti A4 puliti e pronti per l'analisi.
- **Dark/Light Mode**: Per non affaticare la vista durante le sessioni notturne di studio.
- **Privacy Totale**: Il tool processa tutto lato client, nessun dato viene inviato a server esterni.

## 🛠️ Tecnologie Utilizzate

- **React**: Per la gestione dell'interfaccia utente.
- **Tailwind CSS**: Per un design moderno e responsive.
- **Marked & DOMPurify**: Per il parsing sicuro del Markdown.
- **html2pdf.js**: Per la generazione dei documenti PDF direttamente nel browser.

## 🚀 Come usarlo

1. Apri `index.html` in qualsiasi browser.
2. Incolla il testo Markdown nell'area di sinistra.
3. Clicca su **"Scarica PDF"**.
4. Importa il file su Braynr e inizia la tua sessione di lettura efficace.

## 👨‍💻 Autore

Sviluppato da uno studente di Manutenzione Elettrotecnica (5° anno) appassionato di automazione e metodi di studio efficaci.

> **Nota**: Questo progetto non è affiliato ufficialmente con Braynr o Qwen, è uno strumento indipendente creato per migliorare la produttività scolastica.
