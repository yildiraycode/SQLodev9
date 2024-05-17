# SQLodev9
## sql sorguları patika odev 9 <br/>
**Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.**<br/>
1.city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.<br/><br/>
SELECT city.city, country.country<br/>
FROM country<br/>
INNER JOIN city ON city.country_id = country.country_id;<br/><br/><br/>
2.customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.<br/><br/>
SELECT customer.first_name, customer.last_name, payment.payment_id<br/>
FROM customer<br/>
INNER JOIN payment ON customer.customer_id = payment.customer_id;<br/><br/><br/>
3.customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.<br/><br/>
SELECT customer.first_name, customer.last_name, rental.rental_id<br/>
FROM customer<br/>
INNER JOIN rental ON customer.customer_id = rental.customer_id;<br/><br/>

