1.   Population of Germany

SELECT population FROM world
  WHERE name = 'Germany';


2. Show the name and the population for 'Sweden', 'Norway' and 'Denmark'.

SELECT name, population FROM world
  WHERE name  IN ('Sweden' ,'Norway','Denmark');


3.Show the name of country whose area is between 200000 and 250000

SELECT name, area FROM world
  WHERE area BETWEEN 200000 AND 250000;


4 . Show the name and population of country whose name strat with "Al"

 SELECT name, population
      FROM world
      WHERE name LIKE "Al%";


5. Show the name of Country whose name ends with 'A' or 'L'

    SELECT name, population
      FROM world
      WHERE name LIKE "%A" OR name LIKE "%L" ;


6. Show the countries with an area larger than 50000 and a population smaller than 10000000

    SELECT name, area, population
      FROM world
      WHERE area > 50000 AND population < 10000000;

7.  shows the population density of China, Australia, Nigeria and France

    SELECT name, population/area AS population_density
      FROM world
      WHERE name IN ('China', 'Australia', 'Nigeria', 'France');


      