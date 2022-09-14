# PlasticCardPrintMachine

Summary of the Project:

I have designed this software for CIVIL Hospital Karachi, where the management introduce Plastic Card for OPD patient. In Plastic Card Patient Information is print and can be use for future visit.

The Computer Operator feed the patien data in PHP-MySQL program, where on submit button I get an xml file where patient data is included. I get this data of FIFO basis and save this data to Microsoft SQL Server database than insert this data to Plastic Card Machine DBase database file, where as data inserted the Plastic Card is printed. Plastic Card Machine is only support DBase databse.

I am using C Shap for code in MS Visual Studio using threading for get data on FIFO basis. 

A SOAP based Webservices, where data receive in xml format, get in my application and save it in Microsoft SQL Server Table, where Patient OPD Card is printing in Plastic Machine.

Steps to Install Software.
--------------------------

Install XP from the CD

1. First Install Windows XP and follow step 2

2. Change computer Name with this p1-8b050d32a27d  name while installation XP  

3. After Installation Windows XP, change the TCP/ip 
	172.20.34.5
	255.255.255.0
	172.20.34.250

4. Install IIS from WIndows XP CD

---------------------------------------

Installation From the Setup Folder 

1. Install dot Net Frame Work 
2. Install SQL Server and attache card db from the folder c:\sqldb
3. Install Crystal Report Viewer
4. Install VFPOLEDBSetup

-----------------------------------------------------

Copy All folder from C Drive folder to C drive root

1. In IIS creat Virtual Director and named it ASP

2. In CARDWIN folder right click on card.exe file and send to Desktop Create Shortcut
3. In c drive browse CP folder...cp\CardPrint\CardPrint\bin\Debug\CardPrint.exe and send to Desktop Create Shortcut
4. IN c drive browse WindowCard folder...WindowCard\WindowCard\WindowCard\bin\Debug\WindowCard.exe and send to Desktop Create Shortcut

---------------------------------------------

