EMF Annotated USAHA ECVI Schema
===================

Introduction
------------
The [USAHA eCVI subcommittee](https://github.com/tracefirst/usaha_committee) has modeled the standard for Electronic  
Certificate of Veterinarian Inspection information as an [XML Schema](http://en.wikipedia.org/wiki/XML_Schema) meta-model. XML instance documents 
that validate against this schema are standard compliant. 

Need for Additional Functionality
------
Validating eCVI XML instance documents against the eCVI schema only insures the basic standards of XML syntax and document structure. Validation 
against the eCVI schema does not insure that any business rules agreed upon by exchanging producer and consumer business entities are met. 

To exchange and validate business rules a second level of model (document) processing and validation is required.

EMF
---
The Eclipse Model Framework [EMF](http://www.eclipse.org/modeling/emf/) is an industry standard suite of meta-model tools and component generators
compatible with XML Schema models that can be used to generate application components, utilities and applications that provide functionality for loading, persisting and transforming documents and resources; visual editors for the
creation and editing of eCVI documents; referencing, extending and integrating eCVI document information into other applications; and a facility 
for adding higher level eCVI business rules and validation services.

Generating Code from the XML Schema Meta-Model
-----------------------------------------
EMF provides a simple dialog driven process for generating the above mentioned components and runtime utilities from an XML Schema.  
[This Article](http://techblog.goelite.org/generating-an-xml-editor-based-on-xsd-using-emf/) documents the process.

To specify to the code generators more conventional class names for the generated components this project provides a XML Schema that 
adds Eclipse Model Framework [EMF](http://www.eclipse.org/modeling/emf/) annotations to the XML schema created by 
the [USAHA Ecvi subcommittee](https://github.com/tracefirst/usaha_committee) use it in the generation process.

Verticon Integration
--------------------
If you would like to skip the process of generation and just try out the generated components in an Eclipse workspace 
see the Verticon specific project details and installation instructions 
[desktop.ecvi.beta.0.1 Milestone](http://tracker-project.verticon.com/verticon_Tracker/milestone/desktop.ecvi.beta.0.1)

If you have comments to make on this annotation work, you should use the Trac Ticket that is associated with it. -- you can access it
here: [Ticket:913](http://tracker-project.verticon.com/verticon_Tracker/ticket/913)of generated components see the 



Thanks.
