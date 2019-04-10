Folder guidelines:

	- Put general usable codeunits in a root folder: _Libraries
	
	- There can only be 1 PageExtension per page in one Nav .app so put PageExtensions in a root folder so they are easy to find: Page Extensions
	  
	- There can only be 1 TableExtension per table in one Nav .app so put TableExtensions in a root folder so they are easy to find: Table Extensions
	  
	- It might be a good idea to create a folder per object type (codeunits, pages, etc.), but there are no official guidelines so far.

	

Filename guidelines:

	- Name TableExtension files according to the table, which is extended. For example "32 Item Ledger Entry.al".

	- Name PageExtension files according to the page, which is extended. For example "21 Customer Card.al".

	- Name other objects files with #ObjectNo #ObjectName. For example "50000 NP Retail Management.al"


Development guidelines:

	- To avoid conflicts in object names, it might be a good idea to prefix all new objects with customer initials
	
	- Remember to generate a unique .app id with AL: Go! and append it to app.json

	- There are no general AL coding guidelines so far.
