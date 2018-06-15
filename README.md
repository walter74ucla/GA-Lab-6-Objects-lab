# Welcome to: Objects-lab

---
Title: Morning Lab<br>
Contributors: GA Instructional Team<br>
Topics: JavaScript objects

---

## Syntax

List and describe each individual piece of syntax that we use to construct an object. Don't leave anything out! The list is finite.

Example:

```
{} curly braces define the object.
```

<br>
<hr>

## Me

1. Create an empty object called `me`.<br>
2. Assign it properties for **name**, **age**, and **email** with corresponding values.<br>

The object would look something like this if we console logged it:

```javascript
console.log(me);
```

> => {name: "Kristyn", age: 98, email: "kristyn@foo.bar"}


3. Using dot notation, access the **name** property in your object.<br>
4. Without writing directly into the object, update the value of **age** to be 1000 years old.<br>
5. Using dot notation, verify that **age** has been updated.<br>
6. Add a key to this object called: "place of residence" and give it a value of your hometown. Note that the key has spaces, therefore you cannot use dot notation.
6. Access the value of "place of residence"<br>

<br>
<hr>

## Slimer

```javascript
const monster = {
   name: "Slimer",
   color: "greenish",
   type: "plasm or ghost or something"
}
```

* Given the **slimer** object:
    - What would you write to access the `name` and console.log it?
    - What would you write to change the `type` to 'creature' (without changing it inside the object)
    - What would you write to add a key to the object called `age`, and set the age to 6?
    - console.log the object to make sure `type` is creature, and `age` is 6

<br>
<hr>

## Ogres

Let's say you want to make an adventure game where you are an adventurer and you are going to fight **ogres**.

Create **objects** to have them interact.

* how would you define your `adventurer`? Your adventurer will want a **name** and **hitpoints**. What else would your adventurer need?
* how would you define an `ogre`? Your ogre will want **hitpoints**.

* Write a very small program that will simulate a battle between your adventurer and an ogre. 
	* Whoever has more hitpoints, wins the battle.
	* You can do a console.log to show how many hitpoints each opponent has, and who ultimately wins.


<br>
<hr>

# EXTRA STUFF



# Extra Activities

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

FIGURE IT OUT

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
