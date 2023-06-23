# Hash tables are powerful data structures used to store and retrieve data efficiently. They provide constant-time average-case complexity for insertion, deletion, and retrieval operations, making them a fundamental tool in computer science. In this guide, we will explore the concept of hash tables, their implementation, and their various applications.

# What are Hash Tables?

## Hash tables, also known as hash maps, are data structures that enable efficient key-value pair storage and retrieval.
## They are based on the concept of hashing, which involves mapping data to a fixed-size array using a hash function.


# set() When adding a new key/value pair to a hashtable:

## send the key to the hash() method. Once you determine the index of where it should be placed, go to that index Check if something exists at that index already, if it doesn’t, add it with the key/value pair. If something does exist, add the new key/value pair to the data structure within that bucket. get() The get() method takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

## has() The has() method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the hash() method and check the hashtable if the key exists in the table given the index returned.

## keys() The keys() method returns a collection (array) of unique hash keys.

## hash() The hash() method will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

## The efficiency of a hash table depends on the distribution of the hash codes and the quality of the hash function. A good hash function should evenly distribute the keys across the array to minimize collisions and ensure efficient operations.

## Overall, a hash table provides fast access to data by leveraging the hash codes and indexing techniques. It is widely used in various applications, including caching, indexing, and data storage.

# WHY:

## Hash tables are used to efficiently store and retrieve data based on key-value pairs.
## They provide fast access to data, making them suitable for tasks like data lookup, caching, and indexing.
## Hash tables are ideal when there is a need for quick data retrieval without iterating through a large dataset.