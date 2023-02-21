# shakespeare

This is AI that generates Shakespeare alike text.

**DISCLAIMER:** Don't run this script on CPU. If you want you need to decrease n_embd=64, n_head=4, n_layer=4, block_size=32, batch_size=16, eval_interval=500, dropout=0.0 and learning_rate=1e-3.
This AI is based on "Attention is all you need" research paper (also ChatGPT is based on it).

AI is using **self-attention**, mechanism for connecting different positions in a single sequence to construct a representation of the sequence.

More about this you have on my website.[HERE](https://youshitsune.me/2023/02/attention-is-all-you-need/)
