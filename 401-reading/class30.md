# Class 30

[Home](https://daviey52.github.io/reading-notes/)

## Hashtables

Hash is the result of some algorithm taking an incoming string and converting it into a value. This could be used for security purpose or determining the index of the array.

Bucket – this is what is contained in each index of the array of the hastable. Each index is a bucket that could potentially contain multiple key/value pairs.

Collision is what happens when more than one key get hashed to the same location
The idea of a hashtable is the ability to store the key into this data structure and be able to quickly retrieve this value. This is done through what is called a hash. Hashtable allows us to have a time complexity of 0(1) as opposed to looping through the array which give us a time complexity of (n)

The hash function takes a key and returns an interger. This interger can be used to determine where the key/value pair should be placed. The hash code is calculated in constant time and writing to an array at one index 0(1)

### Creating a Hash

1. Add or multiply all the ASCII values together.
2. Multiply it by a prime number such as 599.
3. Use modulo to get the remainder of the result, when divided by the total size of the array.
4. Insert into the array at that index.

Each index of the array can hold many types of values. The trick is how the values are stored in comparison to efficiency. Each Index of the array contain “buckets”. Each of these “buckets” holds one key/value pair combination. When there is no entry in a specific bucket, the buckets (each index of the array) all start NullThe hash table starts each bucket empty and overwrites their value once a key generates a hashCode that corresponds with an index.

Collisions occur when more than one key hashes to the same index in an array. A perfect hash will never have any collition but this can be hard to fully implement.
Common method in a Hashtable class : Find , Contains , Get , Add
