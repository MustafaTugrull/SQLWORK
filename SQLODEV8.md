1.Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.  
2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.  
3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.  
4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.  

<details>
  <summary> CREATE TABLE </summary> 
CREATE TABLE employee (
	id SERIAL,
    name VARCHAR(50) ,
    birthday DATE ,
    email VARCHAR(50)
) 
</details>

<details> 
  <summary>Mockaroo Servisi SQL kodları</summary>
  
insert into employee (name, birthday, email) values ('Lonna', '1995-09-03', 'ldyzart0@jiathis.com');  
insert into employee (name, birthday, email) values ('Barris', '1985-04-15', 'bdonson1@bandcamp.com');  
insert into employee (name, birthday, email) values ('Amandy', '1978-06-01', 'aveazey2@kickstarter.com');  
insert into employee (name, birthday, email) values ('Ezmeralda', '1970-12-04', 'esummersby3@chron.com');  
insert into employee (name, birthday, email) values ('Bertina', '2000-11-30', 'bewell4@springer.com');  
insert into employee (name, birthday, email) values ('Flory', '1997-11-23', 'fhawkwood5@google.de');  
insert into employee (name, birthday, email) values ('Klaus', '2002-12-01', 'kstorkes6@hud.gov');  
insert into employee (name, birthday, email) values ('Wyndham', '1992-12-17', 'wrebbeck7@reverbnation.com');  
insert into employee (name, birthday, email) values ('Marinna', '1957-09-14', 'mpurchall8@xing.com');  
insert into employee (name, birthday, email) values ('Gonzalo', '2001-07-23', 'gbassil9@gizmodo.com');  
insert into employee (name, birthday, email) values ('Dicky', '1959-12-18', 'dkaysora@fotki.com');  
insert into employee (name, birthday, email) values ('Amerigo', '2016-04-09', 'abathersbyb@ted.com');  
insert into employee (name, birthday, email) values ('Alfons', '1956-03-18', 'apolkinhornc@yellowpages.com');  
insert into employee (name, birthday, email) values ('Inness', '1959-11-18', 'igaskinsd@tripadvisor.com');  
insert into employee (name, birthday, email) values ('Junette', '1993-05-18', 'jmccollume@stanford.edu');  
insert into employee (name, birthday, email) values ('Laney', '1992-12-29', 'lcorneljesf@fotki.com');  
insert into employee (name, birthday, email) values ('Sheeree', '1984-04-05', 'spregelg@instagram.com');  
insert into employee (name, birthday, email) values ('Isadora', '1985-07-10', 'ifedorskih@ezinearticles.com');  
insert into employee (name, birthday, email) values ('Forbes', '1984-06-11', 'fmathewi@un.org');  
insert into employee (name, birthday, email) values ('Malachi', '2009-12-07', 'mwildishj@independent.co.uk');  
insert into employee (name, birthday, email) values ('Trev', '1965-01-08', 'teveringhamk@zdnet.com');  
insert into employee (name, birthday, email) values ('Maryellen', '1994-10-10', 'mclementsl@t.co');  
insert into employee (name, birthday, email) values ('Hadrian', '1984-09-09', 'hsainsburybrownm@miitbeian.gov.cn');  
insert into employee (name, birthday, email) values ('Ellynn', '1984-03-01', 'esjostromn@mayoclinic.com');  
insert into employee (name, birthday, email) values ('Meriel', '1998-06-27', 'mpietznero@comcast.net');  
insert into employee (name, birthday, email) values ('Lynnea', '1981-05-17', 'lgumbp@technorati.com');  
insert into employee (name, birthday, email) values ('Janet', '1953-09-07', 'jfosberryq@technorati.com');  
insert into employee (name, birthday, email) values ('Benjamin', '1962-02-27', 'bwolferr@paypal.com');  
insert into employee (name, birthday, email) values ('Candide', '1958-07-30', 'cbebiss@whitehouse.gov');  
insert into employee (name, birthday, email) values ('Deva', '1968-03-16', 'dholberryt@livejournal.com');  
insert into employee (name, birthday, email) values ('Hiram', '2015-09-21', 'hfechnieu@dmoz.org');  
insert into employee (name, birthday, email) values ('Xaviera', '2009-07-21', 'xgraeberv@msn.com');  
insert into employee (name, birthday, email) values ('Norean', '2005-11-09', 'nsturridgew@istockphoto.com');  
insert into employee (name, birthday, email) values ('Bertram', '1974-02-20', 'bmatyushkinx@comcast.net');  
insert into employee (name, birthday, email) values ('Thomas', '1953-01-28', 'tmckintoshy@hc360.com');  
insert into employee (name, birthday, email) values ('Jeno', '1979-11-17', 'jevangelinosz@lycos.com');  
insert into employee (name, birthday, email) values ('Putnem', '1958-08-28', 'pcollumbine10@biblegateway.com');  
insert into employee (name, birthday, email) values ('Nickola', '2011-12-09', 'njohannesson11@twitter.com');  
insert into employee (name, birthday, email) values ('Tallia', '1993-10-05', 'tverring12@youtube.com');  
insert into employee (name, birthday, email) values ('Marcile', '1967-10-10', 'mtexton13@google.fr');  
insert into employee (name, birthday, email) values ('Fons', '1998-01-17', 'fduffin14@google.co.jp');  
insert into employee (name, birthday, email) values ('Darb', '2005-04-06', 'docahey15@delicious.com');  
insert into employee (name, birthday, email) values ('Becca', '1956-05-23', 'bwyman16@gizmodo.com');  
insert into employee (name, birthday, email) values ('Christan', '1995-03-29', 'cjean17@sina.com.cn');  
insert into employee (name, birthday, email) values ('Francklin', '1960-05-30', 'fcrowd18@globo.com');  
insert into employee (name, birthday, email) values ('Jobina', '2004-08-10', 'jfido19@cisco.com');  
insert into employee (name, birthday, email) values ('Correna', '1998-08-25', 'cbonnick1a@pcworld.com');  
insert into employee (name, birthday, email) values ('Cybil', '1966-02-14', 'cshailer1b@merriam-webster.com');  
insert into employee (name, birthday, email) values ('Lorna', '1991-10-25', 'lbaudesson1c@devhub.com');  
insert into employee (name, birthday, email) values ('Carole', '1963-08-31', 'clangstone1d@prweb.com');  
</details>

<details> <summary> UPDATE İŞLEMLERİ   </summary>
<details> <summary> UPDATE 1 </summary>UPDATE employee
SET name = 'özgür',
birthday = '1997-02-24',
email = 'ozguner00@gmail.com'
WHERE id = 1 </details>

<details> <summary> UPDATE 2 </summary> UPDATE employee
SET name = 'özgür2',
birthday = '1997-02-24',
email = 'ozguner00@gmail.com'
WHERE email = 'jmccollume@stanford.edu' </details>
<details> <summary> UPDATE 3 </summary> UPDATE employee
SET name = 'özgür3',
birthday = '1997-02-24',
email = 'ozguner00@gmail.com'
WHERE birthday = '1959-11-18' </details>
<details> <summary> UPDATE 4 </summary>  </details>
<details> <summary> UPDATE 5 </summary>  </details> 
</details>

<details> <summary> DELETE İŞLEMLERİ </summary>  
<details> <summary> DELETE 1 </summary>DELETE FROM employee
WHERE id = 19
</details>

<details> <summary> DELETE 2 </summary> DELETE FROM employee
WHERE name = 'Carole' </details>
<details> <summary> DELETE 3 </summary> DELETE FROM employee
WHERE email = 'lbaudesson1c@devhub.com' </details>
<details> <summary> DELETE 4 </summary>  </details>
<details> <summary> DELETE 5 </summary>  </details> 
</details>
