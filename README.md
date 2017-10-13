# DINOKIKI
Available at http://dinokiki.com

## What is Dinokiki? 
Dinokiki is an interactive website with one purpose: have fun!!!
Turn your audio on and click on the Dinosaur and get ready!
Everytime you click over him a jQuery function randomly calls one of the kikis.

## How was it developed? 
It uses HTML5, [Sass](http://sass-lang.com/), [jQuery](https://jquery.com/), PHP ([CodeIgniter](https://codeigniter.com/)) and MySQL. It's responsive.
Dinokiki changes its style for some special dates such as halloween, christmas and his birthday.

## Will Dinokiki always be the same? 
No. It changes constantly and you can help if you want :D

## Can I help?
Sure! If you have any idea, want to solve an issue, send a kiki or just want to say hi send me a message. Don't forget to follow @mrdinokiki on [twitter](https://twitter.com/mrdinokiki), [facebook](https://facebook.com/mrdinokiki) and [instagram](https://instagram.com/mrdinokiki) for updates!

## How I can run Dinokiki on my computer?
To run Dinokiki in your machine you need to have a local PHP server.
If you want to change the CSS files you'll need to have [Sass](http://sass-lang.com/) installed and compile it.

You have to setup a few things on CodeIgniter. 
1. At application/config/config.php you have to change the base_url to the url you'll use on your machine.
2. At application/config/database.php you have to update the database info with your database.
ps: if you want to have exactly the same database content as the real website, download the [sql file](http://giuliacardieri.com/dinokiki.sql).

### Run with docker
If you want run quickly, will can use a docker.
run `docker-compose up -d`.
wait a minute ;) and
access [http://localhost:8081](http://localhost:8081)
