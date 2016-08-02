# Opening Git repository folders in Textastic 6.2

It is now possible to open entire folders from the iOS Git client [Working Copy][working_copy] in [Textastic][textastic] using the [iOS document picker][document_picker]. Previously you could only open individual files.

These are the steps necessary to open a Git repository in Textastic 6.2:

* Make sure [Working Copy][working_copy] is installed on your device.
* Tap on "Open…" in Textastic.
* Select "Working Copy".  
  <img src="img/screenshot_locations.png" alt="" style="max-width: 100%; max-height: 300px" />
* Navigate to an existing Git repository or clone/initialize a new one.
* Tap on "Pick" to open the repository.  
  <img src="img/screenshot_pick.png" alt="" style="max-width: 100%; max-height: 500px" />
* The repository is now added as an external folder below the "Open…" command.  
  <img src="img/screenshot_external_folder.png" alt="" style="max-width: 100%; max-height: 300px" />

It can be used just as "Local Files" or "iCloud": You can edit existing files and add new ones. You can download and upload files. Web preview is fully supported. Changes you make will be immediately shown in Working Copy. You can then commit your changes in Working Copy. This works great in Split View mode on the iPad.


You can see this in action in the short video at http://bit.ly/textastic62

[textastic]: https://www.textasticapp.com
[working_copy]: https://workingcopyapp.com
[document_picker]: https://developer.apple.com/library/ios/documentation/FileManagement/Conceptual/DocumentPickerProgrammingGuide/Introduction/Introduction.html