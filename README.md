## Aspect Prediction using seeds from the Oposum paper

- One ipynb uses the base bart model and other uses the one trained on cnn summarization dataset.


# Changes done. 
-- use the stemmed seeds. 
-- sample randomly 10 seeds.
-- use comma for the list of seed words. 
-- try different learning rates. 

I also plotted the training loss just to see if the model needs more training. By the 15th epoch, it seems like the training saturates.
- The performance of the model seems okay, but they still make a decent amount of mistakes while generating the aspect for the seed words. 
- I'll try them on some of the topic words from the open amzn dataset. 
