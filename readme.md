# EazyEatz
By: Nayef Ahmed, Chase Haddleton, Ali Toyserkani, Jack Xu

## Idea
Restaurants today are stuck in the past and EazyEatz aims to change that. When you go out for dinner, EazyEatz—utilizing beacon technology—identifies the specific table and restaurant that you and your friends are eating at. While dining, EazyEats allows you to review the menu, order food, and the best part is that when you're done you can just get up and leave. EazyEatz automatically splits your party's bill (equally, or sliced up however you like!), and our innovative leave-and-pay technology reduces the hassle of paying by allowing you to simply leave the restaurant and automatically have your bill charged to you. 

## Challenges
There were a few different challenges in the making of this project, mainly: 
* Git smashing all application files half way through the event
* Estimote Beacons being locked to their registered owners (of whom we are not) 
* A significant portion of the technologies utilized were new to the team

## Solutions
The EazyEats app was created using react-native which enabled us to have a cross-platform compatible app with minimal additional work. The backend of EazyEatz utilizes Node.JS and MongoDB, and is hosted off of Google's Cloud Platform. Due to the Estimotes being locked, our team tried to come up with an alternative solution to using the beacons by building an RFID card reader. Upon the readers detection of a smartphone, it connects back through the internet to the server to push the data to the user's phone (that otherwise would have been gotten from the beacon).

## GUI screenshot
![alt tag](https://github.com/chasehaddleton/EazyEatz/blob/master/readmeImage/cover.png)
![alt tag](https://github.com/chasehaddleton/EazyEatz/blob/master/readmeImage/passcover.png)
![alt tag](https://github.com/chasehaddleton/EazyEatz/blob/master/readmeImage/menu.png)
