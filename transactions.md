1. create table

```sql
    create table transactions(
        id_transaction int primary key auto_increment,
        id_product int,
        id_customer int,
        foreign key (id_product) references products(id_product),
        foreign key (id_customer) references customers(id_customer)
    );
```

2. insert data

```sql
    insert into transactions(id_product, id_customer) value(
        null,
        1,
        1
    ),
    (
        null,
        2,
        1
    ),
    (
        null,
        3,
        2
    ),
    (
        null,
        4,
        2
    ),
    (
        null,
        5,
        3
    ),
    (
        null,
        1,
        3
    ),
    (
        null,
        2,
        4
    ),
    (
        null,
        3,
        4
    ),
    (
        null,
        4,
        4
    ),
    (
        null,
        5,
        5
    ),
    (
        null,
        1,
        5
    );
```