##### Errata for

<center>MACRO SPITBOL<br>The High-Performance SNOBOL4 Language<br>Manual text by Mark B. Emmer and Edward K. Quillen with additional material by Robert B.K. Dewar<br>Catspaw SPITBOL program by Robert B.K. Dewar, Mark B. Emmer, and Robert E. Goldberg.<center>

<center>23 January 2026</center>

A list of corrections and undocumented information to the manual for *MACRO SPITBOL The High-Performance SNOBOL4 Language*. The page numbers are the logical page number printed on the upper corner and not the page number assigned by Adobe Acrobat. The line numbers are from the top of the page and skip blank lines.

Brackets ([ ]) surround comments about corrections.

The corrections given here may not be complete. We appreciate having other documentation errors reported. 

| Pages | Lines | Current Text                               | Replacement Text                                             |
| :---: | :---: | :----------------------------------------- | :----------------------------------------------------------- |
|  111  |  21   | Blanks are not permitted in the prototype. | Blanks are permitted in he prototype. Leading and trailing blanks surrounding the datatype name and each field name. Spaces within identifier names are accepted as natural variables, but require indirection ($) to access. |
|  219  |  11   | Blanks are not permitted in the prototype. | Blanks are permitted in he prototype. Leading and trailing blanks surrounding the function name, each arguments, and each local are trimmed. Spaces within identifier names are accepted as natural variables, but require indirection ($) to access. Consecutive commas and commas separated by spaces are ignored <br><br>The function name must not be the same as a built-in function, or an error 248 will result (Attempted redefinition of system function). |
|       |       |                                            |                                                              |
|       |       |                                            |                                                              |

