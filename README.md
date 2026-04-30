# Git - Working with Remotes
- I repositoru remoti sono versione del tuo progetto che sono ospitate su Internet
- la collaborazione con altri programmatori implica la gestione di questi repository remoti e il push e il pull di dati

Fondamentale è saper **sincronizzare il nostro lavoro locale con un repository remoto.**

*comandi principali:*

`git remote -v` --> visualizza i server remoti collegati al nostro repository

## Aggiungere o rimuovoere un repository remoto
`git remote add <none>` <url>

## Caricare il lavoro locale sul repository remoto
`git push <remote> <ramo-locale>`

## Aggiornare la copia locale del repository, allineandola con la versione remota
`git pull <remote> <ramo-locale>`
