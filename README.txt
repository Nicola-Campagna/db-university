QUERY 1:
SELECT * FROM `students` WHERE `date_of_birth` BETWEEN "1990-01-01" AND "1990-12-31"


QUERY 2:
SELECT * FROM `courses` WHERE `cfu`>10;

QUERY 3:
SELECT * FROM `students` WHERE `degree_id`>30;

QUERY 4:
SELECT * FROM `courses` WHERE `period`="I semestre" AND `year`=1;

QUERY 5:
SELECT * FROM `exams` WHERE `hour`>"14:00" AND `date`="2020-06-20";

QUERY 6:
SELECT * FROM `degrees` WHERE `level`="magistrale";

QUERY 7:
SELECT COUNT(*) FROM `departments`;

QUERY 8:
SELECT * FROM `teachers` WHERE `phone`<> 1;