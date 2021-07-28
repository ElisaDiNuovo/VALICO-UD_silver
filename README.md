# VALICO-UD_silver

Automatically annotated learner Italian treebank. VALICO-UD gold is manually corrected and error annotated and is available in the UD repository (https://github.com/UniversalDependencies/UD_Italian-Valico).

The texts are automatically annotated using UDPipe (https://ufal.mff.cuni.cz/udpipe/2).

VALICO-UD_silver_LS.conllu contains 1,836 Learner Sentences (LS) corresponding to 201 texts, written by German, English, Spanish, and French native speakers learning Italian as L2.

VALICO-UD_silver_TH.conllu contains a Target Hypothesis (TH), i.e., a grammatically corrected version, of the 1,836 LS.

Together with the CoNLL-U files, two txt files are uploaded containing sentence id and sentence text separated by an hash symbol.

Each line in the txt files begins with an id structured as a-bb_xx-c, where:

	a is the number of the text (from 1 to 201);

	bb is the number of the sentence in the text;

	xx is the ISO code for the learner's native language (i.e., de for German, en for English, es for Spanish, and fr for French);

	c is the learner's year of study of Italian (5 indicates more than 4 years, x indicates unknown).

For example:

1-01_fr-3 indicates the 1st sentence of the 1st text of the treebank which is written by a French learner at their 3rd year of study; and

35-27_en-1 indicates the 27th sentence of the 35th text of the treebank which is written by a English learner at their 1st year of study.
