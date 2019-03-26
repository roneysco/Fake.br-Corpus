# Fake.Br Corpus
[![tag](http://oi65.tinypic.com/jjbiht.jpg)](http://nilc.icmc.usp.br/nilc/index.php)

Hello! Thank you for using our corpus!

Here you may find 2 folders, with two versions of the same corpus:

 - ``full_texts`` folder, which contains the full texts, as collected from their websites. Inside this folder, there are 4 more folders:

   - ``fake`` folder: it contains the collected fake news;
   - ``true`` folder: it contains the collected true news;
   - ``fake-meta-information`` folder: it contains the metadata information of each fake news;
   - ``true-meta-information`` folder: it contains the metadata information of each true news;

   The files in the fake and true metadata information folders follow the following model (line by line):

		author
		link
		category
		date of publication
		number of tokens
		number of words without punctuation
		number of types
		number of links inside the news
		number of words in upper case
		number of verbs
		number of subjuntive and imperative verbs
		number of nouns
		number of adjectives
		number of adverbs
		number of modal verbs (mainly auxiliary verbs)
		number of singular first and second personal pronouns
		number of plural first personal pronouns
		number of pronouns
		pausality
		number of characters
		average sentence length
		average word length
		percentage of news with speeling errors
		emotiveness
		diversity

   To find the aligned true and fake news pairs is very simple, as they are equally numbered/named inside their folders.

 - ``size_normalized_texts`` folder, which contains the truncated texts, where, in each fake-true pair, the longer text is truncated (in number of words) to the size of the shorter text. This version of the corpus may be useful for avoiding bias in machine learning experiments.

Finally, if you use our corpus, please include a citation to our project website and the corresponding paper published in PROPOR 2018 conference:

``Monteiro R.A., Santos R.L.S., Pardo T.A.S., de Almeida T.A., Ruiz E.E.S., Vale O.A. (2018) Contributions to the Study of Fake News in Portuguese: New Corpus and Automatic Detection Results. In: Villavicencio A. et al. (eds) Computational Processing of the Portuguese Language. PROPOR 2018. Lecture Notes in Computer Science, vol 11122. Springer, Cham``

Bibtex:

	@InProceedings{fakebr:18,
	author={Monteiro, Rafael A. and Santos, Roney L. S. and Pardo, Thiago A. S. and de Almeida, Tiago A. and Ruiz, Evandro E. S. and Vale, Oto A.},
	title={Contributions to the Study of Fake News in Portuguese: New Corpus and Automatic Detection Results},
	booktitle={Computational Processing of the Portuguese Language},
	year={2018},
	publisher={Springer International Publishing},
	pages={324--334},
	abstract={Fake news are a problem of our time. They may influence a large number of people on a wide range of subjects, from politics to health. Although they have always existed, the volume of fake news has recently increased due to the soaring number of users of social networks and instant messengers. These news may cause direct losses to people and corporations, as fake news may include defamation of people, products and companies. Moreover, the scarcity of labeled datasets, mainly in Portuguese, prevents training classifiers to automatically filter such documents. In this paper, we investigate the issue for the Portuguese language. Inspired by previous initiatives for other languages, we introduce the first reference corpus in this area for Portuguese, composed of aligned true and fake news, which we analyze to uncover some of their linguistic characteristics. Then, using machine learning techniques, we run some automatic detection methods in this corpus, showing that good results may be achieved.},
	isbn={978-3-319-99722-3},
	}
	
	
