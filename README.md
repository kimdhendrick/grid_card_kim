grid_card
=========

Alfred workflow for reading your grid card

Download worflow now:
https://github.com/kimdbarnes/grid_card/blob/master/Grid%20Card.alfredworkflow?raw=true

To import into Alfred, download "Grid Card.alfredworkflow" and open, Alfred should import it.

Open the ruby script step and change the grid_card_values list to your values - make sure to convert your grid card properly.

e.g.:
grid_card_values = 
[
['1', '2', '3'],
['a', 'b', 'c']
]

Run alfred and type "grid <coord1> <coord2> <coord3>"

Possible improvements:
* Open grid card from a file
* Handle format directly as Iain sends it 
