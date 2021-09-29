# german-gpt2-romantik

The german-gpt2-romantik model was fine-tuned on dbmdz's german gpt-2 (https://huggingface.co/dbmdz/german-gpt2) for specialization in poetry generation tasks. The fine-tuned model can be found in this repository: https://huggingface.co/whher/german-gpt2-romantik.

## Training Data
The data for training were hand-chosen poems from the German Romanticism Era (German: Romantik). In total there were 2,641 pieces of poems and 879,427 tokens in the corpus.

## Poem Generation
The model can be directly called in Python using the Hugging Face's transformers. Enter a starting phrase or text, the model will output poem-like texts. You can try by entering "Der Garten der Freude", which outputs:

"Der Garten der Freude,

in dem mein Auge ruht,

wo Gott und die Sonne,

hier im Himmel,

zu allen Zeiten uns umgeben."
