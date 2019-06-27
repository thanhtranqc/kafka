# Guideline

- Copy notification-services to /home/SYSVNPORTAL folder
- Change permission :
	+	cd /home/SYSVNPORTAL/notification-services
	+	sudo chmod -R 755 .*
	
- Run kafka-init.sh

- Run notification-init.sh

- Run jenkins job or copy notification-services-1.0.jar to /home/SYSVNPORTAL/notification-services/bin/

- sudo systemctl start notification

	

