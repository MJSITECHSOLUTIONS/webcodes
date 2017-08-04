1.	app/etc /modules/
•	upload xml files – Ecorps_Orderprint.xml
2.	app/code/local
•	upload Ecorps folder – Inside is Orderprint folder.
3.	app/code/local/Mage
•	create Mage folder and create directory “Adminhtml/Block/Sales/Order” under the Mage folder.
•	Copy core file Grid.php and upload changes to this directory.
•	Upload the Printed.php as a renderer.
4.	app/code/core/Mage/Adminhtml/controllers/Sales
•	Upload the OrderController.php to this directory.
5.	app/code/core/Mage/Adminhtml/Controller
•	check Action.php
