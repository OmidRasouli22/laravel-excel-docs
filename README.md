<meta http-equiv="refresh" content="0;url=/3.1/getting-started/" />
I wanted to install the latest version of this package, but it only install version^1.1.0
So I searched a lot in internet and I found this solution useful:
First of all you should uncomment ";extension=gd" in your "php.ini" in "C:\xampp\php" route.
then you should restart your xampp.
then even with this change, if you install this package you got an error.
so what should you do? you should add "maatwebsite/excel": "^3.0" manully in your composer.json file under "require" section.
then run the command: "composer update maatwebsite/excel" 
Enjoy coding! this will work well.
