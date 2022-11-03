
# Cheap-student-life

##Final project for the Building AI course

## Summary

My project is to help students to find where to buy things cheaper. The user of the solution will share the price of differents things they have bought and where they have bought it. The others users can see it and compare prices and find where things are the cheapiest.


## Background

My project is to help student to find where they can buy things at the best price. It is problem for many students because people don't have much money when they are student. My motivation is to help others students like to save money. This topic is important because we are in a period of inflation and prices are getting higher every time.



## How is it used?

Every user of the solution will enter the price of thing he has bought trought an web app(which I can create because I am a web developer). The solution is needed in shopping domain. It will his users to save money. The users are students but anyone else who want to save money can use it. 


This is how you create code examples:
```
def main():
   object_data_name = ['Sell Point altitute', 'Sell point longitude', 'Object name', 'Price']
   object_data = [48.788135679284466, 2.4447258580222035,"Pizza", 4.99]   # not actually needed in this exercise...
   user_data_name = ['Actual position altitute', 'Actual position longitude',"ideal price"]
   user_data = [48.78970489339042, 2.439565288149726,3] 
    
    # This is just an example 
   loss = math.sqrt((object_data[0]-user_data[0])**2 + (object_data[1]-user_data[1])**2 + (object_data[3]-user_data[2])**2)
main()
```


## Data sources and AI methods
The data comes from the users. The give the position of the sell point and the prices. It is like Wikipedia but for Shopping. 
The AI methods I will use are :
*Regression
*The nearest neighboor method

## Challenges

What does your project _not_ solve? One problem can be the fact that wholesaler who have more low prices will have more visibility than retailer who's prices are often high.

## What next?

Yes the project can become very big. I will need Web developer(both frontend and backend), others data scientist, The main assistance I will need to move on is. 


## Acknowledgments
