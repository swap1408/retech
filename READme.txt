fsmond is a tool to monitor filesystem when your filesystem gets full then you face lots of problem related to filesystem.
How to manage the filesystem, how to make space in filesystem which files to be move or delete.
This tool helps to manage filesystem to reduce the risk of filesystem to get full.
It has two features 1st one is you can set limits minimum and maximum i.e. when you set min and max limits to some filesystem it monitor that filesystem and when the filesystem reached to max limit it removes most old files present in that directory until it reaches to minimum limit. But if you dont want to delete the files you can move file to another filesystem.
You need to mention target directory of the filesystem. then its automatically moves most old files to target directory.
2nd one if you dont want to move or delete files but you want notification when it reached to limit. Then you need to mention email_id its sends the mail on that mail id when it reached to limits.

All the configuration you will get in below mention files.

Configuration file /etc/fsmond.conf  please read this file carefully before starting service

Service file /etc/init.d/fsmon 

Daemon file /usr/bin/fsmond

How to install tool

run install.sh script 
