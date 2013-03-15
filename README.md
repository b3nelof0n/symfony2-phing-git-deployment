Symfony2 Deploy Script for Phing
=============================

This deploy script will help yout to deploy Symfony2 across multiple maschines.


Usage:
=============================

phing -f deploy.xml start_release -Dhost=www1,www1 -Dno-assets=1 -Dversion=v1.03.13.1


Options:
=============================
- -Dno-assets 		= No assets will generatet (fast)
- -Dversion 		= This tag will deployed
- -Dhost 			= Servername to Deploy ( this will map to the file in /config/hosts/) 

Files:
=============================

- /config/hosts/www1.properties (example file host configuration)

host.servername  		(server hostname)
host.username 			(username)
host.password 			(password)
host.server_deploy_path (Server deploy path)

- /config/git.properties 			(Git configuration file)
- /config/mail.properties 			(Mail configuration file)


question / features:
=============================
ask me if you want!