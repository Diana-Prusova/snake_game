
# Snake game

Verze Snake game naprogramovananá pomocí Turtle graphics. Účel hry pro mě byl především v tom, abych se seznámila s problematikou objektově orientovaného programování. 


## Před spuštěním
Hra využívá baliček Tkinter, který by měl být na Windows součástí zakladního balíčku. Na LINUX UBUNTU jsem jej ale musela doinstalovat tímto příkazem:

    sudo apt install python3-tk


## Pravidla hry
Hra samotná je nastavená tak, jak ji všichni známe. Had prochází polem a jí náhodně generovanou potravu, což prodlužuje jeho délku. Zároveň nesmí narazit do hrany hracího pole ani do svého těla. Hra je rozdělená do levlů a je nastavena konečně - je možné dojít do bodu vítězství.

Hra se ovládá klávesami: 

    a = doleva 
    w = nahoru
    d = doprava
    s = dolů

Levely hry:
- LVL 1: do 10 ks snědené potravy. Rychlost hada je 0.3 s.
- LVL 2: do 20 ks snědené potravy. Rychlost hada je 0.2 s.
- LVL 3: do 30 ks snědené potravy. Rychlost hada je 0.1 s. 
- LVL FINÁLE: do 39 ks snědené potravy. Rychlost hada je 0.05 s.
- Pokud hráč zvládne s hadem sníst 40 ks snědené potravy, tak VÝHRAL. 
