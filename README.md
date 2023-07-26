# binary-search-tree-kodluyoruz-patika
Patika.dev Veri Yapıları ve Algoritmalar Ödev 3

---

[ 7, 5, 1, 8, 3, 6, 0, 9, 4, 2 ]

root= 7; insert=5, 7'nin solunda bulunur

```
  7
 /
5
```

insert=1; 7'nin solunda, 5'in solunda bulunur

```
    7
   /
  5
 /
1
```

insert=8; 7'nin sağında bulunur

```
    7
   / \
  5   8
 /
1
```

insert=3; 7'nin solunda, 5'in solunda, 1'in sağında bulunur

```
    7
   / \
  5   8
 /
1
 \
  3
```

insert=6; 7'nin solunda, 5'in sağında bulunur

```
    7
   / \
  5   8
 / \
1   6
 \
  3
```

insert=0; 7'nin solunda, 5'in solunda, 1'in solunda bulunur

```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```

insert=9; 7'nin sağında, 8'in sağında bulunur

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```

insert=4, 7'nin solunda, 5'in solunda, 1'in sağında; 3'ün sağında bulunur

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```
insert=2, 7'nin solunda, 5'in solunda, 1'in sağında; 3'ün solunda bulunur

```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```