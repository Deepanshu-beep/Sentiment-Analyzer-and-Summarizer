# Sentiment-Analyzer-and-Summarizer
Here's the notebook which contains the code which analyzes our whole Day's Emotions and at the end of the day when we shut the code, it displays a graph summarizing our whole day's emotions.

The approach I've used is that, Firstly I detect the face using HAAR Casacde to process just the face rather than processing whole frame. It captures your frame every 2 seconds to decrease complexity and also pauses in absence of user.
Further the face is processed and classified for the 7 emotions for which the model is trained for (Angry, Disgusted, Frightened, Happy, Sad, Surprised, Neutral).

I have uploaded the model on Google Drive, You can access it from ![here](https://drive.google.com/file/d/18mYvdB2N6Ym9PIrWRGdQxmO1gREzCDVo/view?usp=sharing)
