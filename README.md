# Email-Classification
Email Classification using different machine learning algorithms.

A couple of years ago, J.K. Rowling (of Harry Potter fame) tried something interesting. She wrote a book, “The Cuckoo’s Calling,” under the name Robert Galbraith. The book received some good reviews, but no one paid much attention to it--until an anonymous tipster on Twitter said it was J.K. Rowling. The London Sunday Times enlisted two experts to compare the linguistic patterns of “Cuckoo” to Rowling’s “The Casual Vacancy,” as well as to books by several other authors. After the results of their analysis pointed strongly toward Rowling as the author, the Times directly asked the publisher if they were the same person, and the publisher confirmed. The book exploded in popularity overnight.

This project is of a similar nature. Udacity's course "Intro to Machine Learning" gives a step by step description of algorithms to used and their background.

We have a set of emails, half of which were written by one person and the other half by another person at the same company.
Our objective is to classify the emails as written by one person or the other based only on the text of the email. 

The following algorithm will be used for the email classification: 
> Naive Bayes

The repository has 2 pickle files : word_data and email_authors.

The email_preprocess python file serves to process the data from the pickles files. It splits the data into train/test with 0.1 test data.
