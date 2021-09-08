1.when click on hit 
    generate card
        create random value from 1 to 13
        map that ramdom value to the available cards 
        and this will generate any random card
    show card(two thing will be passed one is card, active player)
        check if the score < 21
            create image element 
            and setting the source of that element is what we passes in this funtion (so random card image is setted)
            setting this image in the appropriate div by using query selector and append child
            play the hit sound
    update score(two thing will be passed one is card, active player)
        check if card is A 
            if adding 11 keeps me below 21
                add 11
            else
                add 1
        Otherwise
            map card to cardmap and update scor of active player
    show score
        check if score > 21
            color will be red
            text should be 0
        Otherwise
            by using query selector and append child, set the text to score


2. when click on deal
    remove card of your side and dealer side
    set score of your side and dealer side to 0
    set text of your side and dealer side to 0
    set the color of your side text to white

