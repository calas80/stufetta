# Stufetta
Gestione domotica stufetta


<img width="347" alt="Schermata 2021-10-22 alle 15 14 28" src="https://user-images.githubusercontent.com/48358142/138459765-95619290-5032-43a6-aad2-e486c385b10e.png">

Nulla di complicato:

Con Input_boolean "Caldo Bagno" si attivano tutte le regole. Ogni regola può essere abilitata o disabilitata singolarmente.

All'orario prestabilito il termostato si imposterà su HEAT. 

Il comportamento è uguale a ogni climate: Se la temperatura di riferimento sarà più alta rispetto a quella ambientale, ovviamente la stufetta si accenderà.

Abbiamo la possibilità di impostare un orario per i giorni lavorativi e uno per i giorni feriali. Override ovviamente sovrascrive le precedenti (utile per quando avete bisogno di riscaldare l'ambiente ad un orario che non è il solito, senza per forza dover modificare l'orario solito). Quando è attivo override le schedulazioni feriale e lavorative vengono ignorate. Override si disattiva da solo ogni giorno, quindi non dovete ricordarvi di disabilitarlo quando non serve più. La voce "altro" è solo un’opzione in più.

Controllo dimenticanza serve a spegnere il termostato dopo un tempo prestabilito, che non è il tempo di funzionamento della stufetta ma il tempo di accensione del termostato. Serve ad esempio per non dimenticare il termostato acceso e lasciarlo lavorare tutta la notte. 

Nel package la stufetta può essere azionata anche da un tasto (xiaomi) che è ovviamente opzionale.

Per la card sono necessari i seguenti componenti custom installabili da hacs:
- stack-in-card
- fold-entity-row

# PER PIACERE NON MI CHIEDETE AIUTI SU COME FAR FUNZIONARE LE CARD SE USATE LA UI. 
Io scrivo le mie card in YAML. Non vi so aiutare se usate la UI, mai usata e mai la userò  ^_- 
