# Instagram-DB-Clone
It's a simplified version of Instagram's database. Also, I insert tons of data and find ways to manipulate with them.  
## DataBase clone.
It's a simplified version of Instagram database. In the IG_clone.sql, I use 6 entities(tables) to show the key relationship between Instagram's database. It's a simplified one, it's clear that it's much simplier than the real database of Instagram.   
It's aimed at helping understand the relationship between different table and how can we manipulate the data.
Personally, I implemented it on amazon's AWS cloud 9, which would make it much easier to use mysql if you are not familiar with it.
The command to use mysql in cloud 9 looks like this:

$ mysql-ctl start
$ mysql-ctl cli
$ mysql-ctl stop

After starting mysql, use this command to load the file:

$ source (path)/DB_clone.sql
