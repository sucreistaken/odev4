# odev4
SQL
Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
-- select distinct replacement_cost from film
*************************************************************************
film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
--select count(distinct replacement_cost) from film
*************************************************************************
film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
--select count (title) from film where title LIKE 'T%' AND rating ='G';
*************************************************************************
country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
--select count(*) from country where country LIKE '_____';

--SELECT COUNT(country) FROM country WHERE length(country)=5;
*************************************************************************
city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
--select count(*) from city where city ILIKE '%r' 
*************************************************************************
