# hackathon
Create the new generation Mixmo with fun

Mixmo is a quick letters game.
The letter tiles are all in the middle of the table face down.
Each player receives 6 letters.
At the signal, all players turn their tiles and try to make crosswords with them.
When a player has used all his letters he says Mixmo
Each player picks two more letters and the game goes on until the all face-down letters are used.

[Mixmo website](http://mixmo.fr/MIXMO-jeu-de-lettres.htm)

## Rules
1. branch per team (may have sub branches)
2. Easy setup (ex: docker-compose, install doc)

## Goal resolve as many as story as you can

[Todo list](https://waffle.io/jlboes/hackathon)

## Help

### Letters

120 letters


| a | b | c | d | e | f | g | h | i | j | k | l | m | o | p | q | r | s | t | u | v | w | x | y | z | wildcard | ganster |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | 2 | 3 | 4 | 17 | 2 | 3 | 3 | 9 | 2 | 1 | 3 | 7 | 7 | 3 | 2 | 6 | 7 | 7 | 6 | 3 | 1 | 1 | 1 | 1 | 2 |  1 |


wilcard = *

ganster = $

```
letterPool = "aaaaaaaaaa"
        +"bbcccdddd"+
        "eeeeeeeeeeeeeeeee"+
        "ffggghhhiiiiiiiii"+
        "jjkllllllmmmnnnnnnn"+
        "oooooooopppqqrrrrrr"+
        "ssssssstttttttuuuuuuvvv"+
        "wxyz**$";
```



#### Letters per player

| player | 2 | 3 | 4 | 5 | 6 |
| --- |--- |--- |--- |--- |--- |
|max letters on grid | 60 | 40 | 30 | 24 | 20 |


### Random Algorithm

### Dictionary

Dictionaries in the repo are available for word validation. There is a raw and a json format, you can chosse the one that fits the most for you.

