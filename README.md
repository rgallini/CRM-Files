# CRM-Files
Custom activity for attaching files to entity records

This is an implementation of crmDropZone started by @devbeard (https://github.com/devbeard/dynCrmDropZone).
The files from his project have been updated for CRM 2016 on-premise and added to a new activity entity for adding files.

To use: Import the unmanaged solution, publish customizations

Changes to dynCrmDropZone:
1. I updated the script in the web resource to hide the notes tab and show the tab with the web resource. Having the web resource always showing could be confusing to end users.
2. Two CSS tweaks to make it show better on the form.

Notes on the solution:
1. The ribbon has been customized to only show "Save and Close", which actually calls SavePrimaryActivityAsComplete so the record is closed once it is saved.
2. Other ribbon buttons have been hidden for simplicity. If you want to show them, use the Ribbon Workbench to unhide them.
