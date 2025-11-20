# Giochi\Fuga dal Grinch - Mercatino di Natale 3D 🎮 🇮🇹
https://federicoboccaccio.wordpress.com/

Ispirato da https://www.linkedin.com/posts/sara-buscemi-92b357139_gemini3pro-ai-gemini3pro-ugcPost-7397222432551387136-L4xz<br>
Usando lo stesso prompt.<br>
Solo che quando sono tornato su Linkedin per commentare il post ha deciso che era la mia volontà di caricare i nuovi post e ha cancellato il commento già scritto! Quanto è fatto male quel sito!

# Gioca
Non ho creare release, ma puoi scaricare il file o🌐 [Giocare on line](https://federicoboccacciopersonale.github.io/Giochi-Fuga-dal-Grinch/)

# Informazioni
Diversamente dagli altri miei progetti, questo è solo su GitHub.

# Problemi
* La grafica... se non sai che siete tu e il Grinch, non ci arriveresti mai
* Puoi trapassare gli oggetti, che mi ha fatto passare la voglia di migliorarlo
* Il mondo ha dimensioni finite, e una volta raggiunti i confini, puoi continuare ad andare oltre

E probabilmente altri

# 🎄 Fuga dal Grinch: Mercatino di Natale 3D

Un gioco arcade 3D festivo che gira direttamente nel tuo browser. Muoviti tra le bancarelle innevate, raccogli le decorazioni natalizie ed evita di farti catturare dal Grinch!

## 📖 Descrizione
Sei intrappolato in un mercatino di Natale generato proceduralmente. Il tuo obiettivo è salvare il Natale raccogliendo le palline decorative rosse sparse per la mappa. Ma fai attenzione: il Grinch è sulle tue tracce e diventerà sempre più veloce ogni volta che raccogli un oggetto!

## 🎮 Controlli
Il gioco supporta sia le frecce direzionali che i tasti WASD.

| Azione | Tasti (Frecce) | Tasti (WASD) |
| :--- | :---: | :---: |
| **Muovi Avanti** | ⬆️ Freccia Su | **W** |
| **Muovi Indietro** | ⬇️ Freccia Giù | **S** |
| **Gira a Sinistra** | ⬅️ Freccia SX | **A** |
| **Gira a Destra** | ➡️ Freccia DX | **D** |

## ✨ Caratteristiche Principali

* **Generazione Procedurale:** La posizione delle bancarelle e degli alberi cambia ogni volta che ricarichi la pagina, offrendo sempre un labirinto diverso.
* **Difficoltà Dinamica:** L'IA del Grinch (semplice inseguimento) aumenta la sua velocità di movimento progressivamente man mano che il tuo punteggio sale.
* **Atmosfera Invernale:**
    * Sistema particellare per la neve che cade.
    * Illuminazione dinamica con ombre proiettate (Shadow Mapping).
    * Nebbia (Fog) per creare profondità e atmosfera.
* **Interfaccia Utente (UI):** Punteggio in tempo reale e schermata di Game Over con pulsante di riavvio.

## 🛠 Tecnologie Utilizzate
* **HTML5 / CSS3:** Per la struttura e l'interfaccia utente in sovraimpressione.
* **JavaScript (ES6):** Logica di gioco.
* **Three.js:** Libreria WebGL per il rendering della grafica 3D, luci, ombre e geometrie.

## 🤖 Logica del Nemico (Il Grinch)
Il Grinch utilizza un algoritmo di inseguimento diretto:
1.  Calcola il vettore di distanza tra la sua posizione e quella del giocatore.
2.  Si muove costantemente verso il giocatore.
3.  Se la distanza è inferiore a una soglia di collisione (`1.2` unità), il gioco termina.

## 📝 Licenza
Progetto open source a scopo educativo. Sentiti libero di modificarlo e condividerlo! Buon Natale! 🎅

Mmm... forse dovrei leggere il codice generato.
