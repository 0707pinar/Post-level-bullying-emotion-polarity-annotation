# Post-level-bullying-emotion-polarity-annotation
Annotations of Instagram Posts with Emotion, Polarity and Bullying Labels. This annotation has been used as a part of our research to be presented in [ACM SAC 2019](https://www.sigapp.org/sac/sac2019/) (the 34th ACM/SIGAPP Symposium On Applied Computing).

# Dataset:
A portion of Instagram dataset[1,2] was used. This dataset needs to be requested from one of the authors[1,2] due to the licence agreement. We randomly selected 10 media sessions (i.e., 5 bullying sessions and 5 no bullying sessions) from the Instagram dataset. A media session was the thread of comments (i.e., Instagram posts) following a picture. From 10 Instagram sessions, 1000 Instagram comments were annotated with emotion, polarity and bullying labels upon removing the "empty" labels in the given "clmn" fields.

# Annotations:
The annotations we provided here were post level, meaning each Instagram post was annotated with the three labels. Our annotation txt file contains the following columns:
* unit_id:  This shows the corresponding Instagram sessions. 
* clmn:     This shows the Instagram posts. clmn 1 means the first Instagram post for a given unit_id.
* emotion:  This shows the annotated emotion label for a given Instagram post.
* polarity: This shows the annotated polarity label for a given Instagram post.
* bullying: This shows the annotated bullying label for a given Instagram post.

In the following table, we show each unit_id, numbers of Instagram posts in the source data[1,2] and our annotated data.

unit_id | Number of posts in source data| Number of posts in our annotations
------------ | ------------- | -------------
652910876 | 150 | 150
702714449 | 33 | 33
702714450 | 142 | 107
702714687 | 77  | 70
702714613 | 125 | 125
702714440 | 88 | 88
702714441 | 14 | 14
702714442 | 142 | 142
702714572 | 144 | 144
702714501 | 127 | 127
Total|1042 | 1000

## Emotion labels:
* anger, 
* fear, 
* joy, 
* sadness, 
* no emotion,
* other (This covers emotions not covered by the ones above).

## Polarity labels:
* positive, 
* negative, 
* neutral. 

## Bullying labels:
* bullying,
* no bullying(i.e., noneBll).

## Frequencies and percentages of annotated labels:
![Image of frequency and percentages of annotations](https://github.com/0707pinar/Post-level-bullying-emotion-polarity-annotation/blob/master/instagram_annotations_freq_percentages.png)
      
## References:
1. Homa Hosseinmardi, Sabrina Arredondo Mattson, Rahat Ibn Rafiq, Richard Han,
Shivakant Mishra, Qin Lv, Analyzing Labeled Cyberbullying Incidents on the
Instagram Social Network, accepted in 7th international Conference of Social
Informatics, LNCS 9471, pp. 49–66, 2015 (SocInfo2015).
2. Homa Hosseinmardi, Rahat Ibn Rafiq, Richard Han, Qin Lv and Shivakant Mishram,
Prediction of Cyberbullying Incidents in a Media-based Social Network.
In ASONAM 2016: Proceedings of the 2016 IEEE/ACM International Conference on
Advances in Social Networks Analysis and Mining, 2016.


