# Linguistic cues of actual lies and perceived lies
 
 ### 1. Title
Linguistic cues of actual lies and perceived lies

### 2. Abstract
“[Linguistic Harbingers of Betrayal](http://vene.ro/betrayal/) ” by Niculae et al. presents several linguistic features consistent with betrayal (i.e. more politeness and less positive sentiment), through analysis of player conversations from the strategy game Diplomacy. We propose to study if these same linguistic features are present in lies, and if they match the linguistic features of perceived lies (i.e. messages that people suspect are lies). To do so, we propose to use the [Deception in Diplomacy dataset](https://sites.google.com/view/qanta/projects/diplomacy) from “It Takes Two to Lie: One to Lie, and One to Listen” by Peskov et al. We plan to process the textual content of each message in order to extract similar linguistic features to the ones used in the Betrayal paper. Then, we will compare the features of messages from different categories, namely, truths, lies, perceived lies (from “It takes Two to Lie”), and messages leading up to a betrayal (from “Harbingers of Betrayal”).
### 3. Research questions
1. Are the linguistic features (e.g. higher politeness) found in messages leading up to a betrayal similar to the features found in lies?
2. Are the linguistic features of lies similar to the features of perceived lies? 
3. How do the linguistic features of truths perceived as truth, truths perceived as lies, undetected lies, and detected lies differ?
### 4. Proposed datasets
[Deception in Diplomacy dataset](https://sites.google.com/view/qanta/projects/diplomacy) from “[It Takes Two to Lie: One to Lie, and One to Listen](http://users.umiacs.umd.edu/~jbg/docs/2020_acl_diplomacy.pdf)” by Peskov et al. \[ACL 2020\]. This dataset contains player messages in plain text (unlike the Betrayal dataset), as well as metadata including the speaker intention (Truth/Lie), the receiver perception (Truth/Lie), and game information such as the score and Diplomacy-year at the time the message was sent. We will then need to process messages into linguistic features by using tools such as NLTK, spaCy, or ConvoKit.
### 5. Methods
#### Data collection: 
Use the Deception in Diplomacy dataset.
#### Text processing:
 Use tools such as [NLTK](https://www.nltk.org/), [spaCy](https://spacy.io/), [Convokit](https://convokit.cornell.edu), as well as [other tools out there](https://github.com/xiamx/awesome-sentiment-analysis) (if necessary) to process raw messages and obtain linguistic features (e.g. positive sentiment and politeness).
#### Data analysis:
 Obtain information about the dataset, such as when lies and perceived lies are most likely to happen in terms of year and game score.
#### Matching:
If necessary, perform matching (e.g., by matching each lie with a truth with a similar year, game score, and game score delta).
#### Data comparison:
Use the obtained linguistic features to compare the different types of messages (truths, lies, perceived lies, …). Compare them to the results found in the “Linguistic Harbingers of Betrayal” paper.
#### Data visualization:
Visualize these results using matplotlib and seaborn. Try to obtain figures with a similar style to the ones in the Betrayal paper.

### 6. Proposed timeline
#### 1st week: 
Initialize the repository, preprocess the data to obtain the desired features (politeness, planning markers, sentiment analysis). Do data analysis and start working on the matching.
#### 2nd week: 
Perform matching,  the data comparison (answer the research questions), plot the visualizations, analysis of the results, matching if we deem it necessary.
#### 3rd week: 
Finalization of the notebook, writing of the LaTeX report, making the video

### 7. Organization within the team
*JB = Jean-Baptiste de la Broise, DC = David Cian, DM = David Mizrahi*  


In week 1, JB will handle the text processing, by finding and using good tools to obtain the desired linguistic features. While DM and DC will perform data analysis to learn more about the dataset at hand, which will then be used to find good ways to perform the matching.  
In week 2, DC will perform the matching, which will then be used by DM (using the obtained linguistic features) to do the data comparison and visualization. JB will think about alternate visualizations of the results.  
In week 3, JB will mainly focus on cleaning up the notebook for submission, while DM and DC will mainly focus on the LaTex, although all 3 of us will work on both parts to some extent. Once done, DC will then focus on the video.
