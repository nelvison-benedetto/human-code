1.Fare la spesa seguendo una lista
scrivere lista elements of list:
    for item in list:
        if item has coupon:
            take item and apply discount;
        else 
            take item;
    if rest money:
        take snack extra;


2. Comprare qualcosa su Amazon
if lamp is amazon prime:
    order lamp;
else if budget > 100$:
    take stilographic pen;
else take classic book;

3. Attraversare la strada
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

