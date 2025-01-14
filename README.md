# TravelAgent
Agent which will help users in booking flights/hotels/rent a car


TravelAgent Copilot is chatbot designed to help user to book flights/hotels/rent a car. 
It uses Microsoft Copilot Studio to develop Copilot and uses advance Generative-AI capabilities to assist users in booking.

In this chatbot we used:
- SharePoint lists to store data.
- PowerAutomate to retrieve data from SharePoint.
- Actions in Copilot Studio to call PowerAutomate Flow.
- Carousel Adaptive Cards to display flight details.
- Variables in CS to store data.
- Global Variables to pass values between topics in CS.


**In this step we are getting flights between given two cities.**
- User is ask From city and data is saved in variable in Copilot.
- Then user is ask To City and date.
- Then Action is called to get data from SharePoint list.
- Data is displayed in Carousel adaptive card.
- User can click next and previous to see all flights.


https://github.com/user-attachments/assets/962456d8-7e53-4f15-9c75-d609ade21e93


After user select flight of his/her choice we ask user questions like 
- What kind of seat they prefer (window or Aisle)
- Randomly generated seat is assigned to user
- Then through Adaptive card user details are taken like Name, Email Address, Phone number.
- Once users submit Action is called to submit data in SharePoint and generate confirmation code.


https://github.com/user-attachments/assets/e10bd756-7408-48c5-98d9-c694a323ae9e




