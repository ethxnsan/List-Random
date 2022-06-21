## List
A data structure that is mutable (changeable) ordered sequence of elements. Defined by having values between square brackets [ ] 

ex:
```python
groceryList=["pie","takis","dino nuggets", "chicken tenders", "cheese", "pineapple", "sausage"] #List of strings each string separated by a comma
```

### Indexing List
Each item in a list corresponds to an index number, which is an integer. starting with 0.

ex:

`grocerylist[3]` outputs: --> chicken tenders

`len()` gives us the length of items in our list

`len(groceryList)`--> 7

### List Functions
List.append(Element)--> Adds an item to the end of a list

`grocerList. append("bacon")`

ex:
```python
item = input("Enter a grocery list item: ") #whatever the user inputs
groceryList.append(item) #adds user's input to te end of the list
```
List.insert(Index, Element) --> Add an item to the specific index location

 - `groceryList.insert(0,"water")`
-List.remove(Element) --> Searches the list for a specific element and removes it

 - `groceryList.remove("pie)"`
 - List.pop(Index)--> Removes an item at specified index
   -`groceryList.pop(3)

   ## Random
   A class that randoms numbers. There is a function that lets the computer pick a random number between a given range

   ## Formula
   ```python
    import random #import the random package library
    
  variable = random.randint(startNum, endNum) 

  ex:
  x = random.randint(0,10) 