---
layout: post
title: "HashTable"
description: ""
category: 
tags: []
---
{% include JB/setup %}

**Hashtable**

Also known as Hashmap, is a datastructure that maps keys to values. It is probably one of the fastest ways to lookup an key/entity from a list of keys/entities. Conceptually, things are pretty straightforward. When an entity is added to a hashtable, the hash function is run on this entity to generate a location/index in the array of buckets/slots within the hashtable. This is the location where the value is stored. This value is what would needed to be retrieved in the future (along with the key.).  Theoritically, the hash function needs to generate a unique index per key/entity, however, in reality this is hardly the case. Most hashtable implementations handle "collision" cases graciously (a topic for another day).

Complexity of lookup, inserts and deletes in an hashtable are O(1) given that the hash function calculation is constant time and lookup on the index is also constant time.

However, memory consumption is sometimes a negative impact of hashtable. Memory is reserved for the indices in the hashtable and often times remains unused if collisions are high. To avoid this negative case, consider using tree or graph based datastructures (topic for another day)

Read more [here][1]

  [1]: http://en.wikipedia.org/wiki/Hash_table