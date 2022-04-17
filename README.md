# ISS-Project

# game design document

## Introduction
- Game Concept เป็นเกมPuzzle ที่เล่าเรื่องราวผ่านตัวละครเป็นมุมมองบุคคลที่1
- หมวดหมู่เกม Puzzle
- เนื้อเรื่อง 
- บรรยายกาศของเกม จะเป็นธีมอวกาศ

## Game Structure
- โหมดเกมที่ผู้เล่นสามารถเล่นได้ โหมดเนื้อเรื่องเท่านั้น
- Engagement เราผ่าน website
- การเล่น เป็นเกมเล่นคนเดียว
- วิธีการเล่น point and click แก้ Puzzle

## Graphics & Sound
- มุมมองของเกม เป็นบุคคลที่ 1
- สไตล์กราฟฟิก เป็นกราฟฟิกภาพวาด
- Animation อาจมีเล็กน้อย เช่นเดินทางเปลี่ยนโซน
- Music ถ้าใส่มาได้ก็จะมี
## Platform
- website

## Development System
- VScode

## Game play
- Character 
- Story 
- Objective 
- Core Game Mechanic 
- Level Design map 
- Progression 
- Game Flow 
- UI Flow

[Figma Mockup Design](https://www.figma.com/file/naEJtMEKg3ZsUoGjgdbYcC/ISS?node-id=0%3A1)

``` mermaid
flowchart TB
endgame(End Game)
startgame(Start Game) ---> gin(1 Gin)
gin-- choose A --> gina(eat A)
gin-- choose B --> ginb(eat B)
gin-- choose C --> ginc(eat C)
todlong(2 Tod Long)
gina ---> todlong
ginb ---> todlong
ginc ---> todlong
todlong -- choose A --> toda(Experiment A)
todlong -- choose B --> todb(Experiment B)
todlong -- choose C --> todc(Experiment C)
ork(3 Ork Kamlang Kay)
toda ---> ork
todb ---> ork
todc ---> ork
ork -- Choose A --> orka(Ork Kamlang Kay A)
ork -- Choose B --> orkb(Ork Kamlang Kay B)
ork -- Choose C --> orkc(Ork Kamlang Kay C)
orka ---> endgame
orkb ---> endgame
orkc ---> endgame
```
