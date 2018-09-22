# fso2db
Archives / backups / revision flexibly files, folders, links etc (file system objects - FSOs) to an embedded database.
* A project file controls which file system objects are to be archived and revisioned.
* Every FSO obtains a GUID. 
* When the project will be revisioned then all FSOs are saved and every FSO obtains the same revision number (GUID or similar).
* Every version of a FSOs is saved completely without saving differences etc, for simplicity reasons. 
* Every FSO revision is saved in a table sentence.
