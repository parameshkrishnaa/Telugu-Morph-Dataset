# Telugu-Morph-Dataset
Telugu morph dataset with setence id, pos tag and morph features 
Number of sentences = 10000

### Link for Dataset
Click [here](https://github.com/parameshkrishnaa/Telugu-Morph-Dataset/10000-sentences.tsv) for dataset


## Examples
rAmuluku &lt;'rAmulu,n,any,sg,3,,ki,ki'&gt; 
vaNikipoyiMxi 	&lt;'vaNikipo,v,fn,sg,3,,A,A'&gt; 

### Explanation of fields in the angular bracket. 
**Each field is separated by comma**

### Field 1:	Root word		
### Field 2:	Lexical category		
#### Possible	Values: 	
		n	(Noun)
		pn	(Pronoun)
		v	(Verb)
		adv	(Adverb)
		adj	(Adjective)
		num	(Number Word)
		nst	(Nouns of Space and Time)
		avy	(Avyaya)
## Field 3:	Gender	(for verbs)	
#### Possible Values: 	
		m	(masculine)
		f	(feminine)
		n	(neutral)
		mf	(masculine+feminine)
		fn	(feminine+neutral)
		any	(any gender)
## Field 4:	Number	 	
#### Possible Values: 	
		sg	(singular)
		pl	(plural)
		any	(any number)
## Field 5:	Person		
#### Possible Values:	
		1	1st person
		2	2nd person
		3	3rd person
		any	any person
## Field 6	Case	(for nouns,pronouns)	
#### Possible Values:	
		d	Direct case
		o	Oblique case
			
			
## Field 7: 	Case marker if it is a noun		
#### Possible Values:	
		0	The Nominative case marker
		nu	The Accusative case marker
		wo	The Instrumental case marker/ Associative case marker
		ki	The Dative case marker
		nuMdi/nuMci/niMci	The Ablative case marker
		yoVkka	The Genitive case marker and etc..
		 			 	
###	TAM (Tense,Aspect,Mood) if it is a verb	 	
#### Possible Values:	
		A	The past tense marker
		wunn	The durative marker
		wA	The future marker
		a 	The negation marker
		adaM	The gerund marker
		we	The conditional marker
		inA	The concessive marker and etc..
## Field 8:	Suffix	 	 
#### Possible Values: "X" denotes any suffix
		X_A	question marker
		X_V	inclusive marker
		X_o	dubitative marker
		X_e	emphatic marker
