# PastaClassifier
A deep learning based model that classifies 26 pasta types!
This is my pet project, built with the knowledge acquired through the great fastAI courses and the book by Jeremy, Rachel, Sylvian and the team.
I've done some research behind the scenes about pasta and its history, but I'm not going to bore you with all the details in this first iteration. We all know it's widely regarded as an Italian dish. But its origins date back to 14th century China and Greece. There are over 600 varieties of pasta, but all of them fall under one of the following category ::

Strand
Ribbon
Tubular
Micro
Unique-shaped
Stuffed

Now I'm gonna leave out stuffed pasta, coz it's identification may well be out of the scope for my model. So I'm concentrating on 26 most common and popular pasta varieties that belong to one of the above categories. I believe they are the most important ones in-terms of production and consumption. But there will always be room for expansion and updates.

First let's define our methodology for this project. I'd like to experiment with the Drivetrain Approach by Jeremy Howard et al. I haven't exactly followed this approach before, but I prefer the iterative way of development and also trust Jeremy and his course - FastAI.
Target is to have a complete product even at the end of the first iteration.

Steps :
Objective - Do build an app that make use of a model which can predict the type of pasta from a picture of a pasta-based meal, and suggest some of the best dishes to prepare with it. The latter will include a history of the pasta type, and a recipe. Target consumers are pasta fans around the world.

Levers - What actions you can take?/What inputs you can control? - asking use to upload an image in order to make a prediction. Suggest a recipe based on the prediction.

(Side Note- Now I have to admit that I myself don't totally understand what this step exactly means, but hey, everything is a process, and let's try to understand it better with time. )

Data - We can start with publicly available data. I'm starting with downloading Bing images available via its API.

Building a model - We initially use search engine generated images. Then we can use user uploaded data with theit explicit consent. Will use Deep Neural network as an algorithm and Pytorch and FastAI as Python frameworks to build our model.



