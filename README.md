2009r2fieldsecurity
===================

Dynamics NAV Field Level Security

Project to create a set of tables, forms, pages and codeunits to have field (control) level security ...
These controls are text box, checkbox, menu button, subform, image box etc:

Starting with version 2009 R2

Process:
Export the page or form in Type-ID.txt as text from the Object Browser, Import the object into a template, this will find all the controls that can be managed, Remove any controls that do not need object level control, Merge the code into the object as text that can be imported into the object designer, Create any number of profiles that have control conditions,  Add users to the profiles and test   
