# Sentiment-Analyzer-and-Summarizer
Here's the notebook which contains the code which analyzes our whole Day's Emotions and at the end of the day when we shut the code, it displays a graph summarizing our whole day's emotions.

The following pipeline  has been implemented to accomplish the task:
1. Firstly Face detection is performed using HAAR Casacde to perform facial detection for further processing, rather than processing whole input frame. It captures the facial expression every 2 seconds to decrease complexity and also pauses in absence of user.
Further the face is processed and classified for the 7 emotions for which the model is trained: (Angry, Disgusted, Frightened, Happy, Sad, Surprised, Neutral).

You can find the trained weights file for expression classifcation ![here](https://drive.google.com/file/d/18mYvdB2N6Ym9PIrWRGdQxmO1gREzCDVo/view?usp=sharing)
