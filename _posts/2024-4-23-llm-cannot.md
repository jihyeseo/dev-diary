https://www.strangeloopcanon.com/p/what-can-llms-never-do?utm_source=tldrnewsletter

LLMs have a Reversal Curse.

If a model is trained on a sentence of the form "A is B", it will not automatically generalize to the reverse direction "B is A". 

The models, in other words, do not well generalise to understand the relationships between people. 

Inference is always a single pass. LLMs can't stop, gather world state, reason, revisit older answers or predict future answers, unless that process also is detailed in the training data.

This can be partially addressed through things like chain of thought or using other LLMs to review and correct the output, essentially finding ways to make the inference on track. 

Failure mode - Why can’t GPT learn Wordle?
This one is surprising. LLMs can’t do wordle. Or sudoku, or wordgrids, the simplest form of crosswords.
https://github.com/marquisdepolis/LOOP-Evals 
