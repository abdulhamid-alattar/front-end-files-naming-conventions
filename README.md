Front-End Naming Conventions
============================

This document aim is to define naming conventions for the folders, files created in the projects in order to standardize the understandings in team following best practices.

General File and Path Naming
============================
Any document to be created with the module / project should contain a fully qualified name. The format of the name will follow this pattern to allow easier management.


Folders/Files
============================
-	All lowercase folders and filenames / No special characters
-	File names always starts with an alphabet
-	Don't use spaces in the filename

File names
----------
- HTML File Names
	* No special characters. Allowed only letters a-z, A-Z, the numbers 0-9, hyphens ( - ), underscores ( _ ) and periods ( . )
	* No spaces in the name
	* Start file name with a letter
	* All lower case
	* Keep them short but descriptive
	* Extensions are .html or .htm
	* File names for pages should be easily read and understand

 - CSS File names
 - SCSS File names 
 - JavaScript File names 

module-name.ver.sion.filetype.js
module-name can represent namespace and a module. The version and filetype are usually optional.
filetype can be something relative to how the content of the file is. Often seen are:

-	min for minified files
-	custom for custom built or modified files

####Examples:
-	jquery-1.8.2.min.js
-	jquery.plugin-0.1.js
-	myapp.invoice.js
-	GN.prayer-times-1.1.0.min.js
-	gold.css

Folder structure
----------------
- All folders will be under one [root] folder.
- Htmls will be under the root folder.
- First level of separation will be based on files types:
	* js: for JavaScript files
	* css: for cascading style sheet files
	* scss: for sass files
		* base: base files
		* modules : module specific files
		* utilities : utilities that can be used across all
		* vendor : third party and frameworks
	* img: for image files (all kind of images)
		* bg: background images
		* content: content images
		* generic: generic images
		* icon: icons and sprites
	* json: for json files
	* xml: for xml files
	* fonts: fonts
	
Versioning
==================
Versioning is the creation and management of multiple releases of a product, all of which have the same general function but are improved, upgraded or customized. 

Given a version number MAJOR.MINOR.PATCH, increment the: 

- MAJOR version when you make incompatible API changes
- MINOR version when you add functionality in a backwards-compatible manner
- PATCH version when you make backwards-compatible bug fixes

The version will be concatenated to the file name, as well as the release document and must go in the JS/CSS resources links
[Type]_[Name].vX.Y.Z
Example: w_retailgold.v2.1.1
- X: Major release (contains changes on the way the module is implemented or API changes)
- Y: Minor release (adding changes in the functionality or enhancement without actual change on the how to implement or API)
- Z: PATCH version when you make backwards-compatible bug fixes

Semantic Versioning Specification (SemVer)
------------------------------------------
The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be interpreted as described in [RFC 2119](http://tools.ietf.org/html/rfc2119).

[Reference](http://semver.org/)

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/abdulhamid-alattar/front-end-naming-conventions/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

