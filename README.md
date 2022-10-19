# sql_patika_odev_11-union-intersect  www.patika.dev
sql_patika_odev_11 union-intersect
--answer1
(SELECT first_name FROM actor)
UNION
SELECT first_name FROM customer )
--answer 2
(SELECT first_name FROM actor)
INTERSECT
(SELECT first_name FROM customer )
-- ANSWER 3
(SELECT first_name FROM actor)
EXCEPT
(SELECT first_name FROM customer )
