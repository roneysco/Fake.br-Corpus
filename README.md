# Fake.Br Corpus
[![tag](https://i.imgur.com/ZhZ9Mw7.png)](http://nilc.icmc.usp.br/nilc/index.php)

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

or our paper published in Expert Systems with Applications:

``Silva, Renato M., Santos R.L.S, Almeida T.A, and Pardo T.A.S. (2020) "Towards Automatically Filtering Fake News in Portuguese." Expert Systems with Applications, vol 146, p. 113199.``

Bibtex:

	@InProceedings{fakebr:18,
	author={Monteiro, Rafael A. and Santos, Roney L. S. and Pardo, Thiago A. S. and de Almeida, Tiago A. and Ruiz, Evandro E. S. and Vale, Oto A.},
	title={Contributions to the Study of Fake News in Portuguese: New Corpus and Automatic Detection Results},
	booktitle={Computational Processing of the Portuguese Language},
	year={2018},
	publisher={Springer International Publishing},
	pages={324--334},
	isbn={978-3-319-99722-3},
	}
	
	@article{silva:20,
	title = "Towards automatically filtering fake news in Portuguese",
	journal = "Expert Systems with Applications",
	volume = "146",
	pages = "113199",
	year = "2020",
	issn = "0957-4174",
	doi = "https://doi.org/10.1016/j.eswa.2020.113199",
	url = "http://www.sciencedirect.com/science/article/pii/S0957417420300257",
	author = "Renato M. Silva and Roney L.S. Santos and Tiago A. Almeida and Thiago A.S. Pardo",
	}
	
	
