# SQLPractice-4-3
SQL queries practice
CREATE TABLE tv_shows ( 
  id INT,
  name TEXT,
  rating INT
  );
INSERT INTO tv_shows (id, name, rating ) VALUES (1, 'Once Upon A Time', 5 );
INSERT INTO tv_shows (id, name, rating ) VALUES (2, 'The Office', 5);
INSERT INTO tv_shows (id, name, rating ) VALUES (3, 'The Mayor', 4);
--
SELECT rating, name, id FROM tv_shows ;
