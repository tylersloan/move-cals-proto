# Move Calories App Prototype (WIP)

### Purpose
This is quick 'n dirty prototype of an app that will gather calories data via Moves App and use it as a currency to buy real goods in a custom vending machine.

### Shoutouts
+ I cloned [Davide Moro's](https://github.com/davidemoro/) example [Grunt/Angular/Express app](https://github.com/davidemoro/express-angular) to get started.
+ I'll use the [Node.js wrapper for Moves API](https://github.com/jonezy/shakes/) built by [Jonezy](https://github.com/jonezy/)

### Goals
+ Integrate the Node wrapper into the cloned project.
+ Create view to show authorized user's info and total calories burned via Moves.
+ Assign name to authorized user's ID.
+ Do click-controlled math with those calories. (This will just be client-side for now.)
 
### Future
+ Save authorized user's data from moves in MongoDB.
+ Make the calorie sum via math persist to that DB.