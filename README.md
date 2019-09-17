# MLCPAI
(M)achine (L)earning (C)onversation in (P)ython (AI)

## Instructions
simply run main.py with python3 to begin

## words.txt
* there is words.txt with all of the english words to use with training.
* simply open the file
* run the program
* c+p all of the text in the file to the program and it will train

## example sqlite database
* There is an exmmple sqlite database if you want to just start talking to the bot at /EXAMPLE/mlcpai.sqlite & /EXAMPLE/mlcpai.sqlite.journal
* The sqlite database must be in the same dir as main.py!!!!

## A side note
the program will create an *.sqlite file in the cwd (current working directory). Please do not open or write to this file bc this will corrupt the training data. Also don't delete it unless you are completely sure that you want to delete all training progress.