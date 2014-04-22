ContaoDMS - Customization
=========================

Some helping files and instructions for customizing the [[Contao DMS]](https://github.com/ContaoDMS/dms).

In case there are issues, please use the [tracker](https://github.com/ContaoDMS/customization/issues).


Files
-----

### CSS

- See `css/dms.css` as an example to style your dms frontend.

### Templates

See `templates` for different customized templates.

- _Last documents_

	Use `templates/last_documents/mod_dms_listing_last_documents` in combination with the listing module to list the last documents.
	The access right will be checked, so only accessible documents will appear in the list.
	Change the variable `$maxDocuments` at the top of the template, if more or less then 10 documents should be shown.

	**!!! Attention: The module with this template could not be used within the same page, where the normal listing module (with category structure) ist placed !!!**

- _Last documents extended_

	Use `templates/last_documents/mod_dms_listing_last_documents_extended` in combination with the listing module to list the last documents with extended information.
	The extended version displays some more information, has additional variables and shows an icon at each document which is new since the last login auf the actual user.
	The access right will be checked, so only accessible documents will appear in the list.
	Change the variable `$maxDocuments` at the top of the template, if more or less then 10 documents should be shown (set to zero for an unlimited list of documents).
	Change the variable `$maxDocNameLength` at the top of the template, if the document name should be cutted (set to zero for the complete name).

	**!!! Attention: The module with this template could not be used within the same page, where the normal listing module (with category structure) ist placed !!!**
