# Audio-signal-analysis-and-speech-recognition-PROJECT

è importante suddividere il problema in moduli chiari:
1. Riconoscimento della persona: Identifica chi sta parlando utilizzando un modello di riconoscimento vocale specifico per l'oratore.
2. Verifica della parola: Confronta la parola pronunciata (password) con quella assegnata all'oratore riconosciuto.
3. Verifica che la parola corretta sia stata pronunciata dalla persona corretta.
4. Decisione finale: Autorizza o nega l'accesso in base al risultato della validazione.

1. Modulo di acquisizione vocale: Registrare e preprocessare (filtrare e normalizzare) il segnale audio.
2. Modulo di identificazione del parlante (Speaker Recognition): Identificare chi sta parlando, ovvero
- Estrarre caratteristiche dal segnale vocale (ad esempio, MFCC, Mel-spectrogram).
- Classificare l'oratore usando un modello preaddestrato.
- Ritornare l'identità stimata.
3.  Modulo di riconoscimento vocale (Speech-to-Text): Trascrivere l'audio in testo.
4. Modulo di verifica della password: Verificare se la password pronunciata è corretta per l'oratore identificato.
- Ritornare un valore di validità (True/False).
5. Modulo di gestione degli accessi: Decidere se autorizzare o negare l'accesso.


