# Extreme Networks Automation
Automation Examples for Extreme Networks Operating System. Tested using x440-g2-12p-10ge4 hardware. I am using the same readme template as the offical [Extreme Networks Scripting Repository](https://github.com/extremenetworks/ExtremeScripting/tree/master/EXOS/Python). However, all the automation scripts here are developed by myself.

## Helpful Documentation
* [Extreme Networks Documentation](https://www.extremenetworks.com/support/documentation/)
* [Python Getting Started Guide](https://documentation.extremenetworks.com/pdfs/exos/Python_Getting_Started_Guide.pdf)
* [The EXOS Python API](https://www.extremenetworks.com/support/documentation-api/extremexos-software/)

<!---
------git_dlownload.py------
To allow git_download.py to find the scripts add the script to this list with no spaces for the table like autofsbackup does.
Add a space at the begining of the Description to omit the script from git_download. (see jsoncli)
-->

## Python Scripts
| Script name   | Description   |
| ------------- |:-------------:|
|[GitHub Script Downloader](git_download)|Downloads python scripts located on this page directly to your switch.|

## Extreme .lst File - 
This .lst file includes all of the switch .py scripts at the time of the file upload.  It can be downloaded directly to the switch with the ```download url <url> <vr>``` command.  The .lst will create a folder called gtac and add all the scripts into that folder.  Note: To run the scripts you need to cd into the gtac folder.
* [Haid-Script-Index.lst]
