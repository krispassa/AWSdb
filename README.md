# AWSdb
Steps
1. Login to Amazon AWS cloud with your Amazon account.
2. Click on Service tab, then click on RDS on database sections
3. Click on launch DB instance 
4. Choose MySql engine option.
5. Next, choose dev mysql option. dev = development 
6. Give your DB name, username, and password.
7. Hit create. It may take a couple of minute to create the DB
8. downnload sequel pro (mac) or any dbms and test the connection
8.a: Need Host url, username, password,port, and database
9. if connection throws error after putting valid login credential. Go to settings and change inboud connection to public IP instead of custom IP. By default, Amazon assign Custom IP.
