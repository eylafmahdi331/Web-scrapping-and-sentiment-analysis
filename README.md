# Web-scrapping-and-sentiment-analysis for local and international views of the war in Sudan from YT
In this code, I used two ways of doing scrapping:
1- BeautifulSoup - used it for thehackernews website: one way I scrapped a punch of titles only and another way I scrapped all paragraphs from an article.
2- API: I scrapped YouType video for Vox titled "Sudan's conflict, explained", in this video international and local people express their views and sentiment towards the war between RSF and SAF. I scrapped for a sample of 300 comments.

For YT, I used twitter-RoBERTa base - even if it is fine tuned on twitter, the way people comment is the same so it was still suitable to use it for YT- and because it is not trained, the predictions seem to have high false positive after going over the sentiment prediction and comparing it with the actual sentiment in the sentences.
