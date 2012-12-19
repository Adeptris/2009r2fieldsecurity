2009r2fieldsecurity
===================

Dynamics NAV Field Level Security

Project to create a set of tables, forms, pages and codeunits to have field (control) level security ...
These controls are text box, checkbox, menu button, subform, image box etc:

Starting with version 2009 R2

Process:
1. Export the page or form in Type-ID.txt as text from the Object Browser
2. Import the object into a template, this will find all the controls that can be managed
3. Remove any controls that do not need object level control
4. Merge the code into the object as text that can be imported into the object designer
5. Create any number of profiles that have control conditions
6. Add users to the profiles and test   
