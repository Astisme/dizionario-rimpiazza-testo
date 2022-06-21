# dizionario-rimpiazza-testo
Per iniziare, scarica lo zip **lista.zip** contenente la lista di sostituzioni e decomprimilo.

Visita [la wiki](https://github.com/Astisme/dizionario-rimpiazza-testo/wiki) per scoprire come utilizzare il file scaricato.

# A cosa serve?
Abbiamo creato delle coppie [parola da scrivere - parola da rimpiazzare] che ti permetteranno di utilizzare una tastiera senza accenti e di aggiungere automaticamente gli accenti.
In questo modo non è necessario imparare i comandi della tastiera internazionale o cercare online _"e accentata"_.

# Come funziona?
Le sostituzioni seguono un pattern così definito:
<table>
  <thead>
    <th>Parola scritta</th>
    <th>Parola rimpiazzata</th>
    <th>Regola</th>
  </thead>
  <tbody>
    <tr>
      <td>Partiro</td>
      <td>Partirò</td>
      <td>Se la parola scritta non ha significato, viene rimpiazzata con la parola accentata</td>
    </tr>
    <tr>
      <td>Velocita</td>
      <td>Velocità</td>
      <td>Ulteriore esempio</td>
    </tr>
    <tr>
      <td><del>Necessita</del><br />Necessitaa</td>
      <td>Necessità</td>
      <td>Se la parola scritta ha significato, è necessario raddoppiare la vocale finale</td>
    </tr>
    <tr>
      <td><del>Abbandono</del><br />Abbandonoo</td>
      <td>Abbandonò</td>
      <td>Ulteriore esempio</td>
    </tr>
    <tr>
      <td>cosee</td>
      <td>cos'è</td>
      <td>La regola precedente viene anche usata per costrutti più complessi</td>
    </tr>
    <tr>
      <td>ee</td>
      <td>è</td>
      <td>e per le lettere accentate</td>
    </tr>
    <tr>
      <td>cee</td>
      <td>c'è</td>
      <td>Ulteriore esempio</td>
    </tr>
    <tr>
      <td>dx</td>
      <td>Destra</td>
      <td>Sono incluse anche le abbreviazioni comuni</td>
    </tr>
    <tr>
      <td>sx</td>
      <td>Sinistra</td>
      <td>Ulteriore esempio</td>
    </tr>
  </tbody>
</table>

# Come posso contribuire?
Il file viene aggiornato ogni volta che una nuova coppia viene aggiunta. [Qui sopra](https://github.com/Astisme/dizionario-rimpiazza-testo/tree/main/lista-alfabetica) puoi trovare le coppie già incluse, divise alfabeticamente.

Consulta il dizionario e aggiungi altre coppie seguendo le regole illustrate tramite una Pull Request.

# Quali sono gli sviluppi progettati?
- Ampliamento del dizionario
- Creazione di un dizionario dei simboli
  - esempio (già incluso): tilde - ~
- Espansione del dizionario ad altre lingue
