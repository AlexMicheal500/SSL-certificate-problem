# SSL-certificate-problem when cloning on cloud9 from gitlab
ERROR: fatal: unable to access '
https://openpj.ddns.net/infrastructure/web-app-tp.git/
': SSL certificate problem: certificate has expired . Write a command how to solve using git

Solution:
Run the following command:
git config --global http.sslVerify false

