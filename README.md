define El = Character ("Elizabeth", color="#00FF00")
define U = Character ("???", color="#00FF00")
define A = Character ("", color="40FFFF")
define U1 = Character ("???", color="#FFFFFF")

label start:
    #insert a black void, a slight pause with some faint ear ringing sound in the background
    "The darkness..."
    "The darkness...is scary"
    U "did...did it work?"
    "why am I scared of the dark?"
    "Because...Because..."
    "Because it makes me feel cold...immobile...As if I was dead"
    "the world around me...completely intangible to me... yet so near..."
    U "shit, it's not moving...I thought I did everything right..."
    U "Hey! can you hear me?"
    "I want to escape this darkness... I want to live!"
    U "Uh...what if I try... this!"
    A "*THUNK*"
    A "*THUD*"
    scene img1
    pause
    U1 "*Cough* *Cough* uuuugh..."
    show img2
    U "Great! So it did work! phew... I don't know what I would've done if it didn't."
    scene img1
    show img3
    U "Hey! can. you. understand. me?"
    $ Y = renpy.input("do. you. have. a. name?")
    if Y == "":
        $ Y = Character ("Homu",color="#FFFFFF")
        "I turn my head and try to speak...but nothing comes out of my mouth"
        U "well... at least you can hear me..."
        U "I'm going to call you.. Homu."
        U "Hey Homu! can. you. understand. me?"
        Y "uuugh...yes...."
    U "ok good, you can understand me...I think."
    U "can you get up?"
    Y "...give me...a minute"
    scene img1
    "it took me a few minutes to understand how to move my arms and legs. it was completely alien to me."
    "once I started to get used to moving my limbs, I tried to stand up."
    "..."
    "...I immediately fell down"
    "the girl gives a small smirk, however she quickly tries to hide it by covering her mouth."
    "I guess she didn't want me to feel bad."
    "eventually, with her help, I managed to get up and maintain some balance"
    show img4
    U "Hey, that ain't so bad. I'm really proud of you."
    scene img1
    show img5
    U "I thought this was going to take a couple of weeks, but if you're this much of a natural, then I guess we can go to the main course in no time!"
    return
