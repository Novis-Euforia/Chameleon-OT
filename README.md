
# ABAP Transport Order for Chameleon
## Prerequisites
SAP APPL with minimum version 600 or S4CORE any version.

SAP_UI with minimum version 740

SAP_BASIS with min. version 740

## Import instructions
Download the Chameleon V1.10.zip file with the Chameleon transport requests.

Import the files into the corresponding import directories of the TMS on the application Server: /usr/sap/trans/data and /usr/sap/trans/cofiles.

From STMS Add the transport order S4HK901651 to the import Queue using Extras->Other Request Add
Import the command from the STMS transaction with the following options.

![Import Options](https://raw.githubusercontent.com/Novis-Euforia/Chameleon-OT/main/ot%20import.png)
