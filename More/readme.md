# Milestone 6: Intermediate JavaScript, API

- pop(): Remove an item from the end of an array.
- push(): Add items to the end of an array.
- shift(): Remove an item from the beginning of an array.
- unshift(): Add items to the beginning of an array.

- filter method: return An array containing all the matching elements

---

- where properties of an object are shared from one object to another through a chain, is called "prototypical inheritance" 

- **JSON:** JavaScript Object Notation
- JSON.stringify() convert into string

---

## CRUD:

- Method - Put: check if already there no effect, | na thakla Add korba,
- method - Patching: update data
- Post method: POST is a request method | send some data to the server

---

- http get vs post
- CURD vs REST API

# HTTP response status codes

1. Informational responses (100–199)
2. Successful responses (200–299)
3. Redirection messages (300–399)
4. Client error responses (400–499)
5. Server error responses (500–599)

---

### Js callback function: **A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.**

### Primitive DATA Type:

- string, Number, BigInt, Boolean, Symbol, valueOf()

---

- Sure, here are your explanations in English:

 `Object.keys(objectName)` -> It will return the names of the properties of the `object` as an array.

 `Object.values(objectName)` -> It will return the values of the properties of the `object` as an array.

`Object.entries(objectName)` -> It will return pairs of keys and their corresponding values from the `object` as an array.

 `delete objectName.property;` -> This will delete both the property and its value from the object.

 `Object.seal(bottle);` -> With sealing, you can't delete existing properties, add new ones, but you can change the values of existing properties.

`Object.freeze(objectName);` -> Freezing an object means you can't delete properties, modify existing properties, or change their values. The object becomes immutable.

These are common operations in JavaScript for working with objects and their properties.
---

## get object value

- objectName.property
- objectName["property"]
- objectNmae[expression]

---

### Bind Methods

- The bind() method allows an object to borrow a method from another object without making a copy of that method.

---

# Transfer assignment private repo to my github private repo

`git clone --bare <link>`
`git push --mirror <link>`
`git remove -v`
`git remote set-url origin <link>`
