# PHP_keep_note-webapp-


<h2>The sql commands you have to run on your database:</h2>

<code>
CREATE DATABASE notes;
USE notes;

CREATE TABLE notes (
    sno INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    description TEXT,
    date DATE
);
</code>


