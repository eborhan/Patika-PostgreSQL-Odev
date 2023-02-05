
**1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.**

```sql
CREATE TABLE employee (
	id INTEGER PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```

**2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.**

```sql
insert into employee (id, name, birthday, email) values (1, 'Rebeca Dawtre', '1987-02-24', 'rdawtre0@tripod.com');
insert into employee (id, name, birthday, email) values (2, 'Zoe Connow', '1976-01-08', 'zconnow1@soundcloud.com');
insert into employee (id, name, birthday, email) values (3, 'Norby Fasham', '1930-11-28', 'nfasham2@e-recht24.de');
insert into employee (id, name, birthday, email) values (4, 'Guillermo Hedde', '1997-11-30', 'ghedde3@com.com');
insert into employee (id, name, birthday, email) values (5, 'Ricky Veivers', '1960-08-23', 'rveivers4@census.gov');
insert into employee (id, name, birthday, email) values (6, 'Marlyn Jeanenet', '1926-10-30', 'mjeanenet5@nhs.uk');
insert into employee (id, name, birthday, email) values (7, 'Hendrik Perazzo', '1970-12-16', 'hperazzo6@yahoo.com');
insert into employee (id, name, birthday, email) values (8, 'Roth Blinckhorne', '1914-03-24', 'rblinckhorne7@bing.com');
insert into employee (id, name, birthday, email) values (9, 'Cybil Tarbert', '1940-11-29', 'ctarbert8@digg.com');
insert into employee (id, name, birthday, email) values (10, 'Dylan Crighten', '1978-10-21', 'dcrighten9@joomla.org');
insert into employee (id, name, birthday, email) values (11, 'Harriet Maxwaile', '1904-05-21', 'hmaxwailea@dedecms.com');
insert into employee (id, name, birthday, email) values (12, 'Ramsey Ussher', '1981-02-27', 'russherb@csmonitor.com');
insert into employee (id, name, birthday, email) values (13, 'Lorry Caban', '1931-03-17', 'lcabanc@posterous.com');
insert into employee (id, name, birthday, email) values (14, 'Sheeree Fisbey', '1919-12-01', 'sfisbeyd@edublogs.org');
insert into employee (id, name, birthday, email) values (15, 'Minny Walsh', '1915-05-23', 'mwalshe@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (16, 'Pauline Beekman', '1923-08-29', 'pbeekmanf@spotify.com');
insert into employee (id, name, birthday, email) values (17, 'Monti Cuckoo', '1958-02-16', 'mcuckoog@alexa.com');
insert into employee (id, name, birthday, email) values (18, 'Marcello Liccardo', '1928-03-27', 'mliccardoh@cmu.edu');
insert into employee (id, name, birthday, email) values (19, 'Kincaid Cowins', '2004-10-17', 'kcowinsi@imgur.com');
insert into employee (id, name, birthday, email) values (20, 'Cary Tapenden', '1966-07-11', 'ctapendenj@usa.gov');
insert into employee (id, name, birthday, email) values (21, 'Gail Tackley', '1979-08-27', 'gtackleyk@sitemeter.com');
insert into employee (id, name, birthday, email) values (22, 'Iorgo Nosworthy', '1949-06-08', 'inosworthyl@php.net');
insert into employee (id, name, birthday, email) values (23, 'Lucilia Churchard', '1900-12-03', 'lchurchardm@domainmarket.com');
insert into employee (id, name, birthday, email) values (24, 'Leticia Guterson', '1946-01-08', 'lgutersonn@narod.ru');
insert into employee (id, name, birthday, email) values (25, 'Milli Stein', '1985-05-22', 'msteino@hubpages.com');
insert into employee (id, name, birthday, email) values (26, 'Martha Nucciotti', '1988-02-01', 'mnucciottip@theglobeandmail.com');
insert into employee (id, name, birthday, email) values (27, 'Callean Eastes', '1946-01-10', 'ceastesq@nature.com');
insert into employee (id, name, birthday, email) values (28, 'Melli Bladesmith', '1914-01-08', 'mbladesmithr@canalblog.com');
insert into employee (id, name, birthday, email) values (29, 'Ardis Sandercock', '1948-06-03', 'asandercocks@about.me');
insert into employee (id, name, birthday, email) values (30, 'Persis Snoding', '1973-12-18', 'psnodingt@techcrunch.com');
insert into employee (id, name, birthday, email) values (31, 'Forbes Bootland', '1914-10-15', 'fbootlandu@mayoclinic.com');
insert into employee (id, name, birthday, email) values (32, 'Tess Zambon', '1953-09-07', 'tzambonv@w3.org');
insert into employee (id, name, birthday, email) values (33, 'Mattheus Sidwell', '1925-04-21', 'msidwellw@purevolume.com');
insert into employee (id, name, birthday, email) values (34, 'Ede Ottey', '1950-04-06', 'eotteyx@apple.com');
insert into employee (id, name, birthday, email) values (35, 'Vale Dockwray', '1960-09-29', 'vdockwrayy@yahoo.com');
insert into employee (id, name, birthday, email) values (36, 'Serene Arnoud', '1949-02-21', 'sarnoudz@addthis.com');
insert into employee (id, name, birthday, email) values (37, 'Roger Mulmuray', '1903-02-20', 'rmulmuray10@cam.ac.uk');
insert into employee (id, name, birthday, email) values (38, 'Roldan Farfull', null, null);
insert into employee (id, name, birthday, email) values (39, 'Gabbi Thormann', '1932-02-26', 'gthormann12@tinypic.com');
insert into employee (id, name, birthday, email) values (40, 'Dana Newark', '1922-01-07', 'dnewark13@google.com');
insert into employee (id, name, birthday, email) values (41, 'Jameson Blackledge', '1992-06-15', 'jblackledge14@naver.com');
insert into employee (id, name, birthday, email) values (42, 'Bel Dowyer', '1917-08-07', 'bdowyer15@google.ca');
insert into employee (id, name, birthday, email) values (43, 'Flin Ayton', '2002-10-13', 'fayton16@unicef.org');
insert into employee (id, name, birthday, email) values (44, 'Krystal Pinder', '1972-02-08', 'kpinder17@bandcamp.com');
insert into employee (id, name, birthday, email) values (45, 'Gherardo Cheney', '1907-04-20', 'gcheney18@examiner.com');
insert into employee (id, name, birthday, email) values (46, 'Carolynn Charte', '2003-11-17', 'ccharte19@twitpic.com');
insert into employee (id, name, birthday, email) values (47, 'Clementius Seacombe', '1924-08-04', 'cseacombe1a@aboutads.info');
insert into employee (id, name, birthday, email) values (48, 'Sissy Edgerley', '1904-12-12', 'sedgerley1b@arstechnica.com');
insert into employee (id, name, birthday, email) values (49, 'Lenci O''Bruen', '1911-11-29', 'lobruen1c@ebay.co.uk');
insert into employee (id, name, birthday, email) values (50, 'Jefferson Weathey', '1984-07-16', 'jweathey1d@blogspot.com');
```

**3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.**

```sql
UPDATE employee
SET name = 'Ersan Borhan'
WHERE id = 1
RETURNING *;

UPDATE employee
SET email = 'info@test.com'
WHERE name LIKE 'A%'
RETURNING *;

UPDATE employee
SET email = 'ersan@test.com'
WHERE name = 'Ersan Borhan'
RETURNING *;

UPDATE employee
SET birtday = '2002-06-17'
WHERE name LIKE = 'B%'
RETURNING *;

UPDATE employee
SET birtday = '2005-01-01'
WHERE name LIKE = 'K%'
RETURNING *;


```

**4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.**

```sql
DELETE FROM employee
WHERE id = 7;

DELETE FROM employee
WHERE email = 'ersan@test.com'
RETURNING *;

DELETE FROM employee
WHERE name ILIKE 'a%'
RETURNING *;

DELETE FROM employee
WHERE birthday = '1930-11-28'
RETURNING *;

DELETE FROM employee
WHERE id BETWEEN 3 AND 25
RETURNING *;
```

