Front-End Naming Conventions
============================

This document aim is to define naming conventions for the folders, files and code written in the project in order to standardize the understandings in team following best practices.

Folders/Files
============================
-	All lowercase folders and filenames
-	Don't use spaces in the filename (dash is OK for a word separator)

File names
----------
JS file names will follow jquery naming format.

module-name.ver.sion.filetype.js

module-name can represent namespace and a module. The version and filetype are usually optional.
filetype can be something relative to how the content of the file is. Often seen are:

-	min for minified files
-	custom for custom built or modified files

####Examples:
-	jquery-1.8.2.min.js
-	jquery.plugin-0.1.js
-	myapp.invoice.js
-	gn.prayer-times-1.1.0.min.js

Folder structure
----------------
-	All folders will be under one [root] folder. 
-	First level of separation will be based on files types: 
  *	js: for JavaScript files
  *	css: for cascading style sheet files
  *	img: for image files (all kind of images)
  *	json: for json files
  *	xml: for xml files
-	Second level for JS files based on functionality 
	
JS Code Convention 
==================
JavaScript coding convention is inspired by the Douglas Crockford Conventions with some customizations and extension. 

Cont..

