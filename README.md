# Porfanity-Checker
This program checks for any abusive words and does sentiment analysis of an audio file.
This code uses APIs from Google speech recognition, transcription for translating live audio to recognisable form. 
I also used API from purgomalum website for sentiment analysis.
It has an accuracy of 98%.
The working of the program is simple as sounds:
Firstly the user will be given a choice to choose from mic or audio file.
Then after giving the input audio, the program uses API from Google and PURGOMALUM to recognise abusive and nsfw words. It also generates sentiments such as very positive,
positive, neutral, negative, very negative based on the voice pitch of the audio and gives a score of each category of sentiment between 0 to 1.
Where 0 being the sentiment was not present at all and increasing upto 1 where the sentiment is strongly present.
