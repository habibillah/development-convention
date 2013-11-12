Database Conventions
====================
This is the list of conventions to create databases, tables, fields, and other things related to database development.

1. use english language for name of fields and tables.
2. Table names are lowercase, plural, and underscored without abbreviation except for commonly used. example: `users`, `rules`, `organitation_units`.
3. Field names are lowercase, and without abbreviation except for commonly used like `id` or `uid`.
4. Field names with two or more words are underscored. Example: `first_name`, `last_name`, etc.
5. Use `id` as name of primary key for all tables with int data type for auto increment or char(32) for UUID/GUID.
6. use the (singular) name of the related table followed by `_id` for foreign keys. Example: `user_id` that reference to `users` table.
7. Upper casing SQL keywords and built-in functions. Example: 
     `SELECT first_name
         ,last_name
         ,CONCAT(first_name, last_name) AS full_name 
      FROM users;`
8. Avoid asterisk (*) symbol on select clause.
