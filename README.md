# Protocols Manager
GLPI Plugin to make PDF reports with user inventory.
## Features
* Making PDFs with all or selected user inventory
* Saving protocols in GLPI Documents
* Possibility to create different protocol templates
* Templates have configurable name, font, logo image, city, content and footer
* Possibility to make comments to any selected item
* Showing Manufacturer (only first word to be clearly) and Model of item
* Showing serial number of item or inventory number if serial number doesn't exist
## Compatibility
GLPI 9.3 or higher
NOTE: in GLPI 9.3.x, you have to modify /inc/generate.class.php - search and replace: GLPI_UPLOAD_DIR to GLPI_TMP_DIR.
## Instalation
1. Download and extract package
2. Copy protocolsmanager folder to GLPI plugins directory
3. Go to GLPI Plugin Menu and click 'install' and then 'activate'
## Updating
1. Extract package and copy to plguins directory (replace old protocolsmanager folder)
2. Go to GLPI Plugin Menu, you should see 'to update' status.
3. Click on 'install' and then 'activate'
## Preparing
1. Go to Profiles and click on profile you want to add permissions to plugin
2. Select permissions and save
3. Go to Plugins -> Protocols manager
4. Edit default or create new template: Fill all or some textboxes, choose your font and logo if you want
5. Save template / templates
## Using the plugin
1. Go to Administration -> Users and click on user login
2. Go to Protocols Manager tab
3. Select some or all items
4. Write a comment to item if you want
5. Select your template from list and click "Create"
6. Your protocol is on list above now, you can open it in new tab. It is available in Managament -> Documents too.
7. You can delete all or some protocols by selecting them and click "Delete".
## Notes
1. Generated items depends on what you assign to the user in GLPI
2. You can edit template core in HTML by editing template.php file in protocolsmanager/inc directory
## To do
1. More customization
2. Possibility to add custom row
3. Possibility to change showing serial and inventory number in one or two columns
4. Possibility to add custom columns
## Contact 
mateusznitka01@gmail.com
