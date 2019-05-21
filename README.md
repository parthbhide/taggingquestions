
## Autonomous Tagging of Quora Questions

To automatically assigns tags for questions posted on a forum such as StackOverflow or Quora.

To automatically assigns tags for questions posted on a forum such as StackOverflow or Quora :
	
## What are tags :
		
		A Question can be clasified in to two ways for such forums :
			
			QUESTION 
				|__________> Category 
				|__________> Tags
			
			Here Tags, may be seen as a sub list of categories.

		
		For a clear vision lets take example :
		Question : What is the step by step guide to invest in share market in india?
			--> It may come under category like "share market", "investment"
			--> But it may have tags like "step by step guide","guide",'"india","market"
		Basically tags are to attract more corwd towards the problem so that it can be addressed in a broad way.

->> TAGS are something that are already available in the text itself and just need to explored with some processing.

->> While doing so i noticed that methods like LDA or NMF may not help you out here. ( Unsupervised Learning .. )

->> Using some basic NLP tweeks may give you a list of tags that can be suggested to users.

->> Not using any kind of ML algorithms here !

## References :
1.  https://spacy.io/usage/linguistic-features
2. https://spacy.io/usage/vectors-similarity

## Idea taken form : 

https://github.com/NirantK/awesome-project-ideas
