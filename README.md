Make bingo cards and call numbers for a virtual game night!

# bingocards
Generate bingo cards in R

This code generates classic numbered bingo cards, pulling random non-duplicate samples for each column and writes the cards out as jpeg files. The base of this code is creating a function called bingocards. After creating the function, you can enter the number of cards you want, and the output will be separate, uniquely generated jpeg files. For example, 
```{r}
bingocards(100) 
```
will generate and save 100 bingo cards. 

This function makes classic bingo cards; for text-based bingo game cards, check out: https://github.com/jennybc/bingo. 

# bingocalls
Generate bingo calls in R

This code generates bingo calls, pulling random non-duplicate samples from the possible numbers and adding the corresponding column letter. Output is a list of bingo numbers that you can read in order for players.

Happy bingo playing!!
