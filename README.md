# Emotion-mining

Brief Points:
The article tried to fill the gap between emotion recognition and emotion correlation mining through natural language text from Web news. The correlation among emotions contributes to the failure of emotion recognition.
The system proposes a semi-supervised framework for emotion tweet detection. The detectors are designed based on our observations made from a collection of 14 million tweets, and the detectors are computationally effective, suitable for real-time detection.
More importantly, detectors utilize classification techniques at two levels, tweet level, and cluster level
Most of the emotion mining projects are detecting either positive or negative emotion, But the uniqueness in this project is to detect 4 types of emotions which are happy, sad, angry, surprise.

Summarization:


 ABSTRACT:
 
Emotion analysis has been attracting researchers' attention. Most previous works in the artificial- intelligence field focus on recognizing emotion rather than mining the reason why emotions are not or wrongly recognized. The correlation among emotions contributes to the failure of emotion recognition.  In this article,  we try to fill the gap between emotion recognition and emotion correlation mining through natural language text from Web news. The correlation among emotions,  expressed  as  the  confusion and evolution of emotion, is primarily caused by human emotion cognitive bias. The emotion confusion law is extracted through an orthogonal basis. The emotion evolution law is evaluated from three perspectives: one-step shift, limited-step  shifts,  and  shortest  path transfer. The method is validated using three   datasets:   1)   the   titles;   2)   the bodies;  and  3)  the  comments  of  news articles,   covering   both   objective   and subjective texts in varying lengths (long and short). The experimental results show   that   in   subjective   comments, emotions are easily mistaken as anger. Comments tend to arouse emotion circulations of love-anger and sadness- anger.  In  objective  news,  it  is  easy  to recognize text emotion as love and cause fear-joy circulation. These findings could provide insights for applications regarding affective interaction,   such as   network   public sentiment, social media communication, and human-computer interaction.


Introduction:

Emotion is  complex, individualized,  subjective,  and sensitive to context.  Emotion  guides decision, prepares   the   body   for   action,   and shapes the ongoing behavior [1]. Philosophers tend to conclude that emotion is a subjective response to the objective world, which means emotion stems from the interaction between society and individuals. Individual emotion is complex in at least the following three aspects.
1)Steady individual value is formed through long-term experience. Emotion response among individuals differs even in the same context. For instance,    the    Napoleonic    War    is disputed with two opposite views. The supporters hold the view that the war attacks the French feudal force and prompts historical progress,  while the opponents think the war is unjustified due to its aggressive purpose.
2)Misunderstanding occurs when individuals communicate. The understanding of the context varies as individual prior backgrounds differ. The opinion of an individual becomes more profound when obtaining more knowledge on target events. The misunderstanding of initial emotion happens when there is a prior knowledge gap between the information sender and the receiver.
3)	Individual emotion turbulence exists. The turbulence is affected by external instant negative or positive mood. Emotion changes along with instant conditions for the same event. For most individuals,  it  is  a  common phenomenon in daily life that external conditions influence internal emotions. For example, a sweet-sounding tweet can also be disturbing when one’s work performance is judged negatively.
Emotions are correlated rather than independent, which contributes to the complexity of individual and public emotions. Emotion correlation mining can help analyze the individual and public emotions at least in the following applications:
1)	Public Sentiment Analysis: As Zhao et al. pointed out, emotion variation  contributes  a  lot  to  netizens’ behavior comprehension and abnormal event detection in social media.
2)	Social Media Communication: It is beneficial to generate low ambiguous messages that are empathetic to the information receiver for both news compilation and interpersonal communication. Emotion correlation mining can provide clues for the expression of the intended emotion.
3) 	Human–Computer  Interaction (HCI): Emotions contribute to improve HCI,   for   example,   social   companion robots. Emotion is intuitive in providing robots clues to understand and predict behavior for humanistic reaction.
PROPOSED SYSTEM
In  the  proposed  system,  the  system proposes  a  semi-supervised framework for emotion tweet detection. The proposed framework mainly consists of two main modules: 1) four lightweight detectors in the emotion tweet detection module for detecting emotion tweets in real time and 2) updating module to periodically update the detection models based on the confidently labeled tweets from the previous time window. The detectors are designed based on our observations made from a collection of 14 million tweets, and the detectors are computationally effective, suitable for real-time detection.
More importantly, our detectors utilize classification techniques at two levels, tweet  level  and  cluster  level.  Here,  a cluster is a group of tweets with similar characteristics. With this flexible design, any features that may be effective in emotion detection can be easily incorporated into the detection framework. The framework starts with a small set of labeled samples and updates the detection models in a semi-supervised manner by utilizing the confidently labeled tweets from the previous time window. This semi-supervised approach helps to  learn  new  activities,  making  the framework more robust in identifying emotion tweets.

IMPLEMENTATION:

a.Admin Server

In this module, the Admin has to login by using valid user name and password. After login successful, he can perform some operations such as View All Users And Authorize,View Friend Request And Responses,View  All  Users  Tweets,View All    ReTweets    Details,Add    Emotion Filter,View Emotion Detection in Twitter Stream,View  Tweet  Score  Results,View Emotion Detection Results.
b.User

In this module, there are n numbers of users are present. User should register before performing any operations. Once user registers, their details will be stored to the database. After registration successful,  he  has  to  login  by  using authorized user name and password. Once Login is successful user can perform some operations like Search Friend And Find Friend Request ,View All My  Friends,Create  Your  Tweet,View  All Your   Tweets,View   All   Your   Friends Tweets and Retweet.

