# tableSql
## Tables


##### Table1:books

| Sno | Catagories | High price | low price | latest |
| -- | -- | -- |-- | -- |
| 1 | java |1000 | 100 | 20-1-19 |
| 2 | C++ |500 | 80 | 20-10-18 |
| 3 | C | 100 | 50 | 20-10-17 |

#### 1:Display all Books;

`
Select * from books;
`

#### 2:Sort all books by catagories:

```
select * from books order by catagories;

```

#### 3:Sort all books by High To Low;

```
select * from books order by price desc;
```

#### 4:Sort all books by Low to High;
```
select * from books order by price;

```
#### 5:Sort all books by latest;
```
select * from books order by date;

```
