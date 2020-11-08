---
title: "Computing - Hash Tables"
date: "2020-11-03 10:07"

tags: ["@?computing", "@?public"]
---

##### What is the main advantage of a hash table??
You can quickly find items given a key.

##### A hash table is a type of what data type??
An Abstract Data Type.

##### How is an element's key calculated??
Using a hash function.

##### A key-value hash table is sometimes called what??
A hash map.

##### What is a hashing algorithm??
A calculation applied to a key to transform it into an address.

##### What is it called when a hash function generates the same value for two different inputs??
A collision.

##### What is it called when you find a new place for a value after two inputs have the same hash??
Open addressing.

##### What is the formula for load factor??
$$
\frac{\text{total items}}{\text{capacity}}
$$

##### What can load factor be used for??
Calculating when it is neccassary to allocate more space to store something.

##### Once a hash has been calculated, what operation is used to normalise it to the length of the array??
$$
\text{mod}
$$

##### What is a common method of calculating a hash for a string??
Adding together the ASCII numbers of the characters.
