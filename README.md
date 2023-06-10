# Hate_Speech_Detection

This project is to detect the hate speech(Negative Comments) on social media.

I have used the dataset from kaggle: https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset

Basically, i have used the dataset which consists of columns like hate speech and offensive language. 
I first tried to remove the stopwords using nltk library and then clean the data by removing unnecessary symbols like "#*?!\\//|" and words like"wwwhttp\\",etc using re module.

Then by using sklearn i have the train the model and applied the DecisionTreeClassifier on it.

You can taste the program by inputting some statements and it will tell you whether it is hate speech or not.
I hope it helps!
