[patika.dev](https://patika.dev)

## Binary Search Tree - Proje 3

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

-  Binary Search Tree'nin root'u olarak 5'i seçilir. Root'tan küçük sayılar sağa büyük sayılar sola yazılır.

```
       [5]-> root
      /   \
    [1]   [7]
```

```
       [5]
     /     \
   [1]     [7]
  /   \   /   \
[0]  [3] [6]  [9]
```

```
       [5]
     /     \
   [1]     [7]
  /   \   /   \
[0]  [3] [6]  [9]
    /   \     /
  [2]   [4] [8] 
```