# fel: A Fine-grained Entity Linking vocabulary

Entity Linking (EL) is a task in Information Extraction that links the entity mentions in a text collection with their corresponding knowledge-base (KB) en- tries. With EL, we can take advantage of a large amount of information avail- able in publicly available KBs (e.g., Wikipedia, DBpedia, Wikidata) about real- world entities and their relationships to obtain semantic information that can be used to achieve a better understanding of text corpora. While the previous challenges for EL are well-known, another more fundamental issue is often overlooked by the community: the question of _what is an “entity”?_ Though several definitions have emerged about what an entity should be, there is, as of yet, no clear consensus.

This vocabulary is organized as a hierarchy, where the first level categories are: fel:BaseFormClass, fel:PartOfSpeechClass, fel:OverlapClass and fel:ReferenceClass. Each of them is a partition of the universe of mentions with the goal of seprate current entity definitions. Additionaly, we map other external resouces (in gray) related to which we are proposing, in order to avoid redundancy.


