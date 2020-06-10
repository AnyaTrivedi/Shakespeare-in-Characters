# Shakespeare-in-Characters
Using a Character Level RNN to generate Shakespearean text


This NLP project uses Standford's *Tiny Shakespeare* Dataset (shakespeare.txt) to generate Shakespearean Text using Character level RNNs. 

Why Character Level? Character level RNNS have the advantage of using less memory, while utilising subword information like morphemes, making them widely used in NLP taks for mobile applications.

Two RNN architectures are explored and compared:
* LSTM : More robust to highly dependent input and perform better as the complexity of the input increases
* GRU : Have less tensor operations than LSTMs, and so faster training times

The input to the model is a character, or a string of characters, which is used to generate text on a character by character basis.
