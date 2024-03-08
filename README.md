
# Titanic Spaceship

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.

## Installation
This project uses python libraries such as Pandas, Numpy, and Scikit-Learn. To be able to install these individual libraries, type the following code in the Terminal

- Pandas ```
  pip install pandas
        ```
- Numpy ```
  pip install numpy
       ```
- Scikit-Learn ```
  pip install scikit-learn
       ```
## Roadmap
- Importing Libraries  

- Reading both ```
  train.csv ``` and ```
  test.csv
            ```
- Data Cleaning and processing
- Model Selection 
- Model Deployment

## Data Field Description
- ```PassengerId``` - A unique Id for each passenger. 
- ```HomePlanet```- The planet the passenger departed from, typically their planet of permanent residence.
- ```CryoSleep``` - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
- ```Cabin``` - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
- ```Destination``` - The planet the passenger will be debarking to.
- ```Age``` - The age of the passenger.
- ```VIP``` - Whether the passenger has paid for special VIP service during the voyage.
- ```RoomService```, ```FoodCourt```, ```ShoppingMall```, ```Spa```, ```VRDeck``` - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
- ```Name``` - The first and last names of the passenger.
- ```Transported``` - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.

## Conclusion
The models used for this project are ```SupportVectorMachine```, svm and the ```DecisionTreeClassifier```. Amongst these two (2) models, the ```DecisionTreeClassifier``` was selected as it gave the highest accuracy (78%) 

