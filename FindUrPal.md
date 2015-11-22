# Introduction #

How many times has it happened that you waited two hours for a professor only to realize that he was already there in the campus and thus losing your precious working time? Well this project aims at eliminating such situations. It'll tell you where your faculty(colleague) is and thus reducing your worries.


# Motivation #

Our project is aimed at easing the communication between students and faculty. In today’s market where money and time are important, our product takes care of both the things. It saves peoples’ time as finding people gets simpler. This being a course project is free hence saving money. All that will be required is an initial investment of time by the users for the testing phase. Our product aims at being available in two forms, namely – text messages and a mobile app(for phones with a GPS system).

Students wait long hours for their instructors to arrive to the Institute, not knowing that the instructor, due to some reason might not be coming at all. In this scenario, not all the students would ring up the instructor and ask him if he’d be coming or not. And neither will the 50-60 students come to know even if the instructor has informed 2-3 as they might not be able to spread the word. Hence this software might be of great use in such scenarios.

Further, sometimes people may be in a location where they hope to find a friend or two, but might have misplaced their phone number. Then they can simply use the app and locate their friend.

# Features, Functionality, Services #
1.Interactive UI

2.Simple to use

3.Internet connection not necessary.

4.Cost effective.

5.Fast

6.Can be used as a simple text message service or a mobile app

7.Reliable

# Workflow #

A wants to know the location of B but for that B should have allowed A to track him. For this A sends a request of permission to follow B. If B accepts then an entry is made in the table (let’s call the table as FRIENDS). The table FRIENDS keeps track of the people who are connected.

Now after A can track B, A sends a request to know the location of B to the server. The server looks in the table (STATUS) for the updates status of B. If the status is available it sends a message to A with the location of B.

If the status has not been updated then the server gets the latitude and longitude of B through GPS on his phone (or prompts B to send a text message with his location). When the server gets the coordinates, it maps them to the location in the table (LOCATION) or looks up the name of the location in GoogleMaps. When the name is found, it sends a text message to A with the location of B.

# User Feedback #
It sounds like a very useful product to the students of our college and will certainly make a difference if it can be deployed successfully. On a larger scale, it’ll help friends get closer and more socially active.