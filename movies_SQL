CREATE TABLE movies(
    movie_name VARCHAR(50),
    lead_actor VARCHAR(50),
    actress VARCHAR(50),
    year_of_release INT(4),
    director_name VARCHAR(50)
);


-- Inserting the values into 'movies' table
INSERT INTO movies VALUES('Thiruchitrambalam','Dhanush','Nithya Menon',2022,'Mithran.R.Jawahar');
INSERT INTO movies VALUES('Velaiyilla Pattathari','Dhanush','Amala Paul',2014,'R.Velraj');
INSERT INTO movies VALUES('Bhadra','Ravi Teja','Meera Jasmine',2005,'Boyapati Srinu');
INSERT INTO movies VALUES('Hridayam','Pranav Mohanlal','Kalyani Priyadarshan',2022,'Vineeth Sreenivasan');
INSERT INTO movies VALUES('Rangasthalam','Ram Charan','Samantha Ruth Prabhu',2018,'Sukumar');


-- 1. Retrieving all the attributes from 'movies' table
SELECT * FROM movies;


-- 2. Retrieving all the attributes from 'movies' table based on 'lead_actor'
SELECT movie_name,lead_actor,actress,year_of_release,director_name FROM movies WHERE lead_actor='Ravi Teja';


-- 3. Retrieving 'movies_name' from 'movies' table based on 'lead_actor','actress','year_of_release'
SELECT movie_name FROM movies WHERE lead_actor='Dhanush' AND actress='Amala Paul' AND year_of_release=2014;


-- 4. Retrieving all the attributes from 'movies' table whose 'year_of_release' between 2017,2020
SELECT movie_name,lead_actor,actress,year_of_release,director_name FROM movies WHERE year_of_release BETWEEN 2016 AND 2019;


-- 5. Sort the values of tables based on 'year_of_release' 
SELECT movie_name,lead_actor,actress,year_of_release,director_name FROM movies ORDER BY year_of_release;


-- 6. Retrieving all the 'movie_name','director_name' from 'movies' table that are not directed by 'Mithran.R.Jawahar'
SELECT movie_name,director_name FROM movies WHERE director_name!='Mithran.R.Jawahar';
