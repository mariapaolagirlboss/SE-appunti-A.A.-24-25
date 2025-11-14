Annotazioni, domande o punti da chiarire sul corso.

[[Corso Ingegneria del Software]]

**MODULO 1**

- Product backlog e sprint backlog? Quale è la differenza? Vi è una differenza? (Processo di sviluppo agili). risposta corretta: PO e team decidono cosa fare (sprint backlog) e come rivedere il product backlog (?). **Tale pianificazione ha per risultato la scelta di alcune user story del backlog di prodotto: tale scelta forma il backlog di sprint**. (possibile risposta?)

- Modelli di costo, problemi dei costi del software presenti in power point: Project management dei progetti software sono collegati soltanto ai punti funzione ? oppure no?

- Calcolo del fattore moltiplicativo

**MODULO 2**
**State diagrams**
- Differenza tra do ed entry. Quale delle due affermazioni è corretta? Sono entrambe corrette? 
	- affermazione 1: The difference is that the entry behavior is always run to completion, whereas the do behavior is only run to completion if no event triggers a transition.
	- affermazione 2: 
		- Entry = azione che viene eseguita **una sola volta** non appena si **entra** nello stato
		- Do = attività che viene eseguita **continuamente** (o periodicamente) **mentre** il sistema **rimane** nello stato.
	- Quindi sia Entry che Do possono essere sia attività che azioni ? Si capisce dal contesto? 
RICONTROLLA. Come scegliere tra azione e attività?
https://stackoverflow.com/questions/72385729/uml-state-diagram-difference-between-do-and-entry

- Quando avviene un evento in un determinato stato, il sistema controlla se la transizione può avvenire. In che senso? Tipo porta è già aperta (stato A), evento è aprire porta e verifica se è chiusa (guardia), la verifica fallisce quindi la porta rimane aperta?? 
	- Come verificare un evento?
	- Ognuna delle parti può essere omessa? Cosa si intende? Omessa nel diagramma?

- Synchronization Condition? Posta solo sui nodi join (non credo)? Permette al flusso di procedere?

- 
