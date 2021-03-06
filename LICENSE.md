Omnik PHP Class : Terms of Use
==============================

Running this script(s) is on your own responsibility. Any claim of damaging your hardware and/or software configuration will be rejected/declined;

You may freely change and/or distributed this set of scripts but do not forget to thank all others who partipated to make this work.

Although I wrote this series of scripts, I used ideas, algorithmes,etc from other developers, google, github, etc.

IMPORTANT : ONLY WIFI Modules with s/n 602xxxxxx support direct access thru port 8899! 

Special credits to https://github.com/woutrrr/omnik-data-logger (Wouter van de Zwan) for the python version.
		
If you plan to swap your WIFI module be very carefully:

1. 	switch off the power/current at the DC- and AC-side;
2. 	replace the module;
3. 	check the antenna;
4. 	switch on DC and AC side and check the (green!) leds on the WIFI module;
5. 	re-configure the WIFI module;
6. 	do not forget to update the omnik-portal website with your setting (new serial-number, but same inverter id);
7. 	you should not lose any data on the omnik_portal website;
8.	it is a good practice to backup omnik-portal data (use the export function)
			
These scripts are tested and running in:

1. 	Windows 8 with Apache 2, PHP 5.3 and MySQL 5.1;
2. 	Unix Debian Wheezy with Apache2 (and Lighttpd), PHP 5.4 and MySQL 5.5.30 on a raspberry pi model b 512mb;
3. 	a i386 pc running Debian Squeeze with Apache2, PHP 5.4, MySQL 5.5.30;
3. 	you can add the script to your UNIX crontab either via php cli or 
4.	run w3m http://localhost/yourwww/inverter_sample.php >>output.html
5.	w3m is a text-based browser that runs from the command-line
6.	crontab for windows : use windows task scheduler or consider installing http://www.kalab.com/freeware/pycron/pycron.htm
7.  Attention : Reading the 8899 port in intervals of less than 2 or 3 seconds might cause a buffer returned with only x'FF' values or other undetermined values. Normally 5 seconds or higher works fine
8.	Mac OS not even tested, no plans for it at all
			
Feedback may be send via GITHUB (English please)
				
@Copyright : V.H. Lemoine
