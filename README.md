# SQL--TASK-4

```
1. film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
1. SELECT DISTINCT replacement_cost FROM film;


2. film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
2. SELECT COUNT(DISTINCT replacement_cost) FROM film;


3. film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
3. SELECT COUNT(*) FROM film
WHERE title LIKE 'T%'AND rating = 'G';


4. country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
4. SELECT COUNT(*) FROM country
WHERE country LIKE '_____';


5. city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
5. SELECT COUNT(*) FROM city
WHERE city ILIKE '%R';

```

https://app.patika.dev/berkantkaplan
