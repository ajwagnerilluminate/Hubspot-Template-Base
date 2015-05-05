# Setup Process
This is the setup file for the base Bootstrap theme
As of the time of this writing, the included components are at the following versions:

Bootstrap:   3.3.2
Fontawesome: 4.3.0

Steps
==================================
If updating the BS or FA libraries, then make sure that the customizations noted below
==================================

 1. In ./start.sh, update the portal ID and the API Key.
 2. Open Terminal and browse to this folder, and execute "sh start.sh"
 3. Ensure that the initial files upload properly to the Hubspot Portal.
 4. Using the output from the fontawesome file uploads, edit the "@fa-font-path" 
 	variable in ./less/fontawesome/variables.less
 5. Using that same base path, update the "@img-path" in ./less/styles.less