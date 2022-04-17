# ISS-Project

``` mermaid
flowchart TB
endgame(End Game)
startgame(Start Game) ---> gin(Gin)
gin-- choose A --> gina(eat A)
gin-- choose B --> ginb(eat B)
gin-- choose C --> ginc(eat C)
todlong(Tod Long)
gina ---> todlong
ginb ---> todlong
ginc ---> todlong
todlong -- choose A --> toda(Experiment A)
todlong -- choose B --> todb(Experiment B)
todlong -- choose C --> todc(Experiment C)
ork(Ork Kamlang Kay)
toda ---> ork
todb ---> ork
todc ---> ork
ork -- Choose A --> orka(Ork Kamlang Kay A)
ork -- Choose B --> orkb(Ork Kamlang Kay B)
ork -- Choose C --> orkc(Ork Kamlang Kay C)
orka ---> endgame
orkb ---> endgame
orkc ---> endgame
orkc ---> YEET
```
