# SQL

## SELECT
```sql
SELECT id, name FROM users;
SELECT * FROM users WHERE age > 18;
SELECT * FROM users ORDER BY created_at DESC LIMIT 10;
```

## Агрегаты
```sql
SELECT COUNT(*) FROM users;
SELECT city, COUNT(*) FROM users GROUP BY city;
```

## JOIN
```sql
SELECT u.name, o.total
FROM users u
JOIN orders o ON o.user_id = u.id;
```

## Изменения
```sql
INSERT INTO users (name, age) VALUES ('Иван', 30);
UPDATE users SET age = 31 WHERE id = 1;
DELETE FROM users WHERE id = 1;
```
