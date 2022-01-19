# Here-Technologies-2

## Task 2 :

### Given list of contacts in your address book, please implement a Java search function. 

Example names: Mark Zuckerberg, Will Smith, William Gates, Warren Buffet

Example search input: willi 

should return following output:

candidates with "w" : Warren Buffet, William Gates, Will Smith 
candidates with "wi" : William Gates, Will Smith 
candidates with "wil" : William Gates, Will Smith 
candidates with "will" : William Gates, Will Smith 
candidates with "willi" : William Gates


Implementation :

I have used "Trie" data structure to implement the Phonebook. 

Trie is an ordered tree data structure that uses strings as keys. Unlike Binary Trees, Tries do not store keys associated with the node. The key is actually determined based on the position of the node on the tree. Any descendants of a node shares a common prefix of the key string associated with that node. Hence, trie is also called as Prefix Tree. The word "trie" comes from Retrieval, and it is pronounced as "try". To read more about Trie click here. Since this data structure is a prefix tree, trie is commonly used in Dictionaries, Phone Directories and matching algorithms. Trie is best-suited for phone directory (any matching application for that matter) because it is very efficient in matching strings.


### Screenshot : The application works fine, and gives result as expected.

Phonebook entries : {"Mark Zuckerberg", "Will Smith", "William Gates", "Warren Buffet"}

Query String : Will

Output : 

Suggestions based on w are 
warren buffet
will smith
william gates
Suggestions based on wi are 
will smith
william gates
Suggestions based on wil are 
will smith
william gates
Suggestions based on will are 
will smith
william gates






