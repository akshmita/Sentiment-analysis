# Sentiment-analysis: Forebroding Index
In this project, I design a forebroding Index reflecting fear and anxiousness in news reports
I use a customized dictionary for the calculation of Foreboding Index (FI) and Termfrequency Foreboding Index (TFI), which has has 102 positive words representing foreboding, anxiousness, or uncertainty and 102 negative words representing antonyms of foreboding, anxiousness or
uncertainty. 
For TFI only the words “foreboding, uncertainty, fear, worry” were taken into account, which we will call as root words.
The Foreboding Index for a news report is calculated as
FI = Number of Positive Words / (Number of Negative + Positive Words) ….(1)
The TFI for a news report is calculated as
TFI= Frequency of Root Words / Total Number of Words ……..(2)
The detailed reserach paper can be found at https://www.nibmindia.org/static/working_paper/NIBM_WP03_SRT.pdf
