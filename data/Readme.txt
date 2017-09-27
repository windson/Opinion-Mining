*****************************************************************************
* Annotated by: Minqing Hu and Bing Liu, 2004.
*		Department of Computer Sicence
*               University of Illinois at Chicago              
*
* Contact: Bing Liu, liub@cs.uic.edu 
*          http://www.cs.uic.edu/~liub
*****************************************************************************

                            Readme file

This folder contains the following:

	1. CanonG3_tagged.txt: Contains tagged customer reviews of digital camera Canon G3
	2. CanonG3_untagged.txt: Contains untagged customer reviews of digital camera Canon G3. The tags are removed from the above file CanonG3_tagged.txt.
	   Only the title tag [t] is preserved so that you can find out the beginning of a review
	3. positive-words.txt: Contains a list of standard positive opinion words
	4. negative-words.txt: Contains a list of standard negative opinion words

All the reviews were from amazon.com. They were used in the following 
two papers:

Minqing Hu and Bing Liu. "Mining and summarizing customer reviews". 
   Proceedings of the ACM SIGKDD International Conference on 
   Knowledge Discovery & Data Mining (KDD-04), 2004.

Minqing Hu and Bing Liu. "Mining Opinion Features in Customer 
   Reviews." Proceedings of Nineteeth National Conference on 
   Artificial Intellgience (AAAI-2004), 2004.

Symbols used in the annotated reviews: 

  [t]: the title of the review: Each [t] tag starts a review. 
       We did not use the title information in our papers.
  xxxx[+|-n]: xxxx is a product feature. 
      [+n]: Positive opinion, n is the opinion strength: 3 strongest, 
            and 1 weakest. Note that the strength is quite subjective. 
            You may want ignore it, but only considering + and -
      [-n]: Negative opinion
  ##  : start of each sentence. Each line is a sentence. 
  [u] : feature not appeared in the sentence.
  [p] : feature not appeared in the sentence. Pronoun resolution is needed.
  [s] : suggestion or recommendation.
  [cc]: comparison with a competing product from a different brand.
  [cs]: comparison with a competing product from the same brand.

