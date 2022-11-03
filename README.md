# SWD105-Database-Lesson1-MySql

## Getting Started with MySQL - Install on Windows OS

Overview: in this lesson, you will learn step by step how to install MySQL on the Windows platform using the MySQL Installer. After the lesson, you will have a MySQL server and its tools up and running on your system for learning and practicing.


### Download MySQL Installer

If you want to install MySQL on the Windows environment, using **MySQL installer** is the easiest way. MySQL installer provides you with an easy-to-use wizard that helps you to install MySQL with the following components:

  - MySQL Server
  - All Available Connectors
  - MySQL Workbench with Sample Data Models
  - MySQL Notifier
  - Tools for Excel and Microsoft Visual Studio
  - MySQL Sample Databases
  - MySQL Documentation

To download ***MySQL installer***, go to the following link http://dev.mysql.com/downloads/installer/.  There are two installer files:

  - If you are connecting to the internet while installing MySQL, you can choose the online installation version  `mysql-installer-web-community-<version>.exe `.
  - In case you want to install MySQL offline, you can download the  `mysql-installer-community-<version>.exe`  file.

### Install MySQL via MySQL Installer

To install MySQL using the MySQL installer, double-click on the MySQL installer file and follow the steps below:

  * Install MySQL Step 1
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-1.png)
 

  * Install MySQL Step 2 - Welcome Screen
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-2.png)


  * Install MySQL Step 3 - Download the latest MySQL products
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-3.png)


  * Install MySQL Step 4
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-4.png)


  * Install MySQL Step 5 – Choosing a Setup Type: there are several setup types available. Choose the Full option to install all MySQL products and features.
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-5.png)
  

  * Install MYSQL Step 6 - Checking Requirements

  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-6.png)


  * Install MySQL Step 7 – Installation Progress: MySQL Installer downloads all selected products. It will take a while, depending on which products you selected and the speed of your internet connection.
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-7.png)

    * Installation Progress - Downloading Products in Progress
  
     ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-7-process.png)
     
    * Install MySQL Step 7 – Installation Progress: Complete Downloading. Click the Next button to continue…
  
     ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-7-done.png)


  * Install MySQL Step 8 – Configuration Overview. Click the Next button to configure MySQL Database Server
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-8.png)
  

   * Install MySQL Step 8.1 – MySQL Server Configuration: choose Config Type and MySQL port (3006 by default) and click Next button to continue.
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-9.png)

      * MySQL Server Configuration: choose a password for the root account. Please note the password download and keep it securely if you are installing MySQL database server on a production server. If you want to add a more MySQL user, you can do it in this step.
  
      ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-10.png)


      * MySQL Server Configuration: choose Windows service details including Windows Service Name and account type, then click Next button to continue.
  
      ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-11.png)


      * MySQL Server Configuration – In Progress: MySQL Installer is configuring MySQL database server. Wait until it is done and click the Next button to continue.
  
     ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-12.png)


      * MySQL Server Configuration – Done. Click the Next button to continue.
  
     ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-13-done.png)


  * Install MySQL Step 8.2 – Configuration Overview: MySQL Installer installs sample databases and sample models.
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-13.png)


  * Install MySQL Step 9 – Installation Completes: the installation completes. Click the Finish button to close the installation wizard and launch the MySQL Workbench.
  
  ![](https://www.mysqltutorial.org//wp-content/uploads/2013/05/install-mysql-step-14.png)

In this lesson, you learned how to install MySQL on your Windows system using the MySQL installer.

With that, MySQL is now installed. If you set MySQL as a service, then Windows will automatically start the MySQL server every time you restart the system. This process also installs the MySQL Installer application on the localhost, which can later be used to upgrade or reconfigure the MySQL server. In addition, if you installed MySQL Workbench on your system, you might consider using it to check your new MySQL server connection. By default, the program automatically runs after installing MySQL. 

NOTE: Even though MySQL for Windows is available in several distribution formats, it is still recommended to use MySQL Installer. Since it contains more features and MySQL products than the older MSI, it is easier to use than the compressed file, and you do not need any additional tools to get MySQL running. MySQL Installer automatically installs MySQL Server as well as creates an options file, starts the server, and enables you to create various user accounts. It also includes MySQL Workbench, MySQL for Visual Studio and can be used to upgrade all the above-mentioned products in the future (https://dev.mysql.com/doc/mysql-compat-matrix/en/). 

### Install/Setup

During the initial setup process, you are prompted to Choose the MySQL products to be installedd.

A good decision would be to go with the predetermined setup type that suits your setup requirements. By default, both GA and pre-release products are included in the download and installation with the Developer Default, Client only, and Full setup types. You can opt for the Only install GA products option to limit the product set to include GA products only when using these setup types. Choosing one of the following setup types regulates the initial installation only and does not limit your ability to install or update MySQL the following products for Windows later on: • 

- MySQL Shell 
- MySQL Router  
- MySQL Workbench 
- MySQL for Visual Studio 
- MySQL Connectors (for .NET/ Python/ ODBC/ Java/ C++) 
- MySQL Documentation 
- MySQL Samples and Examples 



### MySQL Installer 

MySQL Installer dashboard is the default setting that you see once you start MySQL Installer after the initial setup is complete. 

  - If you closed MySQL Installer before the setup was over, MySQL Installer will go on with it before it displays the dashboard. 
  - MySQL Installer dashboard Elements have a variety of actions that apply to installed products or products displayed in the catalog. 
  - To commence the following operations, you should click on the operation link and then select the product or products to manage. 
    * The operation “Add” proceeds to the Select Products page. 
    * From there, you can regulate the filter, choose one or more products to download, and start the installation. 
    * Here, you can use the directional arrows to move each product from the Available Products column to the Products To Be Installed column. 
    * To enable the Product Features page where you can customize features, click the related check box. 


### Start Installer

Start MySQL Installer from the search menu. 
  - Once the MySQL Installer dashboard opens, just click the MySQL Installer About icon. 
  - The version number would be displayed above the Back button. 

## Install on MacOs

### Installing MySQL on macOS Using Native Packages 

The Native package is placed inside a disk image file (.dmg) that you first should organize by double-clicking its icon in the Finder. 

  - It should then mount the image and display its contents. 
  - Before starting the installation, you would need to stop running MySQL server instances by using either the MySQL Manager Application, the preference pane, or mysqladmin shutdown variable in the command line. 

To install MySQL using the package installer, you need to first download the disk image (.dmg) file that holds the MySQL package installer. 

  - Then double-click the file to check the disk image and see through its contents. 
  - Doubleclick the MySQL installer package from the disk that is named according to the version of MySQL you have downloaded. 

    * For instance, for MySQL server 8.0.25 it might be named MySQL-8.0.25-macOS-10.13-x86_64.pkg. 
    * The initial wizard introduction screen references the MySQL server version to install. 

Click Continue to begin the installation. 

  - The MySQL community edition will then present a copy of the relevant GNU General Public License. 
  - Click Continue and then Agree to continue. 

From the Installation Type page, you can click Install to start the installation wizard using all defaults, and then click Customize to modify which components to install. 

- However, even if the Change Install Location option is available, the installation location still cannot be changed. 

After that click Install to install MySQL Server. 

After a successful new MySQL Server installation, complete the configuration steps by choosing the default encryption type for passwords, define the root password, and also enable or disable MySQL server at startup. 

- The default MySQL 8.0 password mechanism is caching_sha2_password, and this step permits you to change it to mysql_native_password. 

Most content is described in the surrounding text. To be precise, the installer refers to caching_sha2_password as “Use Strong Password Encryption” and mysql_native_ password as a “Use Legacy Password Encryption.” 

You should also choose a password for the root user and decide whether MySQL Server should start after the configuration step is over. 

A summary is the final stage and references a successful MySQL Server installation. 

- You can now close the wizard. 


# MySQL server is now installed. 
   



