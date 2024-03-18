<h1>SQL Database learning </h1>

<h2>Description</h2>
In this project we are going to Build an SQL database from scratch and write Custom SQL queries.  Mainly for a pizza shop bc its one of my addictions HA
<br />


<h2>Languages and Utilities Used</h2>

- <b>Database mySQL</b>
- <b>Oracle VM virtualbox</b>

<h2>Environments Used</h2>

- <b>Ubuntu linux latest Version</b>

<h2>Skills:</h2>    

- <b>SQL database design and creation</b>
- <b>Relational databases</b>

- <b>Download Ubuntu: https://ubuntu.com/download/desktop </b>
- <b>Download Oracle VM box: https://www.virtualbox.org/wiki/Downloads </b>

<h2>Walk Through:</h2>

<p>FIrst Launch your Ubuntu VM and launch your Terminal to update if needed "sudo apt update" and install mysql "sudo apt install mysql-server -y" After the install in completed 
Type in the command sudo systemctl status mysql to check the program is running properly."sudo mysql" and you are in to start making a database</p>
<img src="https://imgur.com/XO9YLLt.gif"/>
<p> More commonly not on a local server you will see something more along the lines of "mysql -u(username) -h(host/remote server) -p(port) -p(password)"</p>

<p> Now to create a database simply " create database (Name_here);". SHow databases; to see that is was created and enter into that database to make changes by Typing "Use (databse name);"
"create Table (table_name) (" to you guessed it.. create a table within this database HA. We use "(" at the end bc we need to create columns and rows for the creation. Otherwise it wont create the table. I HIGHLY recommend pre planning out your Database layouts and formats in something like excel before hand so you know what type of tables, rows, and columns of information you will be creating. This way it will save you time and a headache later on. PLANNING is one of the most essential ideals in creating a database that is sustainable long term. Here is an example of setting up columns and their datatypes for each section!</p>
<img src="https://imgur.com/yH4xRNN.gif"/>

<p>THis shows the columns name the type of data along with the allowable amount of char () for each to more develop our schema. Now we get to work on creating rows HELL YEAHH :) This shows how we would insert into the specific table with the correlating data and then how we would view that data in the table VIA a Select statement. </p>
<img src="https://imgur.com/8GaDx2j.gif"/>

<p>Should you need to delete anything from a table you have made simply use "delete from (table name) where (parameters) ex: where id = 4;</p>
<img src="https://imgur.com/y9i4K3S.gif"/>

<p> Or if you simply wish to edit one value in a row use" update (table name) set (specific column) = (paramaters) for ex: set sauce = ranch where name = "Ark";
That will change so now Ark wants ranch instead of tomato sauce. Will add more Later to this project in terms of Creating relational databases and Imnporting data into a BI for better data analysis. Also Boolean values (alter (what you want to alter) add (name) (data type); 1= true 0 = false and how to organize selected data (asc,Decs etc..) </p>

TO BE CONTINUED!!
