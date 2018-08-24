README
---
This repository, as the name suggests, is for me to practice, write about and learn some of the computer science fundamentals that I think I am weak at.

Mainly I will be writing about:
- **[How does the internet work](#how-does-the-internet-work)** and parts of it. (Do you know how cool SSH is? How it works and which kinds of keys it uses?)
- **[Data Structures](#data-structures)** in some more detail. I know what a binary search tree is, but when do I apply it to a problem?
- **[Algorithms](#algorithms)** have you heard about Dijkstra's algorithm? It is used to find the shortest path between two points in a system. But how does it work?
- **[Regular Expressions](#regexes)** they come in handy when you have a lot of strings to match and not enough time to match them manually
- **[Basic computer science fundamentals](#cs-fundamentals)** What are strongly typed and weakly typed languages? How does the LRU cache work?
- **[System Design](#system-design)** How do you design a scalable system?
- **[Databases](#databases)** We will look at the different kinds of data stores that are being used today. I am fasconated by Redis, Elasticsearch and MySQL.
- **[Interview Questions](#interview-questions)** Basic Interview questions that I've been asked.
- **[Emacs](#emacs)** What is emacs? How does it work? I am trying to create this README.md using emacs.

---

### [Interview Questions](#interview-questions):
- Can elasticsearch do partial updates?
  - Yes, elasticsearch can do partial updates. You can post the field/part to update using the UPDATE endpoint and the id of the document to be updated. Although only the field(s) which you specified will be modified, actually the whole document will be overwritten. What exactly will happen is that the document to be updated will be retrieved, the changes will be made and the old document will be overwritten with the new document.

- Suppose that I index information about all the restaurants in a particular city. Assuming necessary data, how can I fetch all the restaurants that serve chinese food near me?
  - First of all, I assume that all the restaurants have a tags field which stores the types of cusines that that restaurant serves. So, first,  I'll search for all the restaurants with the tag _chinese_. Then, I'll need the user location to be able to search for the nearest restaurant. Let's suppose our delivery distance is of a 10 km area. Then I'll use 

- What is Normalization in databases?
  - pass