# Patika SQL Ödev 7
Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

1.Film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.

2.Film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.

3.Customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir? 

4.City tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.

1.SELECT rating, COUNT(*) FROM film GROUP BY rating;

2.SELECT replacement_cost, COUNT(*) as film_count 
  FROM film 
  GROUP BY replacement_cost 
  HAVING COUNT(*) > 50 
  ORDER BY film_count DESC;
  
3.SELECT store_id, COUNT(*) as customer_count 
  FROM customer 
  GROUP BY store_id;
  
4.SELECT country_id, COUNT(*) as city_count 
  FROM city 
  GROUP BY country_id 
  ORDER BY city_count DESC 
  LIMIT 1;

## License
[MIT](https://choosealicense.com/)