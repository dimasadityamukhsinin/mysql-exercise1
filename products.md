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
        null,
        'ASUS ROG',
        1000,
        1
    ),
    (
        null,
        'Alienware',
        10000,
        10
    ),
    (
        null,
        'Iphone 4',
        100000,
        100
    ),
    (
        null,
        'Iphone 11',
        1000000,
        1000
    ),
    (
        null,
        'Xiaomi Redmi Note 8',
        10000000,
        10000
    );
```