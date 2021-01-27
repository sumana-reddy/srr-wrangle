# srr-wrangle

## Tell us your assigned play.
My assigned play is "Antony and Cleopatra".

## Tell us your speaker 1.
- CHARMIAN

## Tell us your speaker 2.
- DOLABELLA

## Tell us the question you were asked.
- how many times did each of the two speakers speak?
- additional-top 20 words? (optional)

## List all commands used to answer the question. Final commands must be redirected to a file (or files).
1. (returns CHARMAIN word number of times that is there in the play)
- grep -i '^CHARMIAN' play.txt (OR)
- cat play.txt | grep -i 'CHARMIAN'

1. (returns DOLABELLA word number of times that is there in the play)

- grep -i '^DOLABELLA' play.txt (or)
- cat play.txt | grep -i 'Dolabella'

1. command to get the count of speaker 1 (CHARMIAN)
- $ cat play.txt | grep -i 'CHARMIAN' -c  (104)

1. command to get the count of speaker 2 (DOLABELLA)
- $ cat play.txt | grep -i 'Dolabella' -c  (37)

1. Command to save the count of speaker 1 in charmian.txt
- $ cat play.txt | grep -i 'CHARMIAN' > charmian.txt

1. Command to save the count of speaker 1 in dolabella.txt
- $ cat play.txt | grep -i 'DOLABELLA' > dolabella.txt

1. The sum of 2 speakers speak is 
- 104 + 37 = 141





