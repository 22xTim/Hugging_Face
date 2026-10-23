#About Hugging Face:



Hugging Face is a platform and open-source community that works like GitHub for machine learning. Its

Hub hosts hundreds of thousands of pre-trained models and datasets that anyone can download and

use. Its Python library, transformers, lets you load one of those models and run it in just a few lines of

code. With scikit-learn you trained a model yourself on your own data; with Hugging Face you can start

from a model that someone else has already trained, whether it does sentiment analysis, translation,

summarization, or text generation, and plug it straight into your own program. Every model comes with

a model card that describes what it was trained on, what it’s good at, and where it can go wrong, so

reading the card is part of using a model responsibly.



Create a free Hugging Face account (optional, recommended)

1. Go to huggingface.co, click Sign Up, and create a free account with your email. Confirm your

email address when you receive the message.

2. You don’t need a paid plan for this course.

3. You do not need an account or token to complete this assignment, because all of the models

we use are public. If you see a warning that no Hugging Face token is set, you can ignore it.



More on tokens:

Keep any tokens secret. If you create an access token (Settings, then Access Tokens), treat it like a

password. Never paste it into your notebook, app.py, or any file you push to GitHub. If it ever ends up

in a repository, delete the token on the Hugging Face site and create a new one. To use a token safely,

store it in an environment variable, in Colab’s Secrets panel, or in Streamlit’s st.secrets.



This exercise matters because most real-world Python work now involves using models and tools that

other people built, not just writing everything from scratch. In this assignment you practice a skill you’ll

use in a professional setting: finding a pre-trained model, reading its documentation, running it from

Python, and connecting it to your own data.



It also teaches you to question what a model tells you. You’ll compare two models against human labels

and look at where they fail on sarcasm, negation, and neutral statements. A confident score isn’t the

same as a correct answer, and you are responsible for any AI-generated output you use, whether it

comes from a model or a chatbot writing your code.



Finally, the last part takes you from a notebook to a structured project with a module, a requirements

file, and a Streamlit app. That is the step that turns exploratory code into something other people can

run, and it’s the same step you’ll take with your Project 1 dashboard and Project 2 application.



Overview

You have had experience with csv files and databases in Python. For machine learning applications, you

have explored data visualization and model development. This week you will use a model that someone

else already trained, downloaded from the Hugging Face Hub, and then turn your notebook work into a

small, structured application.



Sentiment analysis is when a computer reads a piece of text and decides whether the writer feels

positive, negative, or neutral about something. Companies use it to sort thousands of reviews,

comments, or tweets without reading each one by hand.
