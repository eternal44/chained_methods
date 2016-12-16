# chained_methods
Method chaining exercise

// Below is a drone object with six methods.
// Each method takes a callback and after some amount of time will execute that callback (for ease of testing, it will also console.log a value).
// At the bottom of the page the expected output is logged.
// And we invoke the chained call of the drone object. However the drone object does not yet have a chained api.

// Your job is to add a chained api to the drone object by only modifying the code in the middle of the page.

// A good answer should include the following criteria.
// 1. Code was only added between the below comments.
// 2. Each method in the chain executes only after the previous method has resolved
// 3. Your solution should be flexible to rearranging the methods or changing the timeouts.
// 4. Your solution should not change the behavior/side affects of the original methods. 
//    You should assume that you don't know how the methods on the Drone object are implemented. 
//    Only that they may or may not be asynchronous, and that they take a callback that will be 
//    called when the action is completed.
