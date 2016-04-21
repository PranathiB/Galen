# Galen
This project uses Galen Framework for UI Automation with Galen version 2.0.7

#####Installing Galen:

Download and install galen from the following link

http://galenframework.com/download/

#####Verify the installation using the following command
```
galen -v
```
#####To run the test, use the following command

galen test NameOfTheTestFile --htmlreport ReportFolderPath

Example:
```
galen test GalenDemo.test --htmlreport html-report
```
#####To run the spec file alone, use the following command

galen check NameofTheSpecFile --url URLOfTheWebsite --size ResolutionOfScreen --include RelevantTags --htmlreport ReportFolderPath

Example:
```
galen check GalenDemo.spec --url http://www.pranathib.com --size 1240x1080 --include "desktop" --htmlreport html-report
```
