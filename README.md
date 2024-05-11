# Maker_Checker

CREATE TABLE temp_table (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) NOT NULL, email
VARCHAR(255) NOT NULL, approval _status INT DEFAULT 0);


CREATE TABLE main_table (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) NOT NULL, email
VARCHAR(255) NOT NULL);

CREATE TABLE approval table (id INT AUTO_INCREMENT PRIMARY KEY, temp_table_ id INT NOT NULL, approval status INT NOT NULL);

yeh table hai create ker lena
