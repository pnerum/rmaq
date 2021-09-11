# rmaq
Remove Apple Quarantine tool

This tool scans a folder for macOS installer packages and lists the following:
* Search for Apple installer packages
* Checks if the com.apple.quarantine is set for the found packages
* Asks if you want to remove it
* checks again if the attribute is gone
* exits

Add this script to a folder that's known to the $PATH variable to make things easy.
Run the following:
`rmaq /path/to/downloaded-items`



