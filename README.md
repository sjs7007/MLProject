# MLProject

1. Remove random choice. 
2. Sentences capped to length 7.
3. Use stop symbols to make all sentences of length 7.
4. Change sequence length to 7. 
5. feed sentence by sentence(window 7 , stride 7)


sentences in list -> remove punctuation -> pad in front with 1 "<" -> pad at end with ">" as many needed to make it 7.
