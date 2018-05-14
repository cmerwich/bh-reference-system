# Biblical Hebrew Reference Features

The first notebook exports five new features that enable a student of Biblical Hebrew (BH) to study its reference system. BH, like other languages, makes use of all kinds of features within the language to establish text-coherence and to ensure that the reader or listener understands to whom or what is being referred to. These BH features are, including their Person, Gender and Number (PGN) properties (if existent): 

* Personal pronouns, `prps`; 
* Demonstrative pronouns, `prde`; 
* The `verb` and its suffix `prs` (if the verb has one); 
* The suffix `prs` of a word; 
* `Nouns` that can function as pronouns. I leave these out of consideration, for now. 

Within Text Fabric (see: [BHSA](https://github.com/ETCBC/bhsa)), the dataset this notebook makes use of, named features are already available. 

All kinds of information from Text Fabric need to be combined however to extract PGN information. The new features (`pgn_prde`, `pgn_prps`, `pgn_prs`, `pgn_verb`, and `pgn_verb_prs` (i.e. verb+suffix) offer a shortcut to doing all this administration. 

The second notebook demonstrates what can be done with the five new features: counting, filtering, visualisation. 