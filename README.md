# Tableau-prep-automation-using-command-line

Tableau prep is an ETL tool which allow us to extract data from variety of  sources, transform that data and then output that data in hyper\.te\csv format for further analysis.
 Tableau Prep is comprised of two products  i.e Tableau Prep Builder for building your data flows and Tableau Prep Conductor for scheduling , monitoring and managing flows across the organization.
Tableau prep conductor is paid version for scheduling refresh task. Good News is ….. we can schedule this task using task manager. Yes , you heard right. 
We can publish data source on tableau online and tableau server . we can  automate this task ,we can refresh this task using cmd on  windows. Here are some steps to do it.
Caution:
•	Tableau Prep Builder should  installed on server.
•	We can use this option for windows and mac.
•	Flows which include cloud connector won’t work  here.
•	This script supported starting version 2019.2.3.
•	Administrator privileges on the machine where you are running the flow.
 Preparation
•	Path where tableau pre is installed.
•	The path where tableau flow file is located.
•	If  you connecting to database then we need details like hostname (ip address will work), port if default no need to mention, username and password.
•	If we have uploaded the data source on server or online then we need server url , site url ,port number, username and password (which you used to see dashboard).

Find a folder
•	Simple workflow on our machine. Check simple file.
•	If input is excel and output is tableau server then check into no_input_connection  file.
•	If input is datasource and output is tableau server then check into input_connection folder.
•	If input connection has multiple data sources connection and output is tableau server then check into multiple_input_connection folder.

Issue
•	You can raise issue in issue . I  will try to help you. Else you can reach me on linkedin or gmail.
•	One mail away : rutujauttarwar1996@gmail.com
•	Linkedin: https://www.linkedin.com/in/rutuja-uttarwar-84a81a129/

