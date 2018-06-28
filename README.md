# qquota_notify
The qcheck_hard.py script will check the hard quota usage on a Qumulo storage system, email the owners of the quotas if the quotas become full or reach a certain threshold, and create a log file of those quotas. 

Tested with Python 2.7.3 and newer with qumulo_api bindings, and Qumulo Core 2.6.0 and higher.

Copy the config.json.example to qconfig.json and edit to suit your site. You can also edit the email message text inside the qcheck_hard.py script. 

No warranty expressed or implied, yadda yadda. 
