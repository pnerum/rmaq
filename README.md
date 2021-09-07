# rmaq
Remove Apple Quarantine tool

This tool scans a folder for macOS installer packages and lists the following:
* Found packages and counts the found items
* Packages containing the com.apple.quarantine bit set with a count

When this is finished it will ask you to remove the quarantine bit set by using `xattr -dr`

Add this script to a folder that's known to the $PATH variable to make things easy.
Run the following:
`rmaq /path/to/downloaded-items`



