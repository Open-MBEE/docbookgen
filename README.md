This project contains resources to transform docbook to PDF and HTML.

view-repo's generating snapshot artifacts uses resources from this project.

To use the resources:

    - Local DEV environment:
        - checkout the project from JPL GitHub into your git directory; typical path is /home/[USERNAME]/git/docbookgen/.
    
    - EMS Server:
        - checkout the project from JPL GitHub into /opt/local/docbookgen directory.
        
        
Unknown issue:

    - Be sure the account (i.e.: alfresco or root) running alfresco has read permission to docbookgen directory.
      In addition, be sure docbookgen/for-1.0/fop properly set with execute right. 
      If it's not, issue the command chmod u+x,g+x,o+x fop