# Build a personal assistant/ chatbot using RASA

Today, consumers are demanding round-the-clock service for assistance. Conversational AI can help to automate this process and to fulfil these expectations. As a result companies are rapidly looking to develop chatbots and virtual assistants to answer questions customers may have at any time of day. 

While brainstorming about a potential use case, that specifically adresses a certain personal need, the idea of creating a **chatbot** that is able to **tell the current time of several international destinations** given the user's location came into my mind. Since I love traveling (especially discovering different continents) you always also have to deal with different time zones. Immediately knowing the respective time in a certain country just by asking your personal assistant turned out to be very convenient.

Rasa is an open source machine learning framework for building AI assistants and chatbots. It turned out to be the ideal foundation for that purpose. 

In order to interact with the bot the following commands are of importance:

- (Re-)trains your rasa model <br>
    *rasa train*

- Starts an action server using the Rasa SDK <br>
    *rasa run actions*

- Loads your trained model and lets you talk to your assistant on the command line <br>
    *rasa shell*


Credits go to this fantastic tutorial: 
https://www.youtube.com/watch?v=1cq7TerQaXI&list=PL75e0qA87dlEjGAc9j9v3a5h1mxI2Z9fi&index=9

