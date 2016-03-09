# Install-automatic-MYSQL-all-component-and-configure
The program is used for automatic and very easy install MYSQL database    and do its configuration automatically so that the user does not have to choose    any parameter from the menu or need read help . Only must approve a few (3-4) button's  type    NEXT. All parameters are stored in the config file setup.ini     what can be edit and change by  programmer to adapt it , according to the needs .
MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT
					======================================================

1. **For what objective is the program **
**MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT.exe**?? .
   The program is used for automatic and very easy install MYSQL database
   and do its configuration automatically so that the user does not have to choose
   any parameter from the menu or need read help . Only must approve a few (3-4) button's  type
   NEXT. All parameters are stored in the config file setup.ini 
   what can be edit and change by  programmer to adapt it , according to the needs .

**2. The author of this project.**
   The author of this project MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT
   is a Polish **radio amateur SP9AUV**. This callsign completely identifies a person 
   in the whole world, as there are no other people in the worldwide of that 
   callsign in Ham Radio.

**3. The terms of the license.**
   The project and the program is completely free without any fees. With the use of the 
   entire project should, however, keep the features of copyright, ie callsign SP9AUV 
   when displaying on the screen. When separate use  of the procedures program 
   behavior callsign  SP9AUV is not necessary.
   
**4. Objective of the development of this project**
   MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT.
   Initially, to the radio amateurs I provided all the files that are needed for installation
   MYSQL database and its configuration, along with a detailed description of what needs 
   to be run consecutively and how to configure the database. However, the majority of 
   people could not do this installation, or simply not want to read the extensive help.
   It became clear to me that this mechanism is too complicated.
   True, Microsoft provides software installation for  more
   components for MYSQL. However,  in this method is also too many elements
   to decide and choose to end the successful installation of MySQL.
   So I decided to develop a program MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT,
   which automatically installs itself all the necessary components, without selecting
   any parameter from menu and also configure itself MYSQL ,  for the needs of a specific 
   program, in my case AWARD_SECRETARY. If it will possible the steps installation are hidden from
   user. The program operatesin this way ,  that basically need is a couple of mouse clicks and it is

**5. Files  accompanying the project:**
   5.1. In the catalog MYSQL_INSTAL_WITH_SOURCE    are placed following directories and files
          MYSQL_INSTAL and in directories
			V_5.1 files to install MySQL version 5.1
			V_5.5 files to install MySQL 5.5
			file MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT.exe
				- the same program to perform automatic installation and configuration of 
                                   MySQL database MYSQL
			file of SHOW_CHM_HELP_IN_64BIT_WINDOWS.exe - Auxiliary program to remove 
                          the hassle of display help files .chm
			file Install_MYSQL_dla_informatykow_PL.chm - help for a Polish - extended only 
                            for developer
			file Install_MYSQL_PL.chm - help Polish, reduced for non-technical users
			file Install_MYSQL_for_computer_science_EN.chm - help English - extended only 
                              for developer
			file Install_MYSQL_EN.chm - help English - shortened for non-technical users
			L_1045.dll files and L_1033.dll - dll files for the language English or  Polish
                 ** configuration file setup.ini.** This is a very important file which determines 
                      what components  are to be installed. In it they are also stored configuration 
                       parameters needed for proper  work then   the program utility. It is possible to 
                      install and configure up to 6 six   MYSQL components. At the present time , 
                          the configuration file may install MySQL : 
                      in version 5.1 or 5.5.
               Configuration file setup.ini is the file same commenting. Programmer after looking
               this file , will be knows what data must  change , to accommodate the setup.ini to
              your database system MySQL.
         **SOURCE**     -  source in a Delphi for program MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT

**6. Using external programs to install and configure the database automatically.**
   At this moment this program is used to automatic installation database:
		Msiexec.exe - basic program for component installation MYSQL, he has options:
			-i install
			-q quite perform operations quietly, ie not-display
			-l create a log of operations was was do 
		- MySQLInstanceConfig.exe - a collection is created only after the successful 
                                   installation and MYSQL
		  It is used to configure the database 
			- Setting up an account and password for the main root
			- Connection configuration for ODBC Driver
			- No port is usually 3306
			- Name server as domain = localhost
			- Name =           	Your choice
			- Pasword user = 	Your choice
			- DATABAE NAME = 	Your choice
		- Mysql.exe - a file is created after successful installation MYSQL
				and is used to create account and password for user for the application program, and
				setting privileges for that user
		- Net.exe - used to run networks to work with MYSQL
		
**7. Use the program to automatic and very easy install MYSQL database.**
   After designing MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT
   It became clear to me that the program can be used for very easy installation database
   MYSQL also by other than amateur radio users.
   Also, by "Mrs. Zosia from the accounting department what does not know anything 
   about science."   The programmer must only edit file setup.ini
   the specific needs for  another company and another user.
   In this way there is no need to travel to another company, and the 
   user group of our finanse applications can be extended to users around the world .
   The program works in English or Polish, depending on what is a Windows environment.
   If the parameters in setup.ini not enough, the programmer can make changes
   in the program MYSQL_INSTALL_AUTOMATIC_ALL_COMPONENT_AND_CONFIGURE_IT
   i.e. in a sources in Delphi .
   
**8. Where can you get the project?**
     
   http://sp9auv.com/EN/index.html?instalation_database_mysql_for_computer_science.php
    
  This is the full version with sources in Delphi
   	You can also have a look at the website discussion forum
			
http://sp9auv.com/fudforum/

There are the screen from program
![scren_from_automatic_instal](https://cloud.githubusercontent.com/assets/16939175/13634298/faf311d4-e5f4-11e5-9249-93add1cc5ce3.jpg)

There are source in Delphi 
[SOURCE.ZIP](https://github.com/sp9auv/Install-automatic-MYSQL-all-component-and-configure/files/165038/SOURCE.ZIP)
But for proper analize this project you need all files with MYSQL files . It have dimension 
166 MB sou I cannot uploat this there , Downolad full version  from above link


