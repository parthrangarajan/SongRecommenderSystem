# SongRecommenderSystem
Another interesting use-case of TuriCreate in Machine Learning i.e. Song Recommender System.

This repository explores the use of two different recommender systems:\
1.Popularity Based Recommendation Systems: As the name suggests, the Popularity Based Recommendation System works on and with the trend. It uses whatever items, in this case songs which are in trend at the moment. If a certain product(song) is being picked more almost everytime by a new user, it means that the likelihood of another user picking it is high.Thus, we could recommend that particular product to the new user.\
2.Personalised Recommender Systems: These are Recommender Systems,which are quite similar to Content Based Recomendation Systems as they rely on the input data from the new user, based on which different products(i.e. songs) are recommended to him/her.

In this repostory we will be using both **_Popularity Based Recommendation Systems_** as well as _**Personalised Recommender Systems**_. The Personalized Recommender System will recommend only those songs that chosen by the user. For example, if the user passes "Elton John" in the _.recommend()_ funtion, she/he will recieve all those songs that were by "Elton John".

The Popularity Based Recommendation Systems works on a scoring prinnciple where sings that are picked more often are more popular. This is a very intuitive approach.
