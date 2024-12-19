# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
When I commented out the StandardScaler the model was a lot less accurate. The model only has an accuracy of .57 compared to ~.88 with the standard scaler. This is because the standard scaler removes variance which makes the model much more accurate.
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The model is very accurate with the StandardScaler. This is almost accurate enough for the given
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The model was very accurate. 
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No.

