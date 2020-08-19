###################HackUPC2019###############################
Title: Dope Rhyme Spitting AI 
A Bot which learned to rap, rap back and to call you and rap in your face.

Members:

1-	Meysam Zamani Forooshani
2-	Samuel Muñoz Ortega
3-	Luca venier
4-	Billel Beboudjit


###Description:

## Inspiration
A previous study on website of one of our team members (https://smunoz.dev/) inspired him to make:
* A rapping bot to answer the rhymes of the user with structure, semantics, and rhyme.
* Complete rewrite of my Word2Vec study with an existing dataset, on spanish rap music.
* Another Word2Vec implementation with 55k english music lyrics.

## What it does
Bot answers to your phrases over:
Web app using voice recognition, answers with text, user can leave ratings. (vue_frontend)
User writes on console, gets an answer over the phone with TTS. (markov/run_twilio)
User writes on console and gets an answer back over text in the console. (markov/run.py)

## What it doesn't do
We trained some markov models, and Word2vec, but we weren't able to combine them because markov
has no memory of previous states of large scope. At least it finds rhymes. 
We downloaded a pre trained GPT-2 model to plug it into a twitter bot, but we wanted to train 
it with a bigger dataset, but we had no time.

