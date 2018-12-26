如果想在自己电脑上运行这个打包的文件，要改的地方：  
1.改数据库密码：\phpStudy\PHPTutorial\WWW\tp5\application\database.php  
2.改数据库密码：\phpStudy\PHPTutorial\WWW\dbfinal\config.ini  
3.改数据库密码：\phpStudy\PHPTutorial\WWW\cx\services.php -143：$con = mysql_connect("localhost","root","root");  
4.改localhost端口：countDown(10,'//localhost:81/tp5/public/');
