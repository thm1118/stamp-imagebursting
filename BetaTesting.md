## Verify Installation ##

  * Download the application from the site by clicking the download button.
  * Verify the application starts Java.  You will be prompted to run the application and will then be asked whether you accept the signing authority which is unverified (I do not maintain a verification certificate)
  * The application should shortly appear with a main frame.
  * Close the application
  * An application startup folder called "Stamp Applications" should have been created with a shortcut named "Stamp Image Bursting Application".

## Verify Re-Launch ##

  * Verify that clicking on the "Stamp Image Bursting Application" icon from the desktop folder will launch the application.
  * You will be promoted for the digital certificate being unverified again.

## Basic Functional Testing ##

  * Start the application and choose "Import from File" and choose a file on your local system which lists the burst directories.  The download website has a sample file you can use if you wish.
  * Load a scanned image of stamps using the Open toolbar icon.  (Some samples have been uploaded to the website [here](http://code.google.com/p/stamp-imagebursting/downloads/detail?name=sample_images.zip&can=2&q=))
  * The image should be parsed and burst boxes will be drawn.  You may need to use the zoom out feature in order to see the stamps and/or boxes depending on the scan resolution.
  * Test the resizing of the burst box by selecting a box and changing the size by dragging the corners.
  * New boxes can be added with the New Overlay button in the toolbar.  The new overlay will be a small box that will likely need to be resized and moved.
  * Clicking Next will move the application to the preview step.  In this step you can set a country value (this will be changing to folder in an update soon) on any burst stamp and specify a number (this will be changing to filename).  Only images that have both a number AND a country will be burst to disk.
  * Above the table is a country selection you can use to set the value on multiple values or clear all values with the "Reset" button.
  * Clicking the Burst button at the bottom of the page will prompt for an output root folder.  All images will appear in a folder under the folder using the country name as the folder name.
  * If a burst attempts to burst the same image that already exists, a conflicts dialog will be shown after bursting.  Unselecting a row in this dialog will no burst the image.

## Verify Uninstall ##

_Verify the application is not running_

  * Ensure the program is NOT running.  Close it/kill it if it is.
  * To uninstall the application go to your Java control panel.  On windows this is via the Programs under the Control Panel.  On the first tab, near the bottom is a "View" under "Temporary Internet Files".  Click this and it will show the Stamp Image Bursting Application.
  * If you select the application and click the "Remove" icon (X) verify the application is removed.  This should also include the application shortcut in the start bar.