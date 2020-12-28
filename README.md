# spring-jasper-report
How to generate dynamic report using spring boot and jasper

*JasperSoft Studio tool*
Link : https://community.jaspersoft.com/project/jaspersoft-studio/releases

# DB


create database jasperpoc;
create user jasperpoc;
GRANT ALL PRIVILEGES ON jasperpoc.* TO 'jasperpoc'@'%' IDENTIFIED BY 'snick2978@limberness';
flush privileges;

mysql -ujasperpoc -p -P33066 -h127.0.0.1 -Djasperpoc
snick2978@limberness
