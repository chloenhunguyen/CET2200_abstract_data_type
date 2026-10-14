assignment task to understand abstract data type 
1. Array

|                 | ArrayList                  | LinkedList                |
| --------------- | -------------------------- | ------------------------- |
| Access by index | O(1)                       | O(N)                      |
| Insert/Index    | May require shifting       | Change node links         |
| Memory          | Maybe have unused capacity | Extra pointer/node memory |
| Storage         | Contiguous                 | Non-contiguous            |

2. Stack
LIFO - Last In, First Out 

Main operations: 
+ push() -> add 
+ pop() -> remove top 
+ peek() -> inspect top 
+ size() 
+ isEmpty() 

Example: Undo/Redo 

3. Queue
FIFO - First In, First Out 

Main operations: 
+ add() -> enqueue 
+ remove() -> dequeue  
+ peek() 
+ size() 
+ isEmpty() 

Examples: printer requests, CPU tasks, call-center systems 
