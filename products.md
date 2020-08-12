1. create table

```sql
    create table products(
        id_product int primary key auto_increment,
        product_name varchar(20),
        price int(20),
        stock int(25)
    );
```

2. insert data

```sql
    insert into products value(
        1,
        'ASUS ROG',
        1000,
        1
    ),
    (
        2,
        'Alienware',
        10000,
        10
    ),
    (
        3,
        'Iphone 4',
        100000,
        100
    ),
    (
        4,
        'Iphone 11',
        1000000,
        1000
    ),
    (
        5,
        'Xiaomi Redmi Note 8',
        10000000,
        10000
    );
```