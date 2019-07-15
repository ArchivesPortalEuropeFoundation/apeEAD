# apeEAD
March 2019: 
This repository is meant for maintenance of apeEAD, the profile of EAD 2002 currently used in the Archives Portal Europe (APE). 
Change requests to the schema or the conversion to apeEAD from local EAD and XML formats can be added here. 

The Working Group on Standards (WGoS) will then include these change requests in their monthly meetings, usually held on the third
Tuesday each month. WGoS will then decide on the best way to address the issue (either by a change of schema or a change of conversion
or a combination of both) and will also take aspects of indexation and display, where required. See the WGoS Best Practices Code (https://github.com/ArchivesPortalEuropeFoundation/apeEAD/blob/master/2019_WGoS_BestPracticesCode.pdf) for more information on the working group processes.

When reporting an issue, the following should be provided:
* Name and place of the specific element / attribute, that needs to be changed
* Name(s) of (all) parent elements where a new element should be added to the schema or conversion
* Any attributes that should be used with the new element, plus suggestions for specific default values (if applicable) 
* Description why it needs to be changed
* Example for usage of the changed element (including potential attributes) in the portal (use case)
* Example of XML code to such a request (in case of a conversion issue, the XML should ideally show the way an issue is dealt with now 
  and the way one would like it to be dealt with in the future)


Note 1:
More comprehensive information and documentation on apeEAD can be found in the Archives Portal Europe Wiki  http://wiki.archivesportaleurope.net/index.php/apeEAD

Note 2:
Technical information (schema and conversion scripts) can be found in our other repositories here on GitHub  
* Schema: https://github.com/ArchivesPortalEuropeFoundation/ape-dpt/tree/master/DPTutils/src/main/resources
* Conversion script: https://github.com/ArchivesPortalEuropeFoundation/ape-dpt/tree/master/xsl
* HTML display in the Archives Portal Europe: https://github.com/ArchivesPortalEuropeFoundation/ape-frontend/tree/master/ape-portal/src/main/resources/xsl
