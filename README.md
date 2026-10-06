# Autonomia_Teoria_Dallabrida_Samuele_4Bi.
Repository corso di autonomia teoria

## Appunti presi in classe

video sull'architettura trasformer RNN Reti neaurali ricorrrenti

##### Video funzionamento LLM:  
GPT: Generative Pretrainerd Trasformer  
Ogni neurone prede il suo valore di ingresso, moltiplica un altro fattore somma bias  
primo layer imput da tutti i neuroni d'ingresso.  
BIAS: sposta la soglia di attivazione  

Vogliamo che questi numeri siano normalizzati tra 0 e 1 (1 acceso - 0 spento)  
Con questo tipo di sistema era diffice fare il training della retre  
Traning cercare il minimi locali  
Sigmoide smooth per meccanismo + efficiente  

##### Tipi di somma:  
Lineari  
Esponenziali  
Derivate di fourier  

***RIGUARDARE I VIDEO VECCHI***  

Viene calcolato l'errore, la distanza tra la predizione ed il valore atteso  
Backpropagation ricalcola i pesi delle reti interne per minimizzare l'errore finale  
Il meccanismo migliore per poter addestrare una rete, vede essere svolta + e + volte  
Addestrare una rete neurale è molto più complessa che usarla  
Se la nostra rete neurale da errore, non usiamo questo errore per fare il training di una rete neurale  
Gli errori diventano materiale di addestramento per il modello successivo  
RAG: research augmented generation  
Generativa: perchè genera risposte testuali  
GEV modello AI che invece che generare testo ci da una predizione, un numero, ecc.  
  - Gli diciamo come deve caratterizzare l'output, es previsioni tempo risultato 30 %  
  - Sulla base dei dati che ho, la possibilità che un certo elemento si guasti.  
  - Dato un certo input quali elementi sono i quali categorie

##### Video:  
Come funziona l'architetture transformer che permette l'AI generativa.  
Differenza ai generativa vs ai generale.. ecc. -> (approfondimenti futuri che faremo in classe)


##### Tokenizer
Come una rete neurale interpreta e genera un testo:  
- Il pc nn ha nessuna coscienza di cosa sia un testo (numeri binari)  
- Pc testo = codifica  
- Come trattare numeri in campo di reti neurali  
  - trattare i singoli caratteri, completa ma nn compatta dei nostri testi  
  - Meccanismo di associare dei blocchi di testo, scomporre questi blocchi di testo in tutte le parole  
  - Blocchi di testo = TOKEN  
  - Tokenizer: Prende le stringhe di testo e le scompone in token, ogni modello ha il suo tokenizer
  - 










