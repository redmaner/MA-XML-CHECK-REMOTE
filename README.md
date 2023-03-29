What is this for?
-------------------------------------------------------------------------------------
This reposirory makes it possible to partially control <a href="https://github.com/Redmaner/MA-XML-CHECK" target="_blank">MA-XML-CHECK</a><br>

system.conf
-------------------------------------------------------------------------------------
This file contains 2 parameters which will be individually explained.<br><br>
<b>SYSTEM_UPDATE</b><br>
If this parameter is set to true, the script will update itself using git pull.<br><br>
<b>LANGUAGE_CONF</b><br>
If this parameter is set to true, the script will recreate languages.conf.<br>
This function can be usefull to cleanup languages.conf over time<br>

languages.conf
-------------------------------------------------------------------------------------
This file controls the languages in MA-XML-CHECK.<br>
By setting a language parameter to "wipe" the script will automatically wipe this language and resync the language.<br>

