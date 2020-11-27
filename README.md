# MERO: Intelligent Recepetionist Chatbot
In this project, we wished to implement a chatbot that could function as a hotel receptionist and mimic conversations between the hotel receptionist and customers that enter the hotel. When thinking about a hotel, the most relevant characteristic would be to have immediate bookings. Instead of calling the front desk and other related departments of the hotel, the bot itself can determine and solve interrogations without any human interference.

# Using Dialogflow
While creating the chatbot using Dialog Flow, the two important parts of the chatbot are intents and entities.
# Intents
The word “Intent” indicates the motivation or the idea after the inquiry given by the user. Frequently, in business conversational settings, customer inquiries can be categorized and arranged with the meaning following the question. 
Main intents present in the Mero chatbot are:
1. Book room
2. Booking modification
3. Complaint
4. Hotel contact
5. Hotel pictures
6. Places to visit
7. Room service
8. Hotel activities
9. transportation
# Entities
Entities are used to match common types of data. There are pre-built entities in dialogflow, and you can also make custom entities.
Main entities in Mero chatbot are:
1. Room-type
2. Complaints
3. Room-service
4. Transport

# Integrating the bot in a testing website
For this you will need to enable Dialogflow messenger in the Integrations section on your dialogflow agent dashboard. You will then have to past the code in the HTML section of your website. And voila!
![alt text](https://github.com/ShireenPatel/MERO/blob/main/images/Screenshot%20(113).png?raw=true)

# Integrating the bot with telegram
You need Telegram token which you will need to paste in the input field you see once you enable telegram in the Integrations section. This way your dialogflow agent and telegram gets connected. Now you can easily search for your bot name in telegram and start chatting with it. 


