# Wiki Installation:
1.	Copy wiki_site.yml file to your server
2.	docker-compose -f wiki_site.yml up
3.	extract backupdb.tar to /home/docker_data/sqldata
4.	extract backup.tar to /home/docker_data/joomladata
5.	groupadd www-data -g 33
6.	chown -R 33:33 /home/docker_data/joomladata/html
