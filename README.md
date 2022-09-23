## Clone
Clone with HTTPS:
```bash
git clone https://github.com/lacayodaniel/connect4.git
```
Clone with SSH:
```bash
git clone git@github.com:lacayodaniel/connect4.git
```

## Execution
There are several agents you may choose to play against. You can read more about how to activate these agents at the bottom of connect383.py.

A few commands to get playing quickly are:
```bash
python connect383.py h c 6 7 --depth=3
```
This will start a game with you vs the computer. The "--depth" flag is used to set the depth for the mini-max algorithm, as well as use my custom heuristic to choose the best leaf state. Try and beat the computer with this command! (read about the heuristic I made in heurstic.txt)

```bash
python connect383.py r h 4 4
```
This allows you to play against an agent which makes random moves on a 4x4 board. Note, score is calculated as the sum of squares for all streaks greater than two. Read more about scoring in Coding.pdf.





