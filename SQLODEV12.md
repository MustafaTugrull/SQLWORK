Aşağıdaki sorgu senaryolarını örnek veri tabanı üzerinden gerçekleştiriniz.

1.Film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?  
2.Film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?  
3.Film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.  
4.Payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.  

1.**SELECT COUNT**(*) **FROM** film   
**WHERE** film.length >    
(**SELECT AVG**(length) **FROM** film)  

2.**SELECT COUNT**(*) **FROM** film  
**WHERE** rental_rate =   
(**SELECT MAX**(rental_rate) **FROM** film)  

3.**SELECT** title **FROM** film  
**WHERE** rental_rate =   
(**SELECT MIN**(rental_rate) **FROM** film)   
**AND** replacement_cost =   
(**SELECT MIN**(replacement_cost) **FROM** film)  

4.**SELECT** customer_id, **COUNT**(customer_id) **FROM** payment  
**GROUP BY** customer_id  
**ORDER BY COUNT**(customer_id) **DESC**  
