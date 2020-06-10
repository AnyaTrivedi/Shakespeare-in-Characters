# Shakespeare-in-Characters
Using a Character Level RNN to generate Shakespearean text


This NLP project uses Standford's *Tiny Shakespeare* Dataset (shakespeare.txt) to generate Shakespearean Text using Character level RNNs. LSTM and GRU based architectures are explored and compared.

Why Character Level? Character level RNNS have the advantage of using less memory, while utilising subword information like morphemes, making them widely used in NLP taks for mobile applications.

The input to the model is a character, or a string of characters, which is used to generate text on a character by character basis.
