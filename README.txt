*** Fake.Br Corpus ***

Hello! Thank you for using our corpus!

Here you may find 2 folders, with two versions of the same corpus:

	1) full_texts folder, which contains the full texts, as collected from their websites. Inside this folder, there are 4 more folders:

		- fake folder: it contains the collected fake news;
		- true folder: it contains the collected true news;
		- fake-meta-information folder: it contains the metadata information of each fake news;
		- true-meta-information folder: it contains the metadata information of each true news;

		The files in the fake and true metadata information folders follow the following model (line by line):

			<author>
			<link>
			<category>
			<date of publication>
			<number of tokens>
			<number of words without punctuation>
			<number of types>
			<number of links inside the news>
			<number of words in upper case>
			<number of verbs>
			<number of subjuntive and imperative verbs>
			<number of nouns>
			<number of adjectives>
			<number of adverbs>
			<number of modal verbs (mainly auxiliary verbs)>
			<number of singular first and second personal pronouns>
			<number of plural first personal pronouns>
			<pausality>
			<number of characters>
			<average sentence length>
			<average word length>
			<percentage of news with speeling errors>
			<emotiveness>
			<diversity>

		To find the aligned true and fake news pairs is very simple, as they are equally numbered/named inside their folders.

	2) size_normalized_texts folder, which contains the truncated texts, where, in each fake-true pair, the longer text is truncated (in number of words) to the size of the shorter text. This version of the corpus may be useful for avoiding bias in machine learning experiments.

Finally, if you use our corpus, please include a citation to our project website and the corresponding paper published in PROPOR 2018 conference.
