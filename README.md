Pic16a1(f886)nRF24AP2__180904a
====
# recoder (TOP LATEST)
- ...
- //04SEP2018 ANT library v0,1
1. added ant folder and include ant head in main file
2. added antInterface (c,h) interface files to if folder
3. added halAnt(c,h) hal file to hal folder
4. added ant files include in main.c file
- //03SEP2018 CLONE PROJECT FOLDER and zip as release (#Pic16n1(f886)nRF24AP2__180830a.hex)
- //03SPE2018 as release nRF24AP2 Project skeleton revision
- //01SEP2018 skel v0,9 -> Pic16a1 (/)
----
# skeleton revision
+ -- skeleton (revision v0,9)
+		-- skeleton (v0,1 as first revision)
# pic16 toolkit 
* - uart
* - TxSW
* - (...)
# standard build all procedure
*	1. build all
*	2. success
*	3. menu/file -> export
*	4. click OK and save as work folder, hex filename:#Pic16n1(f886)nRF24AP2__180830a.hex
*	5. commit
# mercurial untrace file list:
*	1. main.* (exclude main.c)
*	2. oc2k.* (exclude oc2k.mcp)
*	3. untitled.mcw
# development environment
*	- winxp
*	- Mercurial as version control tools (git and svn is not available on winxp)
*	- mplabIDE v8.xx
*	- Picc compiler v8.02PL1
*	- Picc compiler recommend location: c:\pic\ht-pic
*	- work folder: c:\pic16a1
*	- assistance folder: c:\pic16a1ASS (include untitled.mcw backup, document and so on)
*	- microcontroller: pic16f886
*	- ant plus ic: nRF24AP2
# pin defines see ssdInit.h
	//-- RA ---------------
	//(1)RA0 -- A2D BATTERY MEASUREMENT
	//(2)RA1 -- A2D REFERENCE VOLTAGE MEASUREMENT
	//(3)RA2 -- IsHwDev1VCC
	//(4)RA3 -- IsHwTestFREQ
	//(5)RA4 -- IsHwDev2VCC
	//(6)RA5 -- IsHwDev1DR
	//(7)RA6 -- NA
	//(8)RA7 -- NA

	//-- RB ---------------
	//(1)RB0 -- , INT INTERRUPT SERVICE
	//(2)RB1 -- IsHwAntVCC, ANT Power control
	//(3)RB2 -- IsHwAntRESET, ANT Reset control
	//(4)RB3 -- IsHwPwrVCC, DC/DC control
	//(5)RB4 -- IsHwUartSelUSB, UART TX selection
	//(6)RB5 -- IsHwRefVoltASSERT, Reference voltage control
	//(7)RB6 -- SPARE
	//(8)RB7 -- SPARE

	//-- RC ---------------
	//(1)RC0 -- IsAntSuspendASSERTED, ANT SUSPEND CONTROL
	//(2)RC1 -- IsAntSleepASSERTED, ANT SLEEP CONTROL
	//(3)RC2 -- IsHwAntRtsAGREE, ANT RTS
	//(4)RC3 -- SCL (I2CM)
	//(5)RC4 -- SDA (I2CM)
	//(6)RC5 -- IsHwDev1INT
	//(7)RC6 -- TX (SCI)
	//(8)RC7 -- RX (SCI)
****
