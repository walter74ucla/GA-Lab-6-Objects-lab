![ga-logo](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)

# Objects-lab

Title: Objects Lab<br>
Class: wdi-cc <br>
Contributors: GA Instructional Team<br>
Topics: JavaScript objects

---

## Practice

### 1. Syntax

List and describe each individual piece of syntax that we use to construct an object. Don't leave anything out! The list is finite.

Example:

```javascript
// {} curly braces define the object.
```

<hr>

### 2. Me

1. Create an empty object called `me`.<br>
2. Assign it properties for **name**, **age**, and **email** with corresponding values.  Afterwards, logging the object should give the following output:
```js
{name: "Kristyn", age: 98, email: "kristyn@foo.bar"}
```
    or
```js
{
    name: "Kristyn", 
    age: 98, email: 
    "kristyn@foo.bar"
}
```

3. Using dot notation, log the **name** property in your object.<br>
4. Using bracket notation, update the value of **age** to be 1000 years old.<br>
5. Using dot notation, `console.log()` **age** to verify that it has been updated.<br>
6. Add a property to this object called: "place of residence" and give it a value of your hometown. Note that the key has spaces, therefore you cannot use dot notation.<br>
7. Print the value of "place of residence"


<hr>

### 3. Slimer

```javascript
const monster = {
   name: "Slimer",
   color: "greenish",
   type: "plasm or ghost or something"
}
```

Given the **`slimer`** object, do the following:

1. `console.log()` the `name`.
2. change the `type` to 'creature'.
3. Add a property to the object called `age`, and set its value to 6.
4. `console.log()` the object to make sure `type` and `age` are what you want them to be.
5. give the slimer a method to introduce himself, interpolating some of his properties.  call the method.

<hr>

## Apply

### 4. Ogres

Let's say you want to make an adventure where an adventurer and an ogre fight each other.

**Spend a few minutes reading this question a couple times and thinking and pseudocoding before you actually write the code.**

—> Write a very small program that will simulate a battle between your adventurer and an ogre. 
* The battle should play out automatically.  
* The ogre and adventurer will take turns attacking each other, and statistics will be shown after each attack.  
* The ogre's attacks should have random damage value, but the adventurer should always attack with the same value. 
* Whenever someone's hitpoints go below zero, the other person wins the battle.  

Create **objects** and have them interact. Remember, you are modeling things from real life. So just like the characters you are modeling, your objects will have properties (qualities) and methods (things they can do).

* how would you define your `adventurer`? Your adventurer will want a **name** and **hitpoints**. What else would your adventurer need?
* how would you define an `ogre`? Your ogre will want **hitpoints**, right? (Right.)
* How could you implement the "attack" functionalities? Should you do this by adding methods to the objects? Should those methods take parameters?
* Use `console.log()` to show each attack, how many hitpoints the person being attacked loses, the updated stats for the ogre and the adventurer.  At the end log the winner.
* You can use a loop to make the game play out. (What kind of loop? How and when will it stop?)
* Would it be helpful to create another object to control and keep track of other data that isn't specifically about the ogre or the adventurer? Like a `game` object maybe?

Doing this efficiently requires planning.  If you just started coding immediately without thinking through what you're trying to do and planning, then you're doing it wrong.  Timewise, programming is 75-90% planning, and 10-25% actually typing code.

<br>
<hr>

# Extra Practice

## User object

Let's set up an object data structure. Let's say we have a website that sells products, and we have a user of our website, and we want to store that user's data. The object data structure is a good way to organize the data from our user.

### 1. Make a user object

* Create an object called `user`.
* Write in to the object the key-value pairs for `name`, `email`, `age`, and `purchased`. Set the value of `purchased` to an empty array `[]`. Set the other values to whatever you would like.

### 2. Update the user

* Our user has changed his or her email address. Without changing the original `user` object, update the `email` value to a new email address.

* Our user has had a birthday! Without changing the original `user` object, increment the `age` value using the postfix operator. Hint: `age++`

### 3. Adding keys and values

You have decided to add your user's location to the data that you want to collect.

* Without changing the original `user` object, add a new key `location` to the object, and give it a value or some-or-other location (a string).

### 4. Shopaholic!

* Our user has purchased an item! They have purchased some "carbohydrates". Using `.push()`, add the string "carbohydrates" to the `purchased` array.

* Our user has purchased an item! They have purchased some "peace of mind". Using `.push()`, add the string "peace of mind" to the `purchased` array.

* Our user has purchased an item! They have purchased some "Merino jodhpurs". Using `.push()`, add the string "Merino jodhpurs" to the `purchased` array.

* Console.log just the "Merino jodhpurs" from the `purchased` array.

### 5. Object-within-object

You can add an object to an existing object in the same way that you can add any new key/value pair.
If we want to give our user a `friend` with a `name` and `age`, we could write:

```javascript
user.friend = {
    name: "Grace Hopper",
    age: 85
}
```

When we console.log `user`, we would see the `friend` object added to our user object.

* Write a `friend` object into your `user` object and give the friend a name, age, location, and purchased array (empty for now)

* Console.log just the friend's name
* Console.log just the friend's location
* CHANGE the friend's age to 55

FIGURE IT OUT:

* The `friend` has purchased "The One Ring". Use `.push()` to add "The One Ring" to the friend's `purchased` array.
* The `friend` has purchased "A latte". Use `.push()` to add "A latte" to the friend's `purchased` array.

* Console.log just "A latte" from the friend's `purchased` array.


### 6. Loops

* Write a _for loop_ that iterates over the User's `purchased` array (NOT the friend's purchased array), and prints each element to the console.

* Write a _for loop_ that iterates over the Friend's `purchased` array, and prints each element to the console.


### 7. Functions

Write a single function `updateUser` that takes no parameters. When the function is run, it should:

* increment the user's age by 1
* make the user's name uppercase

The function does not need a `return` statement, it will merely modify the user object.



<br>
<hr>

# Hungry for More?

## Cat Combinator

### 1. Mama cat
* Define an object called `cat1` that contains the following properties:
    * name
    * breed
    * age (a number)

* console.log the cat's age
* console.log the cat's breed


### 2. Papa cat
* Define an object called `cat2` that also contains the properties:
    * name
    * breed
    * age (a number)


### 3. Combine Cats!

The cats are multiplying!

Write a function `combineCats` that has two parameters `mama`, and `papa`. The function will take two arguments -- each a cat object.

* Pass `cat1` and `cat2` as arguments to the `combineCats` function. The function should console.log them.

Example:

```javascript
combineCats(cat1, cat2)
```

> { name: "Joe", age: 19, breed: "Mog" }

> { name: "Jam", age: 45, breed: "Siamese" }


**This is to demonstrate that functions can take objects as arguments**

You could also invoke the `combineCats` function by writing the objects straight into the parentheses:

```javascript
combineCats({ name: "Craig", age: 20, breed: "unknown" }, { name: "Linda", age: 20, breed: "undefined" });
```
<br>

* Make it so the `combineCats` function will return a combination of the two incoming cats
    * The result should be an object wherein the
        * name is a concatenation of the parents' names
        * the age is 1
        * the breed is each of the parents' breeds with a hyphen in between

Example:

```javascript
console.log(combineCats(cat1, cat2));
```

Result:

![](https://i.imgur.com/CEB2ire.png)

**This is to demonstrate that a function can return an object**

<br>
<hr>

## 4. Cat brain bender

If `combineCats` returns an **object**, and if `combineCats` takes **objects** as **arguments**, then it stands to reason that:

`catCombinator` can use **itself** as its own argument.

Take a second to stew on that . . .

What is the result of:

```javascript
console.log(combineCats(combineCats(cat1, cat2), combineCats(cat1, cat2)));
```

Whoa . . .

The above console.log is **two levels** deep of combineCats.

* Write a console.log that is **three levels** deep of combineCats. combineCats should have two arguments, each which are combineCats, each which have two arguments, each which are combineCats.

Your output should look something like:

![](https://i.imgur.com/zuTzm5X.png)

