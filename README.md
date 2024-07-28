Ciao ragazzi,
Esercizio di oggi: Vue Email List
nome repo: vue-email-list
Descrizione:
Attraverso l'apposita API di Boolean
https://flynn.boolean.careers/exercises/api/random/mail
generare 10 indirizzi email e stamparli in pagina all'interno di una lista.
Bonus
Far comparire gli indirizzi email solamente quando sono stati tutti generati.

soluzione

1.creo una funzione in cui itero 10 volte le mail generate da un api
2.creo una proprietà "email" a cui assegno un array vuoto
3.creo una lista nel dom in cui utilizzo la direttiva v-for per ciclare l'array
4.dentro la lista richiamo le email dentro l'array