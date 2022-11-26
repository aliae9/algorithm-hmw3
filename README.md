***HMW3***

Proje 3 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root'u 7 alalım. root'un soluna root'dan küçük sayılar, root'un sağına root'dan büyük sayılar gelmelidir.



root => 7:

```
1.adım:

    7
   /
  5

```

```
2.adım:

    7
   /
  5
 /
1
```


```
3.adım:

    7
   / \
  5   8
 /
1
```

```
4.adım:

    7
   / \
  5   8
 /
1
 \
  3
```

```
5.adım:

    7
   / \
  5   8
 / \
1   6
 \
  3
```

```
6.adım:

      7
     / \
    5   8
   / \
  1   6
 / \
0  3
```

```
7.adım:

      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3

```

```
8.adım:

      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      5
```

```
9.adım:

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