# Galen
Trying out Galen Framework for UI Automation with Galen version 2.0.7

Installing Galen:
Download and install galen from the following link

galenframework.com/download/

Verify the installation using the following command

galen -v

To run the test, use the following command

galen test <NameOfTheTestFile> --htmlreport <ReportFolderPath>
eg:
galen test GalenDemo.test --htmlreport html-report

To run the spec file alone, use the following command

galen check <Name of the spec file> --url <URL of the website> --size <Resolution> --include <RelevantTags> --htmlreport <ReportFolderPath>
eg:
galen check GalenDemo.spec --url http://www.pranathib.com --size 1240x1080 --include "desktop" --htmlreport html-report
