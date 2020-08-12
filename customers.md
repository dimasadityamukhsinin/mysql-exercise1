1. create table

```sql
    create table customers(
        id_customer int primary key auto_increment,
        full_name varchar(20),
        username varchar(20),
        email varchar(25),
        no_hp varchar(25),
        address text
    );
```

2. insert data

```sql
    insert into customers value(
        null,
        'Dimas AM',
        'dimas',
        'dimas@dimas.com',
        '1234567890',
        'Jl.Purwodadi'
    ),
    (
        null,
        'Agung',
        'agung',
        'agung@agung.com',
        '1234567890',
        'Jakarta'
    ),
    (
        null,
        'Mondang',
        'mondang',
        'mondang@mondang.com',
        '1234567890',
        'Jakarta'
    ),
    (
        null,
        'Ridho',
        'ridho',
        'ridho@ridho.com',
        '1234567890',
        'Jakarta'
    ),
    (
        null,
        'David',
        'david',
        'david@david.com',
        '1234567890',
        'Jakarta'
    );
```