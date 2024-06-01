# PHP CRUD Application

PHP application that performs crud operations

### ****Creating the Database Table****

Create a table named *crud* inside your MySQL database using the following code.

```sql
CREATE TABLE `crud` (
  `id` int(255) NOT NULL,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  `email` varchar(255) NOT NULL,
  `gender` varchar(255)
)
```
