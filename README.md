
<b>1.before run this script, you have to create group and hadoop user first, and you have to add the user into sudoer.<br>
such as</b>:<br>
	<i>sudo addgroup hadooop</i><br>
	<i>sudo adduser --ingroup hadoop hadoop</i><br>
	<i>sudo visudo</i><br>

<b>when you created the hadoop user, you have to download the hadoop package and set up the settings in the script.</b><br>

<b>!notice!:this script is only run on ubuntu(it use apt to install environment)
if you want to run it on other linux, you can install them by yourself and delete
the line 12 and line 26 which about the apt installation</b>