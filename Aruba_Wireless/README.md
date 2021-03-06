# Sumo Logic for Aruba Wireless

![ArubaWireless-Controller-AuthMgr](ArubaWireless_Controller/Screenshots/ArubaWireless-Controller-AuthMgr.png)

Contains all Aruba Wireless technology and product lines for which Sumo Logic has content for.

See [Sumo Logic Documentation](https://help.sumologic.com/) for instructions on how to collect logs and metrics for use with content.

## Additional Dashboards

![ArubaWireless-Controller-WMSModule](ArubaWireless_Controller/Screenshots/ArubaWireless-Controller-WMSModule.png)

![ArubaWireless-TACACS](ArubaWireless_TACACS/Screenshots/ArubaWireless-TACACS.png)

To use the content:

Download the raw JSON file(s) and search for (CTRL+F / CMD+F) "$$Aruba" to replace with  "sourceCategory=yourSourceCategory".

Guidelines PLEASE READ:

To contribute to subfolders or create new subfolders here, please follow the standards below:

1. All application, dashboard and search content in .json format. Please use descriptive naming such as:
   a. Company_TechnologyLine_ContentFunction. E.g. AWS_Kinesis_Errors.json or Sentinel_Vanguard_All.json

2. Relevant screenshot(s) in .png or equivalent format. Naming similar or equivalent to .json content it represents.

3. Create/update a README.md file (like this one) within the folder to track:
   a. Technology and product lines, authors, versions, etc.
   b. Link(s) to relevant 3rd party documentation to specify what types of data need to be collected for content to work.

For more information, see Aruba documentation here:
[Aruba logging](http://www.arubanetworks.com/techdocs/ArubaOS_64x_WebHelp/Content/ArubaFrameStyles/Management_Utilities/Configuring_Logging.htm)

2018/04/10 - Updated

  Added Aruba Wireless Controller and TACACS dashboards - author: Jason Hwa
