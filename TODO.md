Create a function createUser that accepts name and age and returns a new object with those properties.

Add a method named sayHello inside the object created above. When called it should alert Welcome {user}. Replace {user} with the name of the user.

Use the data (name, age) of two different person to create the object using createUser. Store the returned value in personOne and personTwo.

Change the code inside createUser in such a way that the methods sayHello doesn't have to be in all object. Use the prototypal nature. (Hint Object.create())

Convert the createUser function into Pseudoclassical pattern of object creation. Use F.prototype to store the methods. F.prototype means storing the methods in prototype property of the function.

Use new to create two new objects with the data of two different person and re-assign the value of personOne and personTwo.

Try calling personOne.sayHello() and personTwo.sayHello(). Check if you get the required output.

Convert the createUser function into User class.

Check by creating two instance of the class using data of two different persons and re-assign the value of personOne and personTwo

Try calling personOne.sayHello() and personTwo.sayHello(). Check if you get the required output.