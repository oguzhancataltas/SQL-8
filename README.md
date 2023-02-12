# SQL-8

1. CREATE TABLE employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
2. 
* insert into employee (name, birthday, email) values ('Chauncey', null, 'cperrycost0@bbc.co.uk');
* insert into employee (name, birthday, email) values ('Ray', null, 'rcawthery1@samsung.com');
* insert into employee (name, birthday, email) values ('Rey', '1986-10-22', 'rbalcombe2@oaic.gov.au');
* insert into employee (name, birthday, email) values ('Abigail', '2001-06-25', 'amouland3@google.co.jp');
* insert into employee (name, birthday, email) values ('Shea', '2006-03-08', 'sthistleton4@dagondesign.com');
* insert into employee (name, birthday, email) values ('Rutger', '2008-04-17', 'rmcalpin5@nbcnews.com');
* insert into employee (name, birthday, email) values ('Ricky', '2008-06-08', 'rourry6@moonfruit.com');
* insert into employee (name, birthday, email) values ('Karoly', null, 'ksinton7@google.de');
* insert into employee (name, birthday, email) values ('Dill', null, 'dbowle8@instagram.com');
* insert into employee (name, birthday, email) values ('Ardenia', '1994-07-05', 'asomerled9@tripadvisor.com');
* insert into employee (name, birthday, email) values ('Kiah', null, 'klystona@tinypic.com');
* insert into employee (name, birthday, email) values ('Darcey', '2018-12-11', 'dlongeab@histats.com');
* insert into employee (name, birthday, email) values ('Marlo', '2014-05-21', 'mcoghlanc@marketwatch.com');
* insert into employee (name, birthday, email) values ('Zebadiah', '2012-03-06', 'zmcwatersd@diigo.com');
* insert into employee (name, birthday, email) values ('Marshall', '2004-05-07', 'mjurczike@whitehouse.gov');
* insert into employee (name, birthday, email) values ('Edd', '2001-05-15', 'eanstyf@amazon.com');
* insert into employee (name, birthday, email) values ('Normie', '2006-01-19', 'nwristg@wisc.edu');
* insert into employee (name, birthday, email) values ('Vinita', '1980-07-26', 'veverixh@about.com');
* insert into employee (name, birthday, email) values ('Justine', '1986-08-20', 'jmathelyi@noaa.gov');
* insert into employee (name, birthday, email) values ('Darlleen', '2012-04-27', 'dqusklayj@simplemachines.org');
* insert into employee (name, birthday, email) values ('Kathy', '2016-07-22', 'kranglek@trellian.com');
* insert into employee (name, birthday, email) values ('Evin', null, 'ebuxaml@blogspot.com');
* insert into employee (name, birthday, email) values ('Dot', '1982-07-21', 'dolennachainm@state.tx.us');
* insert into employee (name, birthday, email) values ('Seamus', null, 'sdwinen@ca.gov');
* insert into employee (name, birthday, email) values ('Karilynn', '1993-07-24', 'klimmero@newyorker.com');
* insert into employee (name, birthday, email) values ('Roselin', '1988-01-18', 'rbenbrickp@biglobe.ne.jp');
* insert into employee (name, birthday, email) values ('Ignazio', '2010-01-20', 'icarlowq@psu.edu');
* insert into employee (name, birthday, email) values ('Deny', '1981-08-02', 'dblackadderr@netlog.com');
* insert into employee (name, birthday, email) values ('Magdalene', '1992-05-07', 'mmoyers@google.co.jp');
* insert into employee (name, birthday, email) values ('Nydia', '1991-11-25', 'nsculphert@last.fm');
* insert into employee (name, birthday, email) values ('Britney', '2002-10-04', 'bklosau@bandcamp.com');
* insert into employee (name, birthday, email) values ('Stanford', '1991-11-22', 'ssmartv@un.org');
* insert into employee (name, birthday, email) values ('Osbert', '1995-08-01', 'omehargw@state.tx.us');
* insert into employee (name, birthday, email) values ('Rey', null, 'rcheshirex@sitemeter.com');
* insert into employee (name, birthday, email) values ('Chucho', null, 'cbestey@wunderground.com');
* insert into employee (name, birthday, email) values ('Nollie', '2015-11-06', 'nphillpotz@nationalgeographic.com');
* insert into employee (name, birthday, email) values ('Tomas', '2014-04-20', 'tchapell10@smugmug.com');
* insert into employee (name, birthday, email) values ('Elaine', '1989-04-21', 'egerty11@businesswire.com');
* insert into employee (name, birthday, email) values ('Alexis', '2017-04-11', 'amccaughan12@nsw.gov.au');
* insert into employee (name, birthday, email) values ('Mozes', '2008-11-28', 'mlaughlin13@google.ca');
* insert into employee (name, birthday, email) values ('Alejandrina', '1995-12-17', 'agert14@scribd.com');
* insert into employee (name, birthday, email) values ('Geoffry', null, 'gmastrantone15@drupal.org');
* insert into employee (name, birthday, email) values ('Maggie', '1987-03-26', 'mwillan16@sun.com');
* insert into employee (name, birthday, email) values ('Emily', '1993-10-08', 'elaidlaw17@seesaa.net');
* insert into employee (name, birthday, email) values ('Velvet', '1997-03-27', 'vstair18@google.com.au');
* insert into employee (name, birthday, email) values ('Rossie', '2002-07-23', 'rmapes19@spotify.com');
* insert into employee (name, birthday, email) values ('Allina', '1992-06-28', 'alerwill1a@yellowpages.com');
* insert into employee (name, birthday, email) values ('Travis', '2015-02-16', 'tealam1b@ox.ac.uk');
* insert into employee (name, birthday, email) values ('Janeen', '2004-03-28', 'jfellows1c@artisteer.com');
* insert into employee (name, birthday, email) values ('Reinaldos', '2009-07-28', 'rribchester1d@last.fm');

3. 
* UPDATE employee
SET name = 'Tom'
WHERE id = 2;
* UPDATE employee
SET name = 'Jon'
WHERE id = 5;
* UPDATE employee
SET email = 'rutger@exam.com'
WHERE id = 6;
* UPDATE employee
SET birthday = '1999-10-22'
WHERE name = 'Rey';
* UPDATE employee
SET birthday = '1999-10-22'
WHERE email = 'dlongeab@histats.com';

4. 
* DELETE FROM employee
WHERE id = 13;
* DELETE FROM employee
WHERE name = 'Rey';
* DELETE FROM employee
WHERE id = 44;
* DELETE FROM employee
WHERE id > 47;
* DELETE FROM employee
WHERE name = 'Rutger'
RETURNING *;
