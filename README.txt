CONTENTS OF THIS FILE
---------------------

 * Notes
 * Using the Script


NOTES
-----

Before sending the legal documents to David
===========================================

+ Add the entries concerning the new taxonomy to the most recent XSLX file (e.g.: Taxonomies List 20200909.xlsx). Mark the added entries yellow.

+ Use the DOCX files as templates, update the content and add the date at the end of the file. Recent taxonomies always can be found in the "YYYY-MM-DD" folder.
  It reflects the actual progress. The date in the name of the folder marks the date on which the legal documents were sent to David Gast (e.g.: EBA 2.10 Phase2 Taxonomy -Third Party Software License Approval Form 20200909.docx).

+ In the same folder are also files stored, which David sends back (e.g.: Copy of Taxonomies List 20200909 DAG.xlsx).

+ Add a TXT file to the current directory containing the contents of the mail David sent in reply (e.g.: EMAIL 20200909.txt).

+ Example of how a folder should look like, if the David is already informed about the new taxonomies:

  2020-09-09
    |- Taxonomies List 20200909.xlsx
    |- BOE 2.1.0 Insurance Taxonomy -Third Party Software License Approval Form 20200909.docx
    |- Copy of Taxonomies List 20200909 DAG.xlsx
    |- EBA 2.10 Phase2 Taxonomy -Third Party Software License Approval Form 20200909.docx
    |- EIOPA Pension Funds 2.5.0 Taxonomy -Third Party Software License Approval Form 20200909.docx
    |- EIOPA Solvency II 2.5.0 Taxonomy -Third Party Software License Approval Form 20200909.docx
    |- EMAIL 20200909.txt
    |- ESMA ESEF Taxonomy 2019 -Third Party Software License Approval Form 20200909.docx
    |- FASB 2020 SEC Reporting Taxonomy -Third Party Software License Approval Form 20200909.docx
    |- ...

NOTE : David needs a bit more time to approve license approval documents.
       IMPORTANT: Send approvals only every second or third month in year, not to interrupt workflow.

       Respect this: All are approved. Feel free to update the xls document with the links to the licenses. I either
       found the license or used the Legal or Disclaimer policies.  All of which support our use and
       distribution of the taxonomy.


USING THE SCRIPT
----------------

Current Maintainer: XML/XBRL Standards Maintainer

The scripts allows the user to automatically generate a license approval
forms for David Gast. It is necessary to send the approval to him after a 
new version of a taxonomy packages was released by the provider. Updates
(minor) versions and hotfixes are not necessary to report.

Project creation: Python v3.10.7

