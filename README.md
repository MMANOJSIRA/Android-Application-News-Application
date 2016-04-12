First..I used my own personal domain as PhpMyAdmin..

www.takenmind.com/spider/index.php is used to enter news into the database

www.takenmind.com/spider/connection2.php is used to create connection to the database

www.takenmind.com/spider/jsonarray.php is used to convert the mysql object to json array

The principle I had used is 

1. convert sql to json
2. parse json in android app
3. store the accessed info locally in android app's database(to access the news offline and can be synced with centralised database)
4. Sync the server db and local db in background to check for updates
5. In case of updates, send  a push notification.

The app is incomplete. But can be completed with some more time. 

PS. Donot want to give excuses. but access speed to my domain was poor in NITT wifi and caused technical delays in creating json.


