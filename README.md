# Design a store database(KHAN ACADEMY)
This is the first Khan Academy SQL course Project where I created a Bookstore database that contains 5 columns(ID,TITLE,GENRE,PRICE and RATING)
--This is my bookstore information database
--columns will be ID,TITLE,GENRE,PRICE,RATING.
--EMMA,Dance Dance Dance,A Darkling Plain,Darkness Visible,Death Be Not Proud,The Doors of Perception,Down to a Sunless Sea,Drive Your Plow Over the Bones of the Dead,Dulce et Decorum est,Dying of the Light,East of Eden,Ego Dominus Tuus,Endless Night,England's Green,Everything is Illuminated

CREATE TABLE BOOKSTORE (ID INTEGER PRIMARY KEY,TITLE TEXT,GENRE TEXT,PRICE INTEGER,RATING INTEGER);
INSERT INTO BOOKSTORE VALUES(1,"EMMA","NOVEL",450,3);
INSERT INTO BOOKSTORE VALUES(2,"Dance Dance Dance","NOVEL",250,4);
INSERT INTO BOOKSTORE VALUES(3,"A Darkling Plain","NOVEL",550,3);
INSERT INTO BOOKSTORE VALUES(4,"Darkness Visible","NOVEL",600,3);
INSERT INTO BOOKSTORE VALUES(15,"Death Be Not Proud","NOVEL",350,3);
INSERT INTO BOOKSTORE VALUES(5,"The Doors of Perception","NOVEL",400,3);
INSERT INTO BOOKSTORE VALUES(6,"Down to a Sunless Sea","NOVEL",650,3);
INSERT INTO BOOKSTORE VALUES(7,"Drive Your Plow Over the Bones of the Dead","NOVEL",1450,3);
INSERT INTO BOOKSTORE VALUES(8,"Dulce et Decorum est","NOVEL",775,3);
INSERT INTO BOOKSTORE VALUES(9,"Dying of the Light","NOVEL",980,3);
INSERT INTO BOOKSTORE VALUES(10,"East of Eden","NOVEL",1150,3);
INSERT INTO BOOKSTORE VALUES(11,"Ego Dominus Tuus","NOVEL",875,3);
INSERT INTO BOOKSTORE VALUES(12,"England's Green","NOVEL",1300,3);
INSERT INTO BOOKSTORE VALUES(13,"Everything is Illuminated","NOVEL",580,3);
INSERT INTO BOOKSTORE VALUES(14,"Endless Night","NOVEL",1000,3);

SELECT * FROM BOOKSTORE Order By PRICE;
SELECT AVG(PRICE),MIN(PRICE),MAX(PRICE)FROM BOOKSTORE


