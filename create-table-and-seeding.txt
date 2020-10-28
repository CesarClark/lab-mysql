USE lab_mysql;
SHOW TABLES;

CREATE TABLE cars(
->vin VARCHAR(50),
->manufacturer VARCHAR(50),
->model VARCHAR(50),
->year INT, 
->color VARCHAR(50));

DESCRIBE cars;

INSERT INTO cars VALUE("jso83896", "honda", "prius", 2004, "gray");

SELECT * FROM books;
