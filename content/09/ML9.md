---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.2'
      jupytext_version: 1.3.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

# Machine Learning

Time to get into the fun stuff, Machine Learning. Machine Learning has been the talk of on the decade with the rise of big data, tech start-ups, and the dubbing of the [Data Scientist](https://www.hbs.edu/faculty/Pages/item.aspx?num=43110) as the sexiest job of the 21st century. In reality machines learning as been around for quite sometime. In fact the term "Machine Learning" was coined in 1959 and early Machine Learning was based around pattern classification. Early examples include reseachers in 1981 who used nueral nets to create an alogorthim to classify indenify 40 unique characters.

The reason Machine Learning didn't pickup until the 2000s is result of computational power and data storage. It was not until the last few decades that we have the computational power to truly leverage the power of ML alogrithms at scale, think AWS cloud computing. Addtionally, the cost of data storage has dropped substantially since the early days of machine learning. This is important because machine learning models benefit from being trained on large amounts of data. Secondly, with more data comes more use cases for machine learning, think of Google who recommends items based on your search history or Tesla which uses driving patterns to create self-driving cars. 

In this section we won't go into the details of how to create your own self-driving car, but we will cover the basics of machine learning so that you can hold your own in conversation and identify possible use cases in your day to day life.


So, what is machine learning. The formal definition is the scientific study of algorithms and statistical models that computer systems use to perform a specific task without using explicit instructions, relying on patterns and inference instead. In laymans term, machine learning is algorthims that give a computers the capability to learn something with out explicitly being programed to do so. Still confused? No problem, below are a few examples that will help in conceptualize machine learning:

- __Amazon Alexa:__ Alexa is an example of speech recognition which leverages machine learning to translate spoken words to text. In advanced use cases speech recognition can adapt to your dialect.
- __[Hotdog Not Hotdog](https://www.youtube.com/watch?v=ACmydtFDTGs) (Image Recognition)__: In the T.V. series Silicon Valley a character created a machine algorthm that is able to detect if in an image contains a hotdog.
- __Spotify Recomendations:__ Ever wonder how spotify is able recommend songs that just happend to be right up your alley. It's not by conquincidence. Spoifty is able to leverge the data of all its users and their music tastes to _cluster_ you into a group and provide recommend based on other users in the same group.


Now that we know what machine learning is, let move a little bit deeper. Machine learning can be spilt in to main groups, supervised learning and unsupervised learning. 

Supervised learning is when the machine learning model is trained using labeled data, meaning that our data is already tagged with the correct answer. We can use an example of a model that predicts the DOW Jones. The model would be fed some predictive variables and a labeled varaible, the closing value of the DOW Jones for a given day. The model would then assign weights to each of the predictive varirables such that it would maximize the accuracy of predicting the DOW Jones. It is instrumental to understand the importance of the labeled variable in supervised learning, without it you cannot train your model to make predcitions.

Unsupervised learning is the training of a machine learning model using information that is neither classified nor labeled thus the algorithm will act our given information without guidance. An example is clustering. Say we give our upsupervised machine learning model pictures of both tennis racquets and baseball bats. The model would use characteristics of the images to separate the images into different groups. The groups will not be labeled and would require a human to define each group, but none the less unsupervised learning can be very powerful in creating disjoint groups that a human is not capable of identifying.
