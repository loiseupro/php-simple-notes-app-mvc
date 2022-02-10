# php-simple-notes-app-mvc
This basic application has been created as an example, using the MVC paradigm in PHP.

For this application to work, you must create this database and table:

```
CREATE DATABASE mvc_example; 

CREATE TABLE `note` (
  `id` int(11) NOT NULL,
  `title` varchar(75) NOT NULL,
  `content` text NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

ALTER TABLE `note`
  ADD PRIMARY KEY (`id`);
  
  ```
