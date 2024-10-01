1.Fare la spesa seguendo una lista
scrivere lista elements of list:
    for item in list:
        if item has coupon:
            take item and apply discount;
        else 
            take item;
    if rest money:
        take snack extra;

2.Aprire un pacchetto di figurine
apri pacchetto>controlla carta> se carta non in album: inserisci in album, altrimenti inserisci in mazzetto a parte.

3.Scegliere cosa guardare su Netflix
controlla quanto sonno/tempo hai: se hai <40min: guarda episodio di serie tv, altrimenti guarda un film.

4.Preparare le lasagne alla bolognese
leggi ricetta: segui ricetta passo per passo, avanza di un passo solo quando hai completato il passo in real life.

5. Comprare qualcosa su Amazon
if lamp is amazon prime:
    order lamp;
else if budget > 100$:
    take stilographic pen;
else take classic book;

6.Ordinare una pizza
controlla menu>scegli pizza>chiama cameriere>comunicagli la pizza>aspetta>quando arriva inizia a mangiare> se avanzi:chiedi cartone da portare via.

7.Scansionare un documento su più fogli fronte-retro
prendi foglio>portalo allo scanner>posalo>avvia macchina>quando finisce alza coperchio>gira foglio>avvia macchina>alza coperchio>togli foglio.

8.Contare i posti a tavola di 2 in 2
conta quante persone sono presenti>guarda inizio tavolo>prendi visualmente sedie in coppie di 2>avanza verso la fine del tavolo>finisci tavolo>controlla che totale sedie sia uguale al numero dei presenti, se numero sedie è inferiore calcola differenza e aggiungi sedie.

9.Caricare una foto su Instagram
scatta foto>controlla saturazione e vividezza, se inferiore ai tuoi standart di bellezza:aumenta saturazione e vividezza.

10. Attraversare la strada
stop on the cross line;
if light is green:
    walk;
else if light is yellow:
    walk*2;
else:
    wait 2sec;
    Attraversare la strada();

3. Gioco del blackjack
take 2 card, dealer reaveal 1 card and 1 remains hidden:

    if your points are >21:
        you lose;
    else:
        while is_takingcard:
            choice= do you want take another card?(y/n)
            if choice is "y":
                take another card;
            else:
                is_takingcard = False;
    
    dealer reveal the hidden card:
        while dealer_is_playing: 
            if points < 17:
                take another card:
                    if points >= 17 :
                        dealer_is_playing = False;
                        compare the points;
                        exit();

