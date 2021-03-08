# Predicting Laughter in Stand-Up Comedy
Overview
This project seeks to predict where laughter will occur in a stand-up comedy set. Different Natural Language Processing (NLP) models will be used to categorize comedy transcripts. The best model will be used to categorize all lines in the dataset and will be applied to training and validation sets. Finally, a prediction will be made to test set

## Challenges
•	Establishing a ground truth – identifying where the laughter appears in the text. This may require manually identifying laughter and tagging it. <br>
•	Merging different sources of data together. <br>
•	Classic stand-up follows a regular pattern of introducing a premise, the set-up, and the punchline. However, in modern stand-up the comedian uses techniques like character or persona, personal stories, act outs, facial expressions, vocal tone and pacing. All of these are indistinguishable when looking at raw text. <br>
•	Stand-up needs the audience to have some background knowledge in order for a punchline to work. NLP models do not have this knowledge. <br>
•	Several stand-up techniques need memory of what has happened previously in a set – in particular, tags and callbacks. NLP models are limited in their memory <br>

## Data Sources
Primary
•	Stand-up Comedy Transcripts. http://scrapsfromtheloft.com/comedy/ <br>
•	Note: Stand-Up Comedy uses offensive language and pushes boundaries. To avoid offending readers this repo does not include the original text of the transcripts. I aim to avoid displaying this type of language as much as possible in the notebooks, but please be aware that some offensive words may remain.

## Next Steps
•	Extending the model, with transfer learning and pre-trained models such as ULMFiT, Google’s BERT or OpenAI’s GPT-3. <br>
•	Applying the style of one comedian on to another. <br>
•	Generating a “new” stand-up set using the model. <br>
