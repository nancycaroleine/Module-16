# Ex. No: 16B - Constructing and Balancing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree**, balance it, and print the nodes **before and after balancing** using the appropriate packages and built-in function.

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a method `getDictTree(tree)` to return the `dict_tree` or structure of the AVL tree.

**Step 3**: Define a method `Construct_AVL(L)` to:
- Create a binary tree from the list `L`.
- Print the tree **before balancing**.
- Sort and reinsert the nodes in a balanced manner (simulating AVL behavior).
- Print the tree **after balancing**.

**Step 4**: Create a list `L` of integers.

**Step 5**: Call `Construct_AVL(L)` to build and balance the tree.

**Step 6**: End the program.

## PYTHON PROGRAM
```
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L,N):
  tree = AVL(L)
  for i in N:
      tree.insertNode(i)
  print("AVL Tree Before Balancing\n",getDictTree(tree))
  tree.BalanceTree()
  print("AVL Tree After Balancing\n",getDictTree(tree))

```

## OUTPUT
![image](https://github.com/user-attachments/assets/c997f22e-3cda-4f2f-a7af-296a8fc8d27c)
## RESULT
Thus , a Python program to construct an **AVL tree**, balance it, and print the nodes **before and after balancing** using the appropriate packages and built-in function are verified.
