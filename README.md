# tableSql
## Tables


##### Table1:books

| Sno | Catagories | Popularity | High price | low price | latest |
| -- | -- | -- | -- | -- | -- |
| 1 | java | High |1000 | 100 | 20-1-19 |
| 2 | C++ | Medium |500 | 80 | 20-10-18 |
| 3 | C | Low | 100 | 50 | 20-10-17 |

`
Select * from books;
`
```
select * from books order by catagories;
  
  ```
  ```
select * from books order by popularity;

```
```
select * from books order by price desc;

```
select * from books order by price;

```
```
select * from books order by date;

```
