## June 28, 2019

## Javascript and JQuery, by Jon Duckett

#### Arrays
- a data type that stores a list
- USE WHEN have a list or set of values that are related to each other
- the objects in the array *do not* have to be the same data type
```
Array literal:

var kittens;
kittens = ['calico', 'siamese', 'sphynx'];

var el = document.getElementbyID('kittens');
el.textContent = kittens[0];

*This way is favored
```
- You access items in an array as if looking into a file folder and pulling out the one you want. Each item is automatically assigned a number called an *index*

```
Access:
var itemThree;
itemThree = kittens[2];
```

**The index always starts at 0**

- You can also use properties to learn about the array: .length and so on
- Use loops to access all items in an array

--------------------------------------------------

#### Objects

### Properties and Methods
- group together a set of variables and functions to create a *real life* model
  - variables are called properties
  - functions are called methods

*Property*: part of the object and tells us something about it. The adjectives.
*Method*: represent tasks associated with the object. The verbs.

- Properties and methods have a *name* called a *key* and a **value** which is a **string, number, boolean, array, ect**

### How to create and object, literal notation

```
var hotel = {

  name: 'Holiday Inn',
  rooms: 40, 
  booked: 23,

  checkAvailability: function() {
    return this.rooms - this.booked;
  }
};

*this refers to the rooms and booked in *this* object.
```
- var hotelName = hotel.name;
OR
- var hotelName = hotel['name'];

--------------------------------------------------

#### Storing Data
- data is always stored in name/value pairs
- arrays are a special type of object
- you can combine arrays and objects to create complex data structures


Questions:
1. It seems there are a variety of syntax options. What is best practice?
2. Are objects just arrays for strings?
