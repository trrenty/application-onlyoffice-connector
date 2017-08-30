# OnlyOffice Connector application

* Project Lead: [Caleb James DeLisle](https://www.xwikisas.com/xwiki/bin/view/XWiki/cdelisle) 
* [Issue Tracker](https://jira.xwikisas.com/projects/ONLYOFFICE) 
* [Development Practices](http://dev.xwiki.org/xwiki/bin/view/Community/DevelopmentPractices) (as much as you can !)
* Minimal XWiki version supported: XWiki 8.4
* License: Proprietary - Copyright XWiki SAS
* Translations: N/A 
* Sonar Dashboard: N/A 
* Continuous Integration Status: [![Build Status](http://ci.xwikisas.com/buildStatus/icon?job=application-onlyofficeconnector)](http://ci.xwikisas.com/job/application-onlyofficeconnector/)

# Description

Edit attachments with OnlyOffice directly in XWiki. Supports doc, docx, xls,
xlsx, pps, ppsx.

* Converted to a paying application from [xwiki-labs/xoo](https://git.xwikisas.com/xwiki-labs/xoo)
* Minimal XWiki version: 8.4
* Translations: N/A

# OnlyOffice CORS
In order to use this connector, OnlyOffice must be setup using CORS
(cross-origin-resource-sharing). You can enable this by putting a proxy in front
of OnlyOffice or you can change the OnlyOffice nginx configuration file:
/etc/nginx/includes/onlyoffice-documentserver-docservice.conf to the content of
the supporting file by the same name.