25 Aug 2022
===========

Create a self signed certificate and use it in Nginx on Windows 10 to proxy apps
---------------------------------------

Step 1: Create a Self Signed Certificate
	Check https://github.com/PrasunThapliyal/SignalRDemo

Step 2: Configure Nginx
	Create nginx.conf. Nginx requires logs and temp folders, so create in the same directory as nginx.conf and add mime.types file
	
	Test and Run Nginx from Git Bash terminal

	pthapliy@HAW-PTHAPLIY-01 MINGW64 ~
	$ /c/Prasun/Software/NGINX/nginx-1.15.6/nginx.exe -p "/c/GIT/MyPersonal/NginxSSL/" -c "nginx.conf" -T

	pthapliy@HAW-PTHAPLIY-01 MINGW64 ~
	$ /c/Prasun/Software/NGINX/nginx-1.15.6/nginx.exe -p "/c/GIT/MyPersonal/NginxSSL/" -c "nginx.conf"

Step 3: On the browser, go to https://localhost
---------------------------------------
