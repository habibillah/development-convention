This is the list of conventions to create databases, tables, fields, and other things related to database development.

1. use english language for name of fields and tables.
2. Table names are lowercase, plural, and underscored without abbreviation except for commonly used. example: users, rules, organitation_units
3. Field names are lowercase, and without abbreviation except for commonly used like `id` or `uid`
4. Field names with two or more words are underscored. Example: `first_name`, `last_name`, etc.
5. Use `id` as name of primary key for all tables with int data type for auto increment or char(32) for UUID/GUID
6. use the (singular) name of the related table followed by `_id` for foreign keys. Example: `user_id` that reference to `users` table.
